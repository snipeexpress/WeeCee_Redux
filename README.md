WeeCee Redux
This is a clone of Rasteri's WeeCee v0.3 with a few changes:
1 - added HIDman in place of the PS/2 port to allow modern USB devices to be used as PS/2
2 - updated CS4237B chip circuitry for better filtering and ground plane separation
3 - changed the micro USB for power over to USB-C and added a MAX16054 on/off controller
4 - added a PC speaker to the board itself. can be disabled with a jumper
5 - changed the MicroSD slot and audio out over to cheaper versions. same ones used on Eivind Bohler's TinyLlama ( I had a lot of them ;) )
6 - modified front panel to include a power button and header to connect the board to it directly.
7 - added a small reset button and power light to the front panel to show when the device is on.
8 - added a circuit to show SD card activity as well as an LED to the front panel.
9 - added support to a CR1220 RTC battery directly to the board.

This still uses the same enclosure but will require the new front and rear panels for everything to align properly. 
