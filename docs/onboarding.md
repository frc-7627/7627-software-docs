# Onboarding

Welcome to the 7627 software onboarding guide!

## What does software do?

A robot that has merely been designed, built, and wired is not capable of anything. The missing piece is **software**, and it is your job as part of the software team to produce that missing piece. This will consist of two primary responsibilities:
* **Firmware Management** - As a prerequisite to ensure the software can talk to the hardware, the **firmware** must be properly installed and configured.
* **Programming** - To give the robot the instructions it needs in a form the it can understand, the robot must be **programmed**. We use the **Java** programming language for robot code. If you don't know how to program, in Java or at all, worry not! This documentation contains all the resources you will need to know.

## Prerequisites

You will need a laptop(not a Chromebook! Ideally a windows machine but linux may work in certain cases) and access to unrestricted Internet (not school managed wifi). Then, make sure you already have, or otherwise install, the following applications:

* [**WPILib**](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html) - An indispensable library and development environment for FRC software.

* [**NI Tools**](https://www.ni.com/en/support/downloads/drivers/download.frc-game-tools.html#581857) a NI account is needed to download - this will include all the basic apps you need to run a robot including Driver Station and Roborio imaging tool

* A **flashing software** of your choice. Some options are listed below:
  
  * [**Balena Etcher**](https://etcher.balena.io/) - Works, although deprecated.
  
  * [**Raspberry Pi imager**](https://www.raspberrypi.com/software/) - Software lead 2026 note: I haven't used this but I've heard it works for the job

* [**Rev hardware client**](https://docs.revrobotics.com/rev-hardware-client) - This is used to interface with REV hardware (no way) such as the sparkmax

* [**Rev hardware client 2**](https://docs.revrobotics.com/rev-hardware-client-2) - If your REV hardware is too new or you need some specific feature use this

* [**Phoenix tuner x**](https://github.com/CrossTheRoadElec/Phoenix-Releases/releases) - Can also be installed from the microsoft store, google play store, and apple store. - This is used to interface with CTRE hardware including, krakens, candle, pwm, pdp, IMU, Encoders, and more.

* [**Pathplanner**](https://github.com/mjansen4857/pathplanner/releases) - May also be installed from the microsoft store - this is an easy to use gui to program autonomous paths.

* **Roborio imaging tool** - this comes packaged within NI tools but is essential for robo rio stuff (Systemcore will replace robo rio as of the 2027 season) - This software allows you to update or start anew on a roborio (pray you do not need to use this more than once per season)

* [**AdvantageScope**](https://docs.advantagescope.org/overview/installation) - This is a software we use for log playback, this can be very useful to understand what is going wrong with a robot without needing to be looking at a graph as it happens. 
