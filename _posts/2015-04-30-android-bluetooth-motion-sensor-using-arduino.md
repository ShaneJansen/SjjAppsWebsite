---
layout: post
title: "Android Bluetooth Motion Sensor Using Arduino"
tags: [Software Development]
---

![Android Arduino Bluetooth](/assets/posts{{ page.id }}/1.jpg)

This is an infrared motion sensor connected to an Arduino microcontroller. When motion is detected, the microcontroller communicates to a running Android application via Bluetooth to play a sound and show a notification. The notification is dismissed and the microcontroller is ready to detect the next movement. The alarm can be disabled for 1 minute from the application and if the connection is lost during use, a different sound will play.

## Parts Used
 * 1 Arduino Microcontroller
 * 1 PIR Motion Sensor
 * 4 AA Battery Pack (6.0v)
 * 1 Bluetooth Module
 * 1 200 Ohm Resistor
 * 1 Red LED

## Project Photos
<a href="/assets/posts{{ page.id }}/2.jpg" target="_blank"><img src="/assets/posts{{ page.id }}/2.jpg" width="100"/></a>
<a href="/assets/posts{{ page.id }}/3.jpg" target="_blank"><img src="/assets/posts{{ page.id }}/3.jpg" width="100"/></a>
<a href="/assets/posts{{ page.id }}/4.jpg" target="_blank"><img src="/assets/posts{{ page.id }}/4.jpg" width="100"/></a>
<a href="/assets/posts{{ page.id }}/5.jpg" target="_blank"><img src="/assets/posts{{ page.id }}/5.jpg" width="100"/></a>
<a href="/assets/posts{{ page.id }}/6.jpg" target="_blank"><img src="/assets/posts{{ page.id }}/6.jpg" width="100"/></a>
<a href="/assets/posts{{ page.id }}/7.jpg" target="_blank"><img src="/assets/posts{{ page.id }}/7.jpg" width="100"/></a>
<a href="/assets/posts{{ page.id }}/8.jpg" target="_blank"><img src="/assets/posts{{ page.id }}/8.jpg" width="100"/></a>

## Github Links
* <a href="https://github.com/shanejansen/portable-security-android" target="_blank">Android Source Code</a>
* <a href="https://github.com/shanejansen/motion-detector-arduino" target="_blank">Arduino Source Code</a>

## Demonstration
<iframe width="560" height="315" src="https://www.youtube.com/embed/xCMgG10Ez0A" frameborder="0" allowfullscreen></iframe>
