# Simple Blink
The code in the folders will blink an LED on an MSP430

## How it works
A continuous while loop is used to continuously trigger the LED. The LED is toggled by XORing it with BIT0. Then a delay is added by using a for loop with a delay of 5000 ticks so the blink is visible to the human eye.

## Where can I use this
This code will work on any MSP430 where the LED is linked to the pin 1.0.
