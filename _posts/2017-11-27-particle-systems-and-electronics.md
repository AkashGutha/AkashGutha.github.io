---
layout: post
title: Particle systems and electronics
subtitle: electronics with a touch of creativity
tags: electronics, unity3d, hci
published: true
categories:
    - electronics
    - human computer interaction
    - game developemnt
    - unity3d
author: Akash Gutha
header_img: img/main-bg.jpg
---


The project detailed below is a fun experiment to explore bringing real-life interaction into virtual environments. The interaction is with the computer fan. There are different variants of computer fans available in the market. We are going to be using the 3-wire option, 4-wire variant should work without any issues.

The three wire variant has three color-coded wires (obviously)

1. Red (Power +5v/+12v).
2. Black (Ground).
3. Yellow (analog output/ RPM output).

The red and black are self-explanatory. The yellow wire outputs voltage for ADC (analog to digital converter) to get the current rpm - rotations per minute. In the four-wire variant, you can see a blue wire. The blue wire is for PWM( pulse width modulation) control, to control the speed of the fan which is just an added advantage, but we can also use PWM signals form any micro-controller as the input to the fan to simulate the same effect.

__3 wire variant__
![3-Wire]( {{ "assets/electronics/3-wire-computer-fan.jpg" | absolute_url }} ){:class="img-responsive"}

__4 wire variant__
![4-Wire]( {{ "assets/electronics/4-wire-computer-fan.jpg" | absolute_url }} ){:class="img-responsive"}

# For this project we are going to use the below components

1. Arduino Uno
2. Connecting USB cable
3. Computer fan
4. A computer
5. Unity3d (Game engine)

