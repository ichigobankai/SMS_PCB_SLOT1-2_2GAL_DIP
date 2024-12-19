# SMS_PCB_SLOT1-2_2GAL_DIP
SEGA Master System repro PCB, handling SLOT 1 &amp; 2, using 2x GAL in DIP package

An <strong>easy-to-solder</strong> SEGA Master System PCB (DIP format),<br>
compatible with <strong>slot 1 / 2</strong>,<br>
with a capacity of <strong>512kB</strong><br>
(covering most of the Master System library and homebrew, like Alex Kidd hacks).

<img src="https://github.com/ichigobankai/SMS_PCB_SLOT1-2_2GAL_DIP/blob/main/ichigo_sms2gal.jpg" width="50%" height="auto">

<strong>Works on SMS, MD and Mark III (no special pin used)</strong><br>
BUS pins used : D0..D4, A0, A13..A15, /OE, /CE, /WE and /RESET<br>

<h3>Only few components needed:</h3>

<strong>IC0. FLASH, compatible with:</strong><br>
29F***/39SF*** (Flash) 512Kb MAX (see datasheets for compatibility!)<br>
NB. *can* be rewritten after soldering (depend of your dumper/writer).

<strong>IC1. GAL22V10</strong><br>
file: XKGSMSM1_IC1-v10.jed<br>
added a XKGSMSM1_IC1-v10_TL866.jed (headerless file)

<strong>IC2. GAL16V8</strong><br>
file: XKGSMSM1_IC2-v8.jed

<strong>Capacitors:</strong><br>
3x 100nf ceramic (50v). 5.08mm<br>
1x Electrolytic capacitor between 10uf, 22uf or 47uf, 6.3v~10v, 2.54mm<br>
search for "electrolytic 22uf 6.3v"(example)

<strong>THE ROM NEEDS TO:</strong><br>
* be compatible with SEGA mapper scheme<br>
* use slot 1 and/or 2

<strong>NOT SUPPORTED:</strong><br>
* slot 0 (Space Gun)<br>
* SRAM save

<h4>GERBER FILES are made for JLCPCB,<br>
but should be pretty universal</h4>

Also posted at <a href="https://www.smspower.org/forums/20390-PCBSMSCartridgeWithSlot12InDIPFormatEasyHandSoldering" target="_blank">SMSpower!</a>

<strong>Some pics!</strong>

<h4>PROTO</h4>
<img src="https://github.com/ichigobankai/SMS_PCB_SLOT1-2_2GAL_DIP/blob/main/proto.jpg" width="50%" height="auto">

<h4>Wonder Boy 3 - SLOT 2 only</h4>
<img src="https://github.com/ichigobankai/SMS_PCB_SLOT1-2_2GAL_DIP/blob/main/wb3_slot2.jpg" width="50%" height="auto">

<h4>Sonic the Hedgehog - SLOTS 1 & 2</h4>
<img src="https://github.com/ichigobankai/SMS_PCB_SLOT1-2_2GAL_DIP/blob/main/sonic_slot1-2.jpg" width="50%" height="auto">

Happy soldering,<br>
ICHIGO
