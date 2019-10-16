# c51_prf_gen
Pulse Repetition Frequency

For compile this project use a sdcc.

sdcc is available on http://sdcc.sourceforge.net/

This project use a defined PRF table to generate a pulse on pin P1_0 of C51.

The microcontrollers compatible are AR89S8252, AT89S8253

For the forst compile and test, is used a PAULMON Firmware an runnin at 0x4000 over RAM CODE memory.

For run at 0x0000 address, is necessary change the 0x4000 to 0x0000.

This program, use an UART running at 115200bps 8,N,1 with @22.118400MHz of XTAL.
