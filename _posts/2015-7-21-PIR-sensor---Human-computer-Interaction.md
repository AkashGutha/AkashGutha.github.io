---
  layout: post
  title: PIR sensor - Human computer Interaction
  subtitle: interacting with your computer using PIR sensor
  tags: electronics,hid,arduino,usb
  categories: electronics
  author: Akash Gutha
  header_img: img/main-bg.jpg
---

__What is a PIR sensor ?__
A passive infrared sensor (PIR sensor) is an electronic sensor that measures infrared (IR) light radiating from objects in its field of view. They are most often used in PIR-based motion detectors.

__What does it do ?__
It can detect warm moving objects. Like, Humans or animals walking near it.

__How does it look like ?__
![PIR sensor](https://cdn-shop.adafruit.com/1200x900/189-02.jpg){:class="img-responsive"}

__Does PIR sensor detect static warm objects ?__
No . It can only detect warm and moving objects.

__Does PIR sensor give you a sense of direction ?__
No. They do not.
But, you can always have multiple sensors in place and find the direction by checking the order they fire up.

__How do they work ?__
A Basic PIR sensor in the market will output a high signal for a fixed amount of time, once a movement is detected. This time can be configured by a potentiometer on the back of the PIR sensor. If this potentiometer is turned all the anticlockwise, time time for output dignal will be for a few seconds and the time increases as it is turned clockwise. At the max the time will be for a few minutes (Varies by manufacturer but mostly 7-10). The other potentiometer is for the sensitivity. This can be left in the middle for normal household projects.

