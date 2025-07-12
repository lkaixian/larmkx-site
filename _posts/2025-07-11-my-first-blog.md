---
layout: post
title: "First Learning Experience of STM32 Microcontroller"
date: 2025-07-11
---

<div style="text-align: justify;">
  On 1 July 2025, I enrolled in a short workshop titled "Getting Started with STM32 Using STM32CubeIDE and HAL" which was conducted by Assoc. Prof. Dr. Tee Kian Sek, a specialist in embedded systems and electronics. The workshop held at Sena Lab, FKEE, UTHM, with a duration from 8:00AM to 5:00PM. This workshop was my first exposure to the world of STM32 and it was different that what I was previously working with including Arduino Nano and ESP32 microcontrollers. The STM32 controller that I was working with was STM32F103C8T6, a particular popular and well known microcontroller, which also had a common term of "Blue Pill" as given by its small pill-like shape and the blue colour that the board gives of. 
  
  In this workshop, Assoc. Prof. Dr. Tee Kian Sek also showcase some theory behind the STM32 including the differences between STM32 and other well known microcontroller in terms of functionality, as well as other bare-metal and software interaction such as NVIC (Nested Vectored Interrupt Controller), clock tree in STM32, and HAL (Hardware Abstraction Layer) working principal in general. 
</div>

![photo-3](/assets/120725/photo-3.jpg)
*Assoc. Prof. Dr Tee Kian Sek providing lecturing session on STM32*


<div style="text-align: justify;">
  As this was my first time working with STM32, therefore the first time I am using STM32CubeIDE was quite a learning curve as it was not as intuitive as other IDE including Arduino IDE. But once Assoc. Prof. Dr. Tee Kian Sek explained the general process of setting up and download the code into the STM32 Blue Pill, I now realized it was same step as how I did in Arduino, just I could have more control of the process.


  The final small project worked in the workshop was user-defined animation that can displayed in the OLED screen. It took me some time on inputting the custom code in the driver file and converting the .gif file I would like to display at into C bitmap code with each individual frames. Some tools used to make this process possible which including stm32-ssd1306[1], Image2cpp[2], Ezgif[3] and Rickroll gif itself [4]. But at the end of the day, it works flawlessly. 
</div>

![photo-4](/assets/120725/photo-4.jpg)
*Final setup of GIF animation using infamous "rickroll test".*


<div style="text-align: justify;">
  In short, this workshop had lead me into the new dimension of the embedded system division where STM32 could provide better controls over the hardwares but at the cost of increasing difficulty and learning curve compared to Arduino, ESP32 and Rasberry Pi Pico, which some could use embedded-C and others could use MicroPython. Once again, thanks to Assoc. Prof. Dr. Tee Kian Sek and other lecturers enrolled in the same workshop. 
</div>

![photo-2](/assets/120725/photo-2.jpg)
*Group photo with lecturers and Assoc. Prof. Dr. Tee Kian Sek.*


![photo-1](/assets/120725/photo-1.jpg)
*Poster for promotion and enrollment of workshop.*

