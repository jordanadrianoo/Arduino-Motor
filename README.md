# Arduino Motor

This arduino project is inspired by the "Arduino Projects Book" project 9 by Scogg Fitzgerald and Michael Shiloh. This project uses a 9-volt battery to power a small motor. When using a 9-volt battery, it is important to be cautious about backflow electricity. Backflow electricity can pipeline backwards within circuits and damage them. This project will show you how to properly use a motor with an Arunino Uno.  

# Getting Started
  
  **Prerequisites**:
  
  **Hardware:**
  
  - Arduino Uno
  - USB type B
  - Breadboard
  - Jumper Cables
  - Motor (within 1.5-3.0 Volts and 4200-5700 RPM)
  - 9-Volt Battery
  - Battery Snap
  - Diode 1N4007
  - Mosfet Transistor
  - Tactile Switch
  - 10 KILOHM Resistor  
  
<img src="Project images/Resistor-Chart.png" width="700" height="600">

 **Software:**
 
 - [Arduino API Downloads](https://www.arduino.cc/en/main/software)
 - [Windows Installation Guide](https://www.arduino.cc/en/guide/windows)
 - [IOS Installation Guide](https://www.arduino.cc/en/guide/macOSX)
 - [Arduino Uno Setup Guide](https://www.arduino.cc/en/Guide/ArduinoUno)

# Arduino Schematics

**Abstract Schematics**

<img src="Project images/Arduino Blueprints.jpg" width="700" height="500">

**Implimented Schematics**

<img src="Project images/Arduino Schematics.jpg" width="700" height="400">

# Back Voltage 

It is important to note that a motor can allow electricity to flow in either directions. If electricity is passed in the wrong direction it can damage resistors, circuits, and the motor itself. To prevent this occurrence, this project implements a gate pin and polarized diode. The gate pin stops flow of electricity until we decide to let it flow. With electricity from the Arduino, we allow the 9-volt battery's current to flow into the polorized diode. In addition, the polarized diode only allows currents to flow in a single direction. Both countermeasures prevents backflow from the motor.

# uploading to the Arduino

After downloading the [Source Code](Motor.ino) and Schematics is built, connect the Arduino to the computer using the UBS type-B cord. Open the source code within the Arduino API and hit upload in the top left corner. 

<img src="Project images/Upload .JPG" width="300">

# Sources and References

 - [Arduino](https://www.arduino.cc/)
 - [Arduino Uno](https://store.arduino.cc/usa/arduino-starter-kit)
 
