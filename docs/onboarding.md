# Onboarding

Welcome to the 7627 software onboarding guide!

## What does software do?

A robot that has merely been designed, built, and wired is not capable of anything. The missing piece is **software**, and it is your job as part of the software team to produce that missing piece. This will consist of two primary responsibilities:

* **Firmware Management** - As a prerequisite to ensure the software can talk to the hardware, the **firmware** must be properly installed and configured.

* **Programming** - To give the robot the instructions it needs in a form the it can understand, the robot must be **programmed**. We use the **Java** programming language for robot code. If you don't know how to program, in Java or at all, worry not! This documentation contains all the resources you will need to know.

## Prerequisites

You will need a laptop(not a Chromebook! Ideally a Windows laptop, although Linux may work) and access to unrestricted Internet(not school managed Wi-Fi! Use a mobile hotspot or VPN). Then, make sure you already have, or otherwise install, the following applications:


* [**WPILib**](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html) - An indispensable library and development environment for FRC software.

* [**NI Tools**](https://www.ni.com/en/support/downloads/drivers/download.frc-game-tools.html#581857) - This will include all the basic apps you need to run a robot including Driver Station and the roboRIO imaging tool. Note, you will need to create an NI account, but luckily it is free.
  
  * **RoboRIO Imaging Tool** - Packaged within NI tools, but is essential for roboRIO operation(Systemcore will replace roboRIO as of the 2027 season). It primarily allows you to update or start anew on a roboRIO.

* A **flashing software** of your choice. Some options are listed below:
  
  * [**Balena Etcher**](https://etcher.balena.io/) - Works, although deprecated.
  
  * [**Raspberry Pi Imager**](https://www.raspberrypi.com/software/) - Possibly works.

* [**Rev Hardware Client**](https://docs.revrobotics.com/rev-hardware-client) - This is used to interface with REV hardware such as SparkMAXs.

* [**Rev Hardware Client 2**](https://docs.revrobotics.com/rev-hardware-client-2) - If your REV hardware is too new or you need some specific feature use this.

* [**Phoenix Tuner X**](https://github.com/CrossTheRoadElec/Phoenix-Releases/releases) - Used to interface with CTRe hardware such as Krakens.

* [**PathPlanner**](https://github.com/mjansen4857/pathplanner/releases) - A GUI program for easily creating paths for autonomous operation.

* [**AdvantageScope**](https://docs.advantagescope.org/overview/installation) - Primarily useful for playing back past logs, indispensable for troubleshooting.

### New to programming in Java?

You will also need to know how to program in Java. Some useful tutorials are listed below:

* [W3 Schools Java Tutorial](https://www.w3schools.com/java/) - Teaches the fundamentals of Java. You don't need any programming knowledge to follow the tutorial.

## Next Steps

Each of the following are good next places to learn more about software. You can visit each in any order:


* [Installing and Configuring Firmware](onboarding/firmware-installation.md) - A guide for dealing with firmware setup.

* [Programming for 7627](onboarding/programming-for-7627.md) - A guide more focused on the particulars of programming for the team.

* [Troubleshooting](onboarding/troubleshooting.md) - A guide for when things go wrong.

* [Who you gonna call?](onboarding/who-you-gonna-call.md) - A guide for determining who you need to ask for information.

* [Glossary](misc/glossary.md) - A guide for the various jargon you will eventually need to know.

* [Technical Documentation](tech-docs.md) - Detailed documentation about our codebase, a good reference for if you need information concerning the codebase itself.
