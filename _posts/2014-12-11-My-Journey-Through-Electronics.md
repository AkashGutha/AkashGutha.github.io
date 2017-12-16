---
layout: post
title: My Journey through Electronics
subtitle:
tags:
  - programming
  - robotics
categories:
  - life
  - programming
  - robotics
author: Akash Gutha
header_img: img/main-bg.jpg
published: true
first_prototype_video_id: nkUj4rt1_N0
---

# The Journey

__TL;DR__

Robotics  :arrow_right:  Programming microcontrollers  :arrow_right:  Using Sensors  :arrow_right:  Human Interface Devices  :arrow_right:  Unity and Electronics  :arrow_right:  Neural Electronics

__Simple Robot__

The very first robot that i built was a simple four wheeled robots that had no __intelligent__ electronic design involved. I learnt building it from a robotics workshop conducted by my seniors at the university. The robot had a  controller board and a long strand of wires hanging to connect it to the robot. We used a `Lithium-Ion battery 12V 20AH` enough to keep our robot running for about an hour.

![Buidling]( {{ "assets/robotics/build phase.jpg" | absolute_url }} ){:class="img-responsive"}

![Built]( {{ "assets/robotics/built robot.jpg" | absolute_url }} ){:class="img-responsive"}


After building this I and my team took it to a few events to participate. It did perform well :smile: but never won because, we never built it to win competitions. we were satisfied by the output.

__Line Folowing Robots__

After playing around with the same robot for another month. I came across `Line following robots (LFRs)`. They were instantly interesting to me becuase they were everything i dreamt of doing as a kid `to build something cool using both hardware and software`. I was still in the first year and wasn't much aware of electronics in practice and this was a great experience.

a very very blurry photo that i happened to take. wish we were as foucused on taking photographs as on building robots :wink:

![LFR]( {{ "assets/robotics/lfr.jpg" | absolute_url }} ){:class="img-responsive"}


__Hover Craft__

After taking our new robot the `LFR` to other competiitons in our nearby colleges, I and my team decided to participate in a Bigger TechFests and `IIT Bombay` was the perfect destination. We registered our team on the site for the `Line following Hoverbot Competiton` and started building our first `Hoverbot`

{% include youtubevideo.html id=page.first_prototype_video_id %}

__PCBs__

Laying out your circuit on a PCB is every electornic engineer's dream and sadly it's hard to get a single PCB rpinted in India. In fact it's almost immposible assuming that you are a hobbyist and not are not being backed my any company.

Luckily you cna build PCB at home using Copper plates, Print paper and Ferric chloride. Most of these materials are cheap and can be accquired easily. This method is called `Toner Transfer Technique`.

The first PCB print that i've ever made
![Pcb]( {{ "assets/electronics/pcb print.jpg" | absolute_url }} ){:class="img-responsive"}

Ironing the print onto the copper plate
![Ironing]( {{ "assets/electronics/ironing copper plate.jpg" | absolute_url }} ){:class="img-responsive"}

__LCDs__

Intefacing LCDs was tedious, yet the end result is always fun :heart:. The incentive of seeing your name on the LCD is itself enough motivation to take you through the tedious process. If you are interested in doing this i recommend you checkout Patrick Hood Daniel's channel on youtube.

that level of narcissism :stuck_out_tongue:

![lcd with name]( {{ "assets/electronics/lcd with name.jpg" | absolute_url }} ){:class="img-responsive"}

__Communication Protocls__

With time I found that i'm more interested in programming the microcontroller than building robots. I started learning to program microcontrollers for more serious applications. My first step towards this was to implement every `interface` and `commmunication protocol` from scratch and test them. I started following [Patrick Hood daniel](https://www.youtube.com/watch?v=JMMamSVy1Zs&list=PLE72E4CFE73BD1DE1), a wonderful teacher on youtube. He teaches how to program a microcontroller, specifically the ATMega series.

If you want to know what are the most common topics that you need to cover:
1. Analog to digital conversion (ADC)
2. Digital to analog conversion (DAC)
3. Pulse width Modulation (PWM)
4. Interrupts
5. Crystal oscillators
6. Fuse bits
7. UART (Universal asynchronous reception and transmission)
8. USART (Universal ynchronous and asynchronous reception and transmission)
9. TWI or I2C (Two wire interface or  Inter-integrated Circuit)
10. SPI (Serial peripheral interface)

After learning all the `communication protocols` and `interfaces` and `stuff` that i thought was way out of my league, it was time to put my skills to test. This gave me the chance to play around with numerous sensors. This is a good way to understand how small real world appliances that you find around your house work. 

Surfing through the internet i stumbeled upon Human computer interaction ( All those cool video of hand glove based intercation systems :wink: ). This is made me really interested into Human interface devices. Enter [HID](https://akashgutha.github.io/electronics/2015/06/11/HID-using-ATMega8/)
