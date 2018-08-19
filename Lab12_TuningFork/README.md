# Lab12_TuningFork
[E-book link](http://users.ece.utexas.edu/~valvano/Volume1/E-Book/C12_Interrupts.htm) <br/> 
[Professor Valvano describing the lab](https://www.youtube.com/watch?v=VPnIBZxOL-A) <br/> 
[Photo of Me Demonstrating the lab] (https://youtu.be/29IXDjh-iAA) <br/>

## Purpose
This lab has these major objectives:  <br/> 
1. the understanding and implementing of interrupt software
2. interfacing an output pin to the speaker, so that the software can generate a quiet buzzing sound at 440 Hz
3. study the accuracy of the pitch created with interrupts

## Equipment
* Tiva C Series TM4C123G Lauchpad
* 1kΩ resistor
* 10kΩ resistor
* 6 cables
* 1 switch
* Headphone jack (3.5MM Audio Jack, SJI-355XNG)
* Headphones

## What It Does
In this lab you will make a square wave sound at 440 Hz, which is a standard<br/> 
frequency created by a tuning fork. You will interface a positive logic switch as the <br/> 
input, and you will interface the headphones as an output.  <br/> 

## Functionality
The tone is initially off, when the switch goes from not touched to touched, the tone toggles on/off.

## Photos of My Tuning Fork Project
![lab_12a](https://github.com/automaticaddison/UT_6_20x_Embedded_Systems_Multithread/blob/master/Lab12_TuningFork/20180818__lab12_1.jpg)
![lab_12b](https://github.com/automaticaddison/UT_6_20x_Embedded_Systems_Multithread/blob/master/Lab12_TuningFork/20180818_lab12_2.jpg)
