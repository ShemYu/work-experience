# 針對 Tutorials 進行測試、覆蓋度報表

# Abstract

為了解 Tutorials 覆蓋專案內部多少資源，呈現多少專案方法，    
因此需調研針對撰寫 Tutorails 之 jupyternotebook 應如何測試，  
且是否能整合進 `pytest`, `tox` 等套件進行統一管理，   
保證建置後的配置彈性。

調研數款 module 後，最後選用 pytest plugin `nbval`，    
它在實作上調用邏輯、測試方式與 `doctestplus` 類似，    
也提供不比對 `stdout` 之模式，非常適用當前僅需了解 `coverage` 之需求。

最後將其整併入當前專案使用之 `tox` 測試整合框架當中，方便針對不同環境進行統一管理與測試。

