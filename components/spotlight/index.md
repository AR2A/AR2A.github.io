---
layout: single
title: Highpower Spotlight for Arduino
sidebar:
  nav: "sidenav"
gallery_circuit:
  - url: ../../images/components/spotlight/schematic.png
    image_path: ../../images/components/spotlight/schematic.png
    alt: "schematic.png"
  - url: ../../images/components/spotlight/layout.png
    image_path: ../../images/components/spotlight/layout.png
    alt: "layout.png"

gallery_result:
  - url: ../../images/components/spotlight/front.png
    image_path: ../../images/components/spotlight/front.png
    alt: "front.png"
  - url: ../../images/components/spotlight/back.png
    image_path: ../../images/components/spotlight/back.png
    alt: "back.png"
---

The Spotlight provides the ability to control the rescue robot even in dark rooms. The LED drivers are controlled via ROS to adjust the brightness as required. The brightness can be regulated using a PWM which also offers the opportunity to switch every three LEDs seperately.

## Power-LED

To obtain maximum illumination of the room it is neccessary to use high-power LEDs. A well-known manufacturer of these LEDs is Cree. The light intensity of a single LED is not bright enough therefore 9 LEDs are used seperated to three series of three LEDs each. If one driver fails 6 other LEDs can still will properly work.

![alt tag](../../images/components/spotlight/led.png)

## Heatsink
Since high-power LEDs generate a lot of heat, it is neccessary to use a cooling system for heat dissipation. Depending on the current used to operate the LEDs, the brightness and heat will increase. For this purpose 2 possibilities for heat dissipation have been developed.
The first method is that the soldering pads of the LEDs are bigger than neccessary to provide means of passive cooling, which means that a large part of the heat is emitted to the environment.
The second method is a copper plane located on the back of the board behind the LEDs, to place a heat sink or an external cooler on. This surface is contacted with the enlarged front pads in several places, to dissipate heat.

![alt tag](../../images/components/spotlight/heatsink.png)

## Connection with ROS

To make the LEDs controllable by ROS it is necessary to provide both, a microcontroller and a USB to serial converter. An ATMEGA328 is used as microcontroller and a FT232 from FTDI is used as USB to serial converter. The design provides the possibility to operate the spotlight like an Arduino.

## Circuit

The circuit design shows the components used and their layout.

{% include gallery id="gallery_circuit" caption="" %}

## Result

{% include gallery id="gallery_result" caption="" %}

