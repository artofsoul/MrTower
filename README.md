[![Codacy Badge](https://api.codacy.com/project/badge/Grade/11b722ea472f4136aae08d9c1a020214)](https://www.codacy.com/app/tonikolaba/MrTower?utm_source=github.com&utm_medium=referral&utm_content=tonikolaba/MrTower&utm_campaign=badger)
[![Dependency Status](https://www.versioneye.com/user/projects/592d2ef9a8a0560047cb155e/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/592d2ef9a8a0560047cb155e)
[![AppVeyor Build status](https://ci.appveyor.com/api/projects/status/bj4gqn3gp3gu45sa?svg=true)](https://ci.appveyor.com/project/tonikolaba/mrtower/ "AppVeyor Build status")
[![Build Status](https://travis-ci.org/tonikolaba/MrTower.svg?branch=master)](https://travis-ci.org/tonikolaba/MrTower)

# Mr Tower 

Mr Tower :tokyo_tower: is a Java game. It have been created to be a funny, free and faster 2D game framework, supporting LWJGL - Lightweight Java Game Library and Slick2D for Desktop PC. It have been created to run on windows system.

![alt text](https://github.com/tonikolaba/MrTower/blob/master/res/menu/MrTower.gif) | ![alt text](https://github.com/tonikolaba/MrTower/blob/master/res/menu/MrTower1.gif)
------------ | -------------


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing & Running

Mr Tower game supports LWJGL - Lightweight Java Game Library and Slick2D.

```
1 - Import project as Workspace on eclipse (File/Import/general select Existing Projects into Workspace)

2 - Right click on project properties, select Java Build path, go to Libraries

3 - Extend the lwjgl.jar file and select Native library location, then search for Native folder on the files that you download (MrTower/lib/native). Native folder is just for Windows.

Native folder tell IDE what kind of operation system it will run.

4 - Run Game as Java Application (al.artofsoul.main/Boot is the main method).

```
![Alt text](https://github.com/tonikolaba/MrTower/blob/master/res/menu/native-explain.gif)

P.s if you will use editor to modify the map start at 0:2 in any case, for now. :neutral_face:

Have Fun!
 
## Built With

* [Maven](https://maven.apache.org/) - Apache Maven

Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information. 

* [LWJGL](https://www.lwjgl.org/) - Lightweight Java Game Library

LWJGL is open source software and freely available at no charge. LWJGL is a Java library that enables cross-platform access to popular native APIs useful in the development of graphics (OpenGL), audio (OpenAL) and parallel computing (OpenCL) applications. This access is direct and high-performance, yet also wrapped in a type-safe and user-friendly layer, appropriate for the Java ecosystem.

LWJGL is an enabling technology and provides low-level access. It is not a framework and does not provide higher-level utilities than what the native libraries expose. As such, novice programmers are encouraged to try one of the frameworks or game engines that make use of LWJGL, before working directly with the library.


* [Slick-Util](http://slick.ninjacave.com/slick-util/) - Slick-Util 

Slick-Util is a small library to enable you to load various image, sound and font formats for use with LWJGL.

Its basically a subset of the full Slick2D library which contains various useful classes that can be used by users working with LWJGL code directly.


## Authors

* **Toni Kolaba** - *Initial work* - [tonikolaba](https://github.com/tonikolaba)

![Alt text](https://github.com/tonikolaba/download/blob/master/info/artofsoullogoVOG.png?raw=true"ArtofSoul")

