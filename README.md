# Spiritualized GB & GBC
GB and GBC core for openFPGA on Analogue Pocket
-

Almost everything should be supported by this core.  

Be sure your gbc_bios.bin file is in /assets/gbc/common/ before using!
It should be exactly 2304 bytes.

Note that the link port is fully supported but unless a GB or GBC cartridge
is plugged in, it will run at 3.3V.

Rumble is supported if you plug in a DS rumble pak! Games like Pokemon Pinball
will utilize it if present.  

Enjoy


This core is for the [Analogue Pocket](https://www.analogue.co/pocket) via [openFPGA](https://www.analogue.co/developer).

## Release Notes

* First public release
* Supports sleep and wake and memories

## Installation
To play Game Boy and Game Boy Color on your Pocket follow these instructions. 
1. Download and install the latest Pocket firmware here https://analogue.link/pocket-firmware
2. Unzip the contents onto the root of your Pocket SD Card in the appropriate folders. 
3. You will need to add a GBC bios to your sd card. Name the gbc bios file "gbc_bios.bin" and place it in the assets/gbc/common folder.
4. Place rom files in the assets/gbc/common folder.
5. Power on Pocket and select openFPGA to run the core.
