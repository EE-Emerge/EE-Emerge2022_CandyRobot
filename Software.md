---
layout: default
title: Software
description: EE-Emerge Candy Robot 2021-2022
---

The OpenMV camera has its own Python-based integrated development environment (IDE), allowing for easy access to MicroPython libraries.

With features like a framebuffer viewer, a color sensor, and a histogram display, we are able to choose which colors to detect using its RGB value and the Threshold Editor. The camera is programmed so that once all the candy of a certain color is picked up, the candy of the next color will be detected and picked up.


<p align="center">
  <img 
    width="400"
    height="400"
    src="{{site.baseurl}}/assets/css/threshold.png"
  >
</p>

From the camera, we are able to obtain the coordinates of the candy and convert them into G-code to communicate with the 3D printer through SPI and UART communication.


<p align="center">
  <img 
    width="400"
    height="400"
    src="{{site.baseurl}}/assets/css/code.png"
  >
</p>


