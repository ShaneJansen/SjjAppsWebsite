---
layout: post
title:  "Android App and Android Wear App Controlling Mains Power via Raspberry Pi"
categories: jekyll update
---

![Android App and Android Wear App](/assets{{ page.url }}1.jpg)

This is an extension of the
<a href="/raspberry-pi-controlling-mains-power/" target="_blank">Raspberry Pi Controlling Mains Power Project.</a>
The Android and Android Wear apps allow you to control any number of devices from an outlet.
I setup port forwarding on my router  so the devices can be controlled from anywhere in the world with Internet.
There is an Apache server running on the Raspberry Pi with a REST API available to the applications.  There are
two endpoints on the REST API which are "get-state" (gets a list and current state of devices) and "set-state"
(set the state of a particular device).

## Project Photos
<a href="/assets{{ page.url }}1.jpg" target="_blank"><img src="/assets{{ page.url }}thumb_1.jpg"/></a>
<a href="/assets{{ page.url }}2.jpg" target="_blank"><img src="/assets{{ page.url }}thumb_2.jpg"/></a>
<a href="/assets{{ page.url }}3.jpg" target="_blank"><img src="/assets{{ page.url }}thumb_3.jpg"/></a>

## Open Source Github Project
*  <a href="https://github.com/ShaneJansen/TheLodgeAndroid" target="_blank">Android and Android Wear Source Code</a>
*  <a href="https://github.com/ShaneJansen/TheLodgeServer" target="_blank">Raspberry Pi (Server) Source Code</a>

## Demonstration Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/EOatzmbiEB4" frameborder="0" allowfullscreen></iframe>
