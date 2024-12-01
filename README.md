# SMS_PCB_SLOT1-2_2GAL_DIP
Master System repro PCB 512kB, handling SLOT 1 &amp; 2, using 2x GAL in DIP package

An easy-to-solder SEGA Master System PCB (in DIP format), compatible with slot 1 / 2, with a capacity of 512kB
(covering most of the Master System library and homebrew, like Alex kidd hacks).

Only few components needed :

IC0. FLASH, compatible with :
29F***/39SF*** (Flash) 512Kb MAX (see datasheets for compatibility!)
NB. *can* be rewritten after soldering (depend of your dumper/writer).

IC1. GAL22V10
file: XKGSMSM1_IC1-v10.jed

IC2. GAL16V8
file: XKGSMSM1_IC2-v8.jed

Capacitors :
3x 100nf ceramic (50v). 5.08mm
1x Electrolytic capacitor between 10uf, 22uf or 47uf, 6.3v~10v, 2.54mm
search for "electrolytic 22uf 6.3v"(example)

THE ROM NEEDS TO:
* be compatible with SEGA mapper scheme
* use slot 1 and/or 2

NOT SUPPORTED:
* slot 0 (Space Gun)
* SRAM save
