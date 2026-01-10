# Chapter 3
```plantuml
@startuml
MonitorTask--> GVL: tell water and moisture 
MonitorTask--> GVL: tell if water is needed
WaterTask--> GVL: Read water level, moisture and temperature
WaterTask--> GVL: Turn on the water, and the duration of it
@enduml
```