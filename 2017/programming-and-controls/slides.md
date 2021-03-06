# FRC Programming and Controls

### Adam Brightwell
### January 7th, 2017



# Who?

* Software/Database Engineer
* [PostgreSQL](http://www.postgresql.org/) Open Source Database
* Team 4533 - Lead Programming and Controls Mentor



# Controls


## Control System Overview
<ul>
<li class="fragment">Driver Control System - The interface between the operator and the robot</li>

<li class="fragment">Robot Control System - The electronic hardware/software inside the robot</li>

<li class="fragment">Robot Communication System - A local area network router establishing wireless/tethered communication between a driver and the robot</li>
</ul>


## Driver Control System
## (Driver Station)

<ul>
<li>A netbook/laptop PC</li>
<li>Up to four (4) USB Joysticks or [Game Pads](http://gaming.logitech.com/en-us/product/f310-gamepad)</li>
<li>A USB hub</li>
<li>Other custom controls (2012 introduced the MS Kinect).</li>
</ul>


## Robot Control System


## National Instruments roboRIO
![frc-roborio](./images/roborio.png)


## Power distribution system
<img src="./images/pdb.png" width="200px">


## Motor controllers, relays, solenoids, sensors, etc.
![talon-srx](./images/talon-srx.png) ![spike-relay](./images/spike-relay.png)


## [Getting Started](http://wpilib.screenstepslive.com/s/4485/m/13503)



# Programming Languages


## LabView
<ul class="fragment">
    <li class="fragment">Graphical Programming Environment</li>
    <li class="fragment">Developed by National Instruments</li>
    <li class="fragment">Not a "language"</li>
    <li class="fragment">Difficult to debug</li>
    <li class="fragment">It's HUGE!</li>
</ul>


## LabView
![labview-image](./images/labview.jpg)


## Java
<ul>
    <li class="fragment">Object Oriented Programming (OOP) Language</li>
	<li class="fragment">Use Eclipse IDE</li>
    <li class="fragment">Beginner Friendly</li>
    <li class="fragment">[Installing Java Development Tools](http://wpilib.screenstepslive.com/s/4485/m/13503)</li>
</ul>


## C++
<ul>
<li class="fragment">Object Oriented Programming Language</li>
<li class="fragment">Use Eclipse IDE</li>
<li class="fragment">Not Beginner Friendly</li>
<li class="fragment">Workshop will be available</li>
</ul>



# Programming The Robot


# The Basics


## Control Objects
* Joystick
* SpeedController
* DigitalInput/DigitalOutput


## Robot Types


## Simple Robot
* "autonomous"
* "operatorControl"


## Iterative Robot
* Simple Robot 2.0
* Initialization and clean up methods.


## Command Robot

* Subsystems
* Commands
* Command Groups


## Robot Modes
* Operator Control (TeleOp)
* Autonmous


# [Example](https://github.com/abrightwell/frc-kickoff-example/blob/master/src/edu/wpi/first/wpilibj/templates/RobotTemplate.java)



# [What's Changed](https://wpilib.screenstepslive.com/s/4485/m/13503/l/681378-new-for-2017)?
* WPILib is now Open Source!!!! [GitHub - WPILib Suite](https://github.com/wpilibsuite)
* Most 3rd party devices unbundled from core WPILib ([CANTalon](http://www.ctr-electronics.com/hro.html#product_tabs_technical_resources), etc.).
* Moving away from NIVision in favor of [OpenCV](http://opencv.org/).
* New 'commands' added to reduce boiler plate (TimedCommand, etc).
* [XBoxController class](https://github.com/wpilibsuite/allwpilib/blob/master/wpilibj/src/athena/java/edu/wpi/first/wpilibj/XboxController.java) added.



# Version Control
![octocat](./images/octocat.png)

Workshop?



# Virtual Workshops


* Every Thursday 5-6pm for all 6 weeks of build season
* Google Hangout (On Air)
* Programmer Driven
* Please sign up to receive workshop invites


* Week 1: Getting Started - Installing tools and first steps
* Week 2: Networking - Setting up the wireless network
* Week 3: Robot Basics - Motor Controllers, sensors, oh my!
* Week 4: SmartDashboard
* Week 5: Robot Vision?
* Week 6: Open Questions and Answers



# Follow Us
* [github.com/wando-advanced-robotics](https://github.com/wando-advanced-robotics)
* [github.com/frc-team-342](https://github.com/frc-team-342)



# Contact

* Email: [adam.brightwell@gmail.com](mailto:adam.brightwell@gmail.com)
* GTalk/Hangout: [adam.brightwell](https://hangouts.google.com/)
* Slack: [adam.brightwell](https://scfrc.slack.com)
