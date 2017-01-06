---
layout: post
title:  "Android Bluetooth Motion Sensor Using Arduino"
categories: jekyll update
---

![Android Arduino Bluetooth](/assets{{ page.url }}1.jpg)

This is an infrared motion sensor connected to an Arduino microcontroller.
When motion is detected, the microcontroller communicates to a running Android application via Bluetooth
to play a sound and show a notification.  The notification is dismissed and the microcontroller
is ready to detect the next movement.  The alarm can be disabled for 1 minute from the application
and if the connection is lost during use, a different sound will play.

## Parts Used
1.  1 Arduino Microcontroller
2.  1 PIR Motion Sensor
3.  4 AA Battery Pack (6.0v)
4.  1 Bluetooth Module
5.  1 200 Ohm Resistor
6.  1 Red LED

## Project Photos
<a href="/assets{{ page.url }}2.jpg" target="_blank"><img src="/assets{{ page.url }}thumb_2.jpg"/></a>
<a href="/assets{{ page.url }}3.jpg" target="_blank"><img src="/assets{{ page.url }}thumb_3.jpg"/></a>
<a href="/assets{{ page.url }}4.jpg" target="_blank"><img src="/assets{{ page.url }}thumb_4.jpg"/></a>
<a href="/assets{{ page.url }}5.jpg" target="_blank"><img src="/assets{{ page.url }}thumb_5.jpg"/></a>
<a href="/assets{{ page.url }}6.jpg" target="_blank"><img src="/assets{{ page.url }}thumb_6.jpg"/></a>
<a href="/assets{{ page.url }}7.jpg" target="_blank"><img src="/assets{{ page.url }}thumb_7.jpg"/></a>
<a href="/assets{{ page.url }}8.jpg" target="_blank"><img src="/assets{{ page.url }}thumb_8.jpg"/></a>

## Open Source Github Project
*  <a href="https://github.com/ShaneJansen/MotionDetectorAndroid" target="_blank">Android Source Code</a>
*  <a href="https://github.com/ShaneJansen/MotionDetectorArduino" target="_blank">Arduino Source Code</a>

## Demonstration Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKJGCs2Isdg" frameborder="0" allowfullscreen></iframe>
