---
layout: single
title: Components Overview
sidebar:
  nav: "sidenav"

gallery_ros-on-nuc:
  - url: ../components/ros-on-nuc/
    image_path: components/ros-on-nuc0.png
    alt: "Ros on Intel-NUC"
  - url: ../components/ros-on-nuc/
    image_path: components/ros-on-nuc1.png
    alt: "Ros on Intel-NUC"
  - url: ../components/ros-on-nuc/
    image_path: components/ros-on-nuc2.png
    alt: "Ros on Intel-NUC"

gallery_imu:
  - url: ../components/imu/
    image_path: components/imu0.png
    alt: "IMU"
  - url: ../components/imu/
    image_path: components/imu1.png
    alt: "IMU"
  - url: ../components/imu/
    image_path: components/imu2.png
    alt: "IMU"

gallery_motor:
  - url: ../components/motor-controller/
    image_path: components/motor-controller0.png
    alt: "Motor-Controller"
  - url: ../components/motor-controller/
    image_path: components/motor-controller1.png
    alt: "Motor-Controller"
  - url: ../components/motor-controller/
    image_path: components/motor-controller2.png
    alt: "Motor-Controller"

gallery_spotlight:
  - url: ../components/spotlight/
    image_path: components/spotlight0.png
    alt: "Spotlight"
  - url: ../components/spotlight/
    image_path: components/spotlight1.png
    alt: "Spotlight"
  - url: ../components/spotlight/
    image_path: components/spotlight2.png
    alt: "Spotlight"

gallery_buck-converter:
  - url: ../components/buck-converter/
    image_path: components/buck-converter0.png
    alt: "Buck-Converter"
  - url: ../components/buck-converter/
    image_path: components/buck-converter1.png
    alt: "Buck-Converter"
  - url: ../components/buck-converter/
    image_path: components/buck-converter2.png
    alt: "Buck-Converter"
---

## Ros on Intel-NUC

ROS is the abbreviation for Robot Operating System. It provides an extensive framework for robot development, tools and more. It has been used for data communication, processing and visualization.
All components are connected via USB to an Intel NUC board and can be managed via ROS.
[Read more...](/components/ros-on-nuc/)

{% include gallery id="gallery_ros-on-nuc" caption="" %}



## Imu

This is a ROS package developed to calibrate and fuse the orientation data provided by an Polulu MiniImu v9. The ROS MiniImu Calibration and Sensor Fusion Packages are tested under ROS Indigo and Ubuntu 14.04.
[Read more...](/components/imu/)

{% include gallery id="gallery_imu" caption="" %}



## Motor-Controller

This motor-controller-package brings support for the brushed motor controller based on the LXRobotics Highpower Motorshield to ROS and can be easily adapted for other motor-shields.
[Read more...](/components/motor-controller/)

{% include gallery id="gallery_motor" caption="" %}



## Spotlight

The Spotlight provides the ability to control the rescue robot even in dark rooms. The LED drivers are controlled via ROS to adjust the brightness as required. The brightness can be regulated using a PWM which also offers the opportunity to switch every three LEDs seperately.
[Read more...](/components/spotlight/)

{% include gallery id="gallery_spotlight" caption="" %}



## Power Supply

The robot is supplied with voltage by a battery pack. The voltage supply of most of the components is handled by the Intel NUC board via USB. The Intel NUC board itself and the highpower spotlights need 19 V and the Microsoft Kinect 12 V. The previous prototype setup with linear regulator and heat sink has been replaced. 
[Read more...](/components/buck-converter/)

{% include gallery id="gallery_buck-converter" caption="" %}

