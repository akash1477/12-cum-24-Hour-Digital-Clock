# 12-cum-24-Hour-Digital-Clock
A 12 cum 24 hour digital logic based clock made using basic counter and decoders. The schematics and simulation are done on ARES Proteus Design Suite 8.6
(https://getintopc.com/softwares/electronics/proteus-8-6-professional-free-download/). The clock signal of 1 Hz is generated by using a crystal of 32.768 kHz through frequency dividers. The PCB is also designed and circuit will be implemented soon in real.

The components used are:

1) Four 74LS08 ICs (AND gates)
2) Six 74ls90 ICs (BCD counters)
3) Six 74LS147 ICs (7 segment decoder)
4) One 74LS157 IC (Mux)
5) One CD4060BCN IC (Frequecy divider/counter)
6) One CD4027BE IC (Dual JK ff)
7) One SN74LS109AN IC (+ve edge trigg. JK ff)
8) Six 7-segment LED
9) Two LED (for AM and PM display)
10) Crystal (32.768 kHz)
11) Six 50 ohm resistors
12) Four 500 ohm resistors
13) Four 1N4007 diodes
14) Four Push Buttons
15) One SPDT switch (for selecting the mode)
16) Two 33pf ceramic capacitors
17) DC 5v power supply
