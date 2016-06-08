---
layout: single
title: Ros on Intel-NUC
sidebar:
  nav: "sidenav"
---

## ROS - Robot Operating System


# What is ROS?
Although ROS is the abbreviation of Robot Operating System it's an open source framework and no operating system. ROS itself needs a linux operating system (Ubuntu). It provides a flexible framework for writing robot software. It's a collection of tools, libraries and conventions that aim to simplify the task of creating complex and robust robot behaviour across a wide variety of robotic platforms. ROS supports mainly C++ and Python.


# Usage of ROS in the project
Most robotic applications demand a huge processing power. Therefore distributed computing which performs calculations both on on- and offboard systems is required. ROS provides a publisher-subscriber concept. Every computational process is represented as node. A node can publish messages on topics and/or subscribe on topics to receive messages. The message types can be customized. The motor controller for example uses the rosserial_arduino node for communication. 
Image data from the Microsoft Kinect has been processed with rviz, a visualization tool. Rviz has also been used to visualize the orientation of the IMU.

