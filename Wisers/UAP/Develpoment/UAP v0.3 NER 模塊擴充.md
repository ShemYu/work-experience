# 模塊更新

在現有的 NER 相關模組上進行擴充，增加更多版本的 NER 供使用者進行分類標記，且在不影響架構的前提下進行模塊擴充:    
```python
from package import NER, NERModel
NER(model=NERModel.model_a)
```

payload 自動修正功能，藉由使用者客製 function input，自動對照 payload 應該修正的 key 進行修正:
```python
from package import Module
Module.request(fix_function=lambda x:x[:1000])
```
當 catch Exception 時，就修正為前 1000 筆

## Keyword
- Development