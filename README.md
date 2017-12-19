# ZordProject
Mini-humanoid controlled by PS3 controller. Inspired by [Zord-project](https://github.com/Resaj/zord-project) by 
[Rubén Espino San José (Resaj)](https://github.com/Resaj)

Initially, the project included a redesigned Arduino Due with a bluetooth dongle for controlling via PS3 bluetooth controller. The dongle wass connected at microcontroller's native port and had the posibility to control 20 outputs for servomotors like SG-90; and 2 buses (UART and I2C) for bus servomotors like Dynamixel.

<p align="center">
<img src="images/First prototype (top).jpg" width="300" align = "center">
</p>

<p align="center">
<img src="images/First prototype (bottom).jpg" width="300" align = "center">
</p>

<p align="center">
<img src="images/First prototype (3D).jpg" width="300" align = "center">
</p>

The idea of the project consists in substitute the Arduino Due by a STM32F446, connect the bluetooth dongle to its native port, adapt the Arduino IDE and USB Host libraries for the new microcontroller and mount the electronics in a new humanoid chasis with litlle servomotors.

The project is only based on open source technology (Arduino, KiCad, FreeCAD/OpenSCAD).
