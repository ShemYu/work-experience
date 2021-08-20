# 內容


基於易用性將 APICaller 回傳結果區分為正確、錯誤:
- 需在修改最少代碼前提下修改回傳結果
  - 其他 module 使用 APICaller 取的回傳後，會從 response data 進行解析，因此略有難度

最終以繼承 tuple 客製化 iterator 的方法，保證 iterator 邏輯與修改前相同，但其他行為皆為 `tuple`


###### tags: `development`, `api`, `magic method`