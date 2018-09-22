# Button Blink
This code blinks an LED using a button

## How it works
A continuous while loop is used to poll the button. To check whether or not the button is pressed an if statement is used. In this if statement PxIN is anded with BITx based off of which pin the button is on. In the if statement the LED is and equaled with the invers of its respective BITx to toggle it if the button is pressed. Else the state stays the same. For the msp430f5529 the pull up/down resistor needs to be set and the select bit needs to be disabled to disable the alternate functionality.

## What Devices does it work on
This works on any MSP430 however the pull up and pull down resistors and select bits need to be changed to reflect the correct pins on different devices.
