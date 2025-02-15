<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project simply uses 4 flipflops to divide down the clock.

Reset circuit was attempted with 4 AND gates, but this **does not** work correctly, only resetting the bit 0 and stopping the count, but the remaining bits **does not** reset correctly.

## How to test

Simply enable the project and apply a reasonable clock (slow like a few Hz for visible output on the display).

## External hardware

No external hardware is needed except for the development board with the 7-segment display connected to the output pins.
