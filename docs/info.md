<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The chip recieves pulse widths, echo delay time, and number of echo pulse from a microcontroller via SPI communication. The pulse sequence is triggured by a start_pulse signal. 

## How to test

Create a mock spi data and feed into the chip through the relevant input_PAD. Measure the tx_drive signal. 

## External hardware

A microcontroller.
