# aichallenge_pkgs

## Introduction
This is a package extracted from the [Autoware.AI](https://www.autoware.ai/) for [Japan Automotive AI Challenge](https://www.jsae.or.jp/jaaic/).  
This package is based on [Autoware.AI v1.13](https://discourse.ros.org/t/autoware-ai-1-13-released/11785).

## Requirements
### Lanelet2
The `lanelet2_extension` depends on [Lanelet2](https://github.com/fzi-forschungszentrum-informatik/Lanelet2).  
So, please install Lanelet2 with reference to [official manual](https://github.com/fzi-forschungszentrum-informatik/Lanelet2#manual-installation).  
I used [Lanelet2 v0.9](https://github.com/fzi-forschungszentrum-informatik/Lanelet2/releases/tag/0.9).

### Others
The [tier4/aichallenge_bringup](https://github.com/tier4/aichallenge_bringup) depends on some packages.  
So, please install the following packages.

- ros-melodic-rosbridge-server
- ros-melodic-nmea-msgs
- ros-melodic-jsk-rviz-plugins
- ros-melodic-jsk-recognition-msgs

## Build Instructions
```shell
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/src
$ git clone https://github.com/atinfinity/aichallenge_pkgs.git
$ cd ..
$ catkin build
$ source devel/setup.bash
```
