# Chapter 1
```plantuml
@startuml

[*] --> Initial state
Initial state --> ReadSensors(Moisture level and temperature)
ReadSensors --> Changing variabiles
Changning variabiles --> ReadSensors : Loop
@enduml

```
