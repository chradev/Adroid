# Adroid
[Adroid](https://en.wikipedia.org/wiki/User:Chradev/Adriod) is proposed as an open S.T.E.A.M. platform and a process for building of educational things like robots based on the principles of the Open Source in all aspects including but not limited to the ideas, algorithms, internal and external design, mechanical, electronical and software staff. It is intended to include latest science, technology and art achievements with a special respect to an advanced learning process appropriate for any person age, interests and profession.

Adroid is not only a platform but it is also a continuous process intended to accumulate all gained knowledge and experience by all participants in S.T.E.A.M. the educational processes using it. A special relational multi-dimensional knowledge base and tools will be created and updated continuously to help the learning and teaching processes. On the other hand Adroid can be used by artists, scientists and engineers to reach better results faster.

# More new ideas

## Using Active Ball Joint Mechnism for head movement

<img src="https://github.com/chradev/Adroid/blob/main/assets/ActiveBeallJoint.png?raw=true" alt="Active Beall Joint Mechanism" width="100%">


# Next steps to be done

## Electrical and mechanical issues

* Schematic of motor drivers for driving wheels motors like auxiliary geared stepper motors;
* Unification of the motor control based on RPi Pico PIO algorithm by Van Hunter Adams;
* Modifying of 3D printed driving wheels to use both O-rings and silicone/rubber tires like in Pololu wheels;
* Unification of sets of motor pairs for driving wheels, head and body movement, including appropriate sensors;
* Adding of distance, line following and edge sensors to the driving wheels' setup;
* Adding of a pair of hall sensors for head movement for controlling of end and middle positions;
* Change from a single to a pair of auxiliary geared stepper motors for body movement (two-arm model);
* Migration from free wheel ball bearing to nylon pulley with bearing for arms;
* Adding of a pair of hall and PCB made strain gauge sensors for body movement by arms;
* Development of a PCB with arm sensors, electronics and geared stepper motors driver;
* Selecting an appropriate communication interface for both the RPi Pico MCUs and the RPi 5 board;
* Development and prototyping of appropriate printed circuits boards;
* Revising of chosen PRi 5 UPS power supply module;
* Investigation of the possibility to use a liquid based true color printing system.

## Software issues

* Splitting of algorithms for deeply embedded applications for dual-core RPi Pico MCUs;
* Integration of uROS and ROS 2 systems into RPi Pico and RPi 5 firmware;
* Defining of appropriate configuration and command infrastructure;
* Implementation of appropriate control algorithms and information structure;
* Development of interactive user interface based Web Sockets ;
* Development of a task based interface for high level robot control.

# First real prototypes

## Some software staff developed and/or tested (short videos)

### Head and body movement using geared stepper motors controled by RPi Pico PIO

Van Hunter Adams' algorithm for the RPi Pico PIO is downloaded, built and tested on the head and body movement auxiliary geared stepper motors in the Small Adroid prototype. For the building of the firmware, Linux OS on the RPi 5 board at the Wide Adroid prototype is used. The complete set of the RPi Pico C/C++ SDK and all the required libraries and tools to build and flash it on the target are also installed. The video shows synchronized body and head movements controlled by the RPi Pico PIO. The animation with 46.5 fps visible on the 3.2" TFT SPI display is generated on an overclocked at 250 MHz RPi Pico MCU using the TFT_eSPI library and transferred over SPI at 62.5 MHz.

[IMG_1380.webm](https://github.com/user-attachments/assets/fc1d304b-d6ce-423e-b7e3-0300df6fe03b)

### Dual camera streaming server with ePTZ control

The next video is a compilation of a user interface based Web Sockets and remote terminals running corresponding server staff and shows the real time ePTZ control of both cameras. In addition, the almost real time video streaming and its low latency are observable thanks to embedded and synchronized clocks running at both server and user ends.

https://github.com/chradev/pi-h264-to-browser-streamer/assets/11261306/cbac77e0-3cdb-4b67-8a05-6e53c996912c

## Mechanical design prototypes

Three real Adroid prototypes (the Small, the Tall and the Wide) are shown in the picture below. It was chosen to use NEMA 42HB34 stepper motors for the main robot movement and 28BYJ-48 geared stepper motors as auxiliary with ULN2003 drivers for body and head movement. The body movement is based on a single stepper motor, belt gear based on 16- and 60-tooth GT2 pulleys, and an arm with a pair of ball bearing free wheels on springs. Two of them (the Tall and the Wide) are running on their RPi 5 boards Linux OS and a dual camera streaming server with ePTZ control written on Python. The RPi 5 boards are powered by 3S Li-Po UPS modules. The head movement (pan only) of these two prototypes is based on a single auxiliary geared stepper motor. The Small Adroid prototype (low budget variant) contains three RPi Pico MCUs and ULN2003 drivers for stepper motor control, two MCUs with a 2 MP OV2640 SPI camera and microphone each, and one for the server staff based on the Seeed Studio XIAO ESP32S3 Sense modules. All these low consumption modules are extremely small (21mm x 17,5mm) and have 8MB RAM, 8MB of flash, 2.4GHz Wi-Fi, BLE 5.0, a wide set of interfaces, and can be programmed via their USB-C конектор.

<img src="https://github.com/chradev/Adroid/blob/main/assets/Prototypes-b.png?raw=true" alt="Prototypes" width="100%">

## 3D printed unified details and wide mount variant with own wheel design

In the picture below is shown the second generation of 3D printed unified details, including own Pololu like driving wheel with two O-rings, hub and 60-tooth GT2 pulley. It is planned instead of a single motor with belt gear and a single arm with a pair of free ball bearing wheels for body movement to use a dual arm scheme with a directly coupled geared stepper motor, a nylon pulley with bearing, a PCB made strain gauge, and a pair of hall sensors for each arm. On the photo is shown a new prototype variant with two body movement auxiliary geared stepper motors;

<img src="https://github.com/chradev/Adroid/blob/main/assets/3D-Printing-Details-Gen4-Plus.png?raw=true" alt="3D Printing Details" width="100%">

## Third party components

The components shown on the picture are before the second generation of 3D printed unified details and include Pololu wheels and belt geared body movement scheme staff.

<img src="https://github.com/chradev/Adroid/blob/main/assets/ThirdPartyStaff.png?raw=true" alt="Third Party Staff" width="100%">

## Simulated design configurations

The simulation web application was developed in the very beginning and did not reflect later modifications made in prototyping process.

<img src="https://github.com/chradev/Adroid/blob/main/assets/AllDesignConfigurations.webp?raw=true" alt="All Design Configurations" width="100%">

# Related projects and links

Some of the links include staff from different projects, investigations and tests that could be used in the current development process.

 * [A simple web application to test different design configurations of STEAM robots](https://github.com/chradev/steam-robot-design-simulator)
 * [Dual camera, near-real-time, h.264 video streamer from RPi 5 to a bowser](https://github.com/chradev/pi-h264-to-browser-streamer)
 * [Own implementation of open source intelligent robot – startup design notes](https://www.radevs.net/chradev/projects/DesignNotes.pdf)
 * [Unified ILI9341 Graphic Test](https://github.com/chradev/Unified-ILI9341-Graphic-Test)
 * [Unified_ili9340_Graphic_Test_plus](https://github.com/chradev/Unified_ili9340_Graphic_Test_plus)
 * [DrawWithDMA](https://github.com/chradev/DrawWithDMA)
 * [Unified Multicore Low Power IoT Platform](https://www.radevs.net/chradev/projects/Unified_Multicore_Low_Power_IoT_Platform.pdf)
 * Open S.T.E.A.M. initiative - ([En](https://www.radevs.net/chradev/projects/OpenSTEAM.pdf), [Bg](https://www.radevs.net/chradev/projects/OpenSTEAM_bg.pdf))
