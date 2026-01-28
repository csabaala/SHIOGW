# Assembly information
## 12V power source
To activate the additional digital input and output channels, connect the power source to the H5 header.
You can connect to the SHIOGW H10 connector using a JST cable.

<img src="https://github.com/csabaala/SHIOGW/blob/main/Pictures/LRMNT_12V.jpg" alt="drawing" width="380"/>

## Using input channel as ADC
You can soldering the input channels (I3 - I5) to use as ADC (Analog to Digital Converter) input.
To enable ADC reading solder the following parts (for example for I3 channel):

* R1: 0 ohm
* R5: 0 ohm (to bypass OP1)
* R3: Voltage divider high resistor 
* R4: Voltage divider low resistor 
* C5: 100 nF capacitor

Do not solder:

* OP1
* C1