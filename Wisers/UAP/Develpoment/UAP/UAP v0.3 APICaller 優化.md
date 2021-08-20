# APICaller optimized

1. payload 自動修正   
    使用者自定義錯誤處理方法，修正模塊 catch 到的 payload too long 相關錯誤:
    ```python
    from package import Module
    Module.request(fix_function=lambda x:x[:1000])
    ```
    ##### e.g. 當 catch Exception 時，就修正為前 1000 筆

###### tags: `development`, `API`, `optimize`