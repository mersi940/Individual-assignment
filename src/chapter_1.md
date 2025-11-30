# Chapter 1
```plantuml
@startuml
[*] --> Init
Init --> ReadSensors(Moisture level and temperature)
ReadSensors --> Changing variabiles
Changning variabiles --> ReadSensors : Loop
@enduml

```
