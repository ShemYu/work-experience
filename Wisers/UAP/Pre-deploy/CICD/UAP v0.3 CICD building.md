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


  
###### tags: `CI/CD`, `deploy`, `test`, `package`, `pypi`, `documentation`, `doctest`, `sphinx`, `coding style`, `docker`