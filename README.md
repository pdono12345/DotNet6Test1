# DotNet6Test1

此專案為 .Net6 的練習專案

- 練習目標
  - .Net5 升級到 .Net6
  - Serilog 的使用
  - UniTest
  - 用 Docker 來部屬
  - 將開發流程整合進 Jenkins pipeline
    - git push 後會先經過 SonarQube 檢查語法
    - 必須通過 UnitTest
    - 用 Docker 部屬

- 流程

  code > git push > [ Jenkins_start] > SonarQube > UnitTest > Docker publish > [ Jenkins_end ]
  
- 歷程

  - 2022.06.20 建立 Jenkins 與 github webhook 的連結測試 1
