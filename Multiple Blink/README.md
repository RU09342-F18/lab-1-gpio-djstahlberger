# Multiple Blink
This code blinks two LED's on an MSP430 at seperate rates. For one cycle of the one LED the other LED will blink 7 times.

## How does it work
A continuous while loop is used to toggle the LEDS. the first LED is XORed with its respective BITx to toggle it. A for loop that runs 7 times is used to toggle the second LED 7 times. The second LED is then XORed with its respective BITx to toggle it. A delay of 10000 ticks is then used so the blink can be seen by the human eye.

## Where can I use it
This code can be used on any MSP430, however the outputs have to be changed to the pins respective to different LEDS. (PxDIR |= BITx)
