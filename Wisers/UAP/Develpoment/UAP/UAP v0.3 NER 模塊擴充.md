# 模塊更新

在現有的 NER 相關模組上進行擴充，增加更多版本的 NER 供使用者進行分類標記，且在不影響架構的前提下進行模塊擴充:    
```python
from package import NER, NERModel
NER(model=NERModel.model_a)
```
藉由枚舉類別提供使用者相關模塊說明、模型選擇。

###### tags: `development`, `ner`