# 模塊更新

在現有的 NER 相關模組上進行擴充，增加更多版本的 NER 供使用者進行分類標記，且在不影響架構的前提下進行模塊擴充:    
- 加入列舉變數作為使用 model 參數
  ```python
  from enum import Enum
  class Models(Enum):
      model_name = model_api_reference
      ...
  ```
- 更新測試架構，減少測試代碼量增進可維護性
  ```python
  def test_a_model():
      a_model_instance = AModel()
      actually_test(a_model_instance)
  ...
  ```

## Keyword
- Development