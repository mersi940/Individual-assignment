# Chapter 1
```plantuml
@startuml
[*] --> INIT
Init--> CHECK_SOIL: Start Task
CHECK_Soil--> UPDATE_GVL : Moisture read
@enduml

```