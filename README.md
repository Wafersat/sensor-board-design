# WSS Sensor Board
WSS's Sensor Board design.
## Why sensor board?
Because the final goal of the WSS is to integrate everything onto a custom PCB, a sensor board allows us to test out the various sensor functionality without having to be tied down to one particular hardware. We can evaluate the board design on multiple MCUs. Modular design is always preferred in the development phase. 
## What MCU?
Right now we're looking at the RP2040 from Raspberry Pi.
## Why RP2040?
- Lots of documentation and reference designs
- Cheap, at $1 a pop, and plenty available
- Dev boards very available and many have open-source designs
- Good enough for our purposes
## Why CircuitPython?
Adafruit Industries, who builds and maintains CircuitPython, had written libraries for many of the sensors we use. Using CP instead of MicroPython speeds up the development process. Plus, I'm pretty sure their coding quality is miles ahead of mine.
