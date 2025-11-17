This is a project to build a DIY differential probe for oscilloscopes (CRT or DSO)
This project was based on an earlier version of a few years ago and went through a number of enhancements based on what we learned.

There are now three versions of the probe, a 1MHz, a 10MHz and a 100MHz version, using the same PCB, but with different parts.
These three versions can be powered by a number of so called voltage regulator Daughter Boards.
Two are listed here. They can be powered by USB-C PD Trigger Boards. 

There is also a 3D printed version of the probe enclosure available.
The files in this project folder contain the schematics, the BOM and the production information to order the PCB's and enclosure.
All other information about this project can be found on my Blog here:
https://www.paulvdiyblogs.net/2025/08/building-new-100mhz-differential-probe.html

The specifications for the 100MHz probe are: (the others are on the Blog)
- Input impedance: 20MegOhm//1.25pF - differential, 10MegOhm//2.5pF for each terminal to GND.
- Differential Gain = 1/10V/V. Any lower than this and most hobby DSO's cannot resolve a 1V input signal with any clarity.
- Maximum AC Common Mode Voltage (with 50V differential input) = 350VAC
- CMRR > 90dB @ DC, ~60dB @ 1MHz.
- Differential Voltage Range > +/-25V for 240VAC common-mode, +/-25V for 0V common-mode.
- 3dB bandwidth >= 100MHZ (depends on signal amplitude)
- DC offset < 1mV (trimmed)
- Noise: 30mVpp or lower at output.
- Power supply: 5.25V +/- 0.25V. This can be a USB-C PD supply plus a regulator, see the power options.
- Cost: ~$50 not including shipping and handling costs. Not including 3D printed enclosure.

Enjoy building one of these, you will be happy that you did!
