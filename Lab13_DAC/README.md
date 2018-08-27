# Lab13_DAC
[E-book link](http://users.ece.utexas.edu/~valvano/Volume1/E-Book/C13_DACSound.htm) <br/> 
[Professor Valvano describing the lab](https://www.youtube.com/watch?v=o678t86HEGc) <br/> 

## Purpose
This lab has these major objectives:  <br/> 
1. To learn about DAC conversion
2. To understand how digital data stored in a computer could be used to represent sounds and music
3. To study how the DAC  and interrupts can be used together to create sounds

## Equipment
* Tiva C Series TM4C123G Lauchpad
* four switches
* four 10kΩ resistors
* four to six resistors
* Headphone jack (3.5MM Audio Jack, SJI-355XNG)
* Headphones

## What It Does
Most digital music devices rely on high-speed DACs to create the analog waveforms required to <br/> 
produce high-quality sound. In this lab, you will create a very simple sound generation system that <br/> 
illustrates this application of the DAC. Your goal is to create an embedded system that plays four <br/> 
notes, which will be a digital piano with four keys. <br/>

## System Requirements
The first step is to design and test a 4-bit binary-weighted DAC, which converts 4 bits of digital <br/> 
output from the TM4C123 to an analog signal. <br/>
The second step is to design a low-level device driver for the DAC. <br/>
The third step is to design a low-level device driver for the four keys of the piano.<br/>
The fourth step is to organize the sound generation software into a device driver. <br/>
The last step is to write a main program that links the modules together creating the digital piano. <br/>
After initialization, the main loop will input from the piano keyboard, and then call Sound_Play(C), <br/>
Sound_Play(D), Sound_Play(E), Sound_Play(G), or Sound_Off(), depending on the input pattern. <br/>
You may ignore multiple keys pressed at the same time.<br/>
