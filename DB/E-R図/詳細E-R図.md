```puml
@startuml
entity "学生" {
  + 学籍番号 [PK]
  ==
  氏名
}
entity "資格" {
  + 資格コード [PK]
  ==
  資格名
}
@enduml
```
