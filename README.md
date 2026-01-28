# [SHIOGW](/Hardware/SHIOGW)

DIN rail mount extension board for [Olimex ESP32-GATEWAY](https://www.olimex.com/Products/IoT/ESP32/ESP32-GATEWAY/open-source-hardware).

More [Pictures](/Pictures#assembled-boards) and [Video](https://youtu.be/ds2y22MUNzQ) of the assembled board and extensions.

Example [ESPHome configs](/ESPHome)

## Features

* 12V to 5V step-down converter
* 2 open collector output (50 mA load per channel)
* 2 opto isolated input
* LEDs for output and input status
* 2 sensor input (ds18b20, dht)
* RS-485 interface
* 4 pin JST connector for I2C extensions
* 14 pin IDC connector for direct GPIO access

View [3D model](https://3dviewer.net/#model=https://github.com/csabaala/SHIOGW/blob/main/Hardware/SHIOGW/SHIOGW.wrl)

<img src="Pictures/SHIOGW.png" alt="drawing" width="380"/>

## Extensions

### [GWHMI](/Hardware/GWHMI)

Control interface for SHIOGW.

* PCB for 128x64 OLED display and control buttons. Fits the 0.96 and 1.3 inch OLED versions.
* Mountable top of the SHIOGW board.
* Connects to SHIOGW's 12 pin IDC connector with a small ribbon cable.
* BTN1 (up) and BTN3 (down) shared with I1 and I2 on SHIOGW main board.

View [3D model](https://3dviewer.net/#model=https://github.com/csabaala/SHIOGW/blob/main/Hardware/GWHMI/GWHMI.wrl)

<img src="Pictures/GWHMI.png" alt="drawing" width="380"/>

### [SHIO88E](/Hardware/SHIO88E)

I2C IO extension.

* MCP23017 based
* 8 open collector output (50 mA load per channel)
* 8 opto isolated input
* LEDs for output and input status
* One more I2C connector to connect other device

View [3D model](https://3dviewer.net/#https://github.com/csabaala/SHIOGW/blob/main/Hardware/SHIO88E/SHIO88E.wrl)

<img src="Pictures/SHIO88E.png" alt="drawing" width="380"/>

### [LRMNT](/Hardware/LRMNT)

Adapter PCB to mount [Heltec LoRa 32 V3](https://heltec.org/project/wifi-lora-32-v3/) module to SHIOGW board.

* 2 extra open collector output (50 mA load per channel)
* 4 extra opto isolated input

View [3D model](https://3dviewer.net/#https://github.com/csabaala/SHIOGW/blob/main/Hardware/LRMNT/LRMNT.wrl)

<img src="Pictures/LRMNT.png" alt="drawing" width="380"/>

### [SHIOADS](/Hardware/SHIOADS)

Din rail mount breakout board for ADS1115 module.

* On board voltage divider resistors (R1 - R8)
* Solder jumpers to set I2C address (JP1 - JP4)

View [3D model](https://3dviewer.net/#https://github.com/csabaala/SHIOGW/blob/main/Hardware/SHIOADS/SHIOADS.wrl)

<img src="Pictures/SHIOADS.png" alt="drawing" width="100"/>