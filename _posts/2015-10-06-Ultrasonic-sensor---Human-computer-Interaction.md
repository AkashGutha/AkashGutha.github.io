---
  layout: post
  title: Ultrasonic sensor - Human computer Interaction
  subtitle: interacting with your computer using Ultrasonic sensor
  tags: electronics,hid,arduino,vusb
  categories: 
    - electronics
  author: Akash Gutha
  header_img: img/main-bg.jpg
---

__What is an Ultrasonic sensor ?__
An Ultrasonic sensor is a device that can detect signals of a specific frequency. Especially, audio signals.

__How does it work ?__
It sends an audio wave of a specific frequency, then it will raise the output signal `HIGH`. Once the echo hits the receiver the signal goes `LOW`. 

__How does it look like ?__
![Ultrasonic sensor](https://www.clinchhub.com/wp-content/uploads/2016/12/sku_133696_3.jpg){:class="img-responsive"}

__How can we calculate the distance from the obstacle ?__
The distance is proportional to the time the output signal is `HIGH`. Since, the time taken by the audio signal to reach an obstacle and reach back to the sensor is equal to the time the signal is `HIGH`, we can calculate the distance.
```
Speed of sound = 340.29 m / s
Signal Up Time = 0.01 s
Distance Travelled = (Signal Up Time) * ( Speed of sound )
```
This gives us the double distance. since, the audio signal travels from the source to the obstacle and back
```
Distance To Obstacle = Distance  Travelled / 2
```

__What are we going to build ?__
A Distance calculator to understand the basic setup of an ultrasonic sensor. Later, we will convert it into a human interactable device.

__Baisc Setup__
![Circuit]( {{ "img/ultrasonic_basic_ckt.png" | absolute_url }} ){:class="img-responsive"}


Link to the Github project: [Ultrasonic HID](https://github.com/AkashGutha/Ultrasonic-Human-Interface-device.git)
