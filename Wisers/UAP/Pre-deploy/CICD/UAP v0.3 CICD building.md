# CICD build

# Abstract 

討論並設計內部 Library CICD Stages, Step 及細節規範與準則。    
CICD 部屬以下幾項工作:
- Coding style check
- Package
- Upload internal Pypi server
- Testing
  - Document example code test
  - Unittest
  - Installation test on multi python version
- Documetation autogenerate

部屬之內容區分為 `PUSH`, `TAGS` 依照不同


## Keyword
- CI/CD
- 發布流程
- 測試
- 封裝
- Pypi
- 文件
- 文件自動化
- 代碼風格
- Docker