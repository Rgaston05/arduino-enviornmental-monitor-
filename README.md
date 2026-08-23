# Arduino Environmental Monitoring Station
An Arduino Uno-based environmental monitoring station designed to measure and display real-time environmental conditions including temperature, relative humidity, atmospheric pressure, and light intensity 

## Project Overview 
This project uses an Arduino Uno as the central controller for an environmental monitoring system. Sensors collect environmental data once per second, which is processed by the microcontroller and displayed continuously in real time

The system is intended to measure: 
- Ambient temperature
- Relative humidity
- Atmospheric pressure
- Light intensity

## Project Objectives 
- Measure environmental conditions using multiple sensors.
- Process sensor data using an Arduino Uno
- Calculate additional environmental values from direct sensor measurements.
- Organize environmental data into meaningful categories and trends.
- Design the system so individual sensors and software components can be tested independently

  ## Calculated Values

  The system will derive additional environmental information from the direct sensor measurement, including:
  - Dew point
  - Heat index
  - Temperature in Fahrenheit
  - Absolutely humidity
  - Sea-level pressure
  - Pressure trend
  - Estimated altitude
  - Light category
  - Daily minimum, maximum, and average values
 
   ## Hardware

  The system is built around an Arduino Uno and will use dedicated sensors for each environmental measurement.
  |Component      |                   Purpose                            |
  |Arduino Uno    |             Main microcontroller and data processing |
  |Temperature/Humidity Sensor| Measure ambient temperature and relative                                                                         humidity
  |Pressure sensor|        Measures atmospheric pressure                 |
  |Light sensor   |       Measure ambient light intensity                |
  |Display        |Display measurements and calculated environmental data|
  |Breadboard     |          Circuit Prototyping                         |
  |Jumper Wires   |         Electrical connection between components     |  
