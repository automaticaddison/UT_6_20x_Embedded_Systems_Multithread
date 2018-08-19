# Lab11_UART
[E-book link](http://users.ece.utexas.edu/~valvano/Volume1/E-Book/C11_SerialInterface.htm) <br/> 
[Professor explaining the lab](https://www.youtube.com/watch?v=u7Hs55N1FAo) <br/>

## Purpose
In Lab11, you will learn how to write software that converts numbers into ASCII strings and display <br/>
the string on the display connected to UART0. Please read the entire lab before starting.<br/>

## Equipment
* Tiva C Series TM4C123G Lauchpad

## What It Does
Part a) Write an I/O driver routine that outputs strings to the UART0 device. See the comments in the UART.h and UART.c <br/> 
for more detailed descriptions of how this UART_OutString function is to work. <br/>

Part b) Write an I/O driver routine that outputs an unsigned decimal number to the UART0 device. See the comments in the UART.h and UART.c for more detailed descriptions of how these UART_ConvertUDec and UART_OutUDec functions are to work. <br/>

Part c) Assume the system stores the integers 0 to 9999, but the values mean 0.000 to 9.999 cm. For example, in the software a variable 
might contain 1234, but that value actually means 1.234 cm. Write an I/O driver routine that outputs the value of the distance to the UART0 device. See the comments in the UART.h and UART.c for more detailed descriptions of how these UART_ConvertDistance and
UART_OutDistance functions are to work.
