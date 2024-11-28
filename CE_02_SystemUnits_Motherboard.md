# CE REVISION SHEET 02
## SYSTEM UNITS : MOTHERBOARD
<br>

also known as ```MAIN BOARD```, ```SYSTEM BOARD```, and ```PLANAR```, it is the central printed circuit board, or ```PCB```

it connects all the components inside the computer case


<br>

________
### 01.00 FORM FACTOR
________________

the motherboard needs to be compatible with multiple othe system units, including the case, the power supply, etc.

it includes
* dimension / size
* power supply type
* location of mounting holes
* number of ports


<br>
<br>

________
### 02.00 PROCESSOR SOCKET
________________

the CPU is attached to the motherboard, therefore it needs to fit the socket the motherboard has installed on

the socket provides mechanical and electrical connection between the CPU and the motherboard

all processor sockets use ```ZIF``` or Zero Insertion Force sockets

on the market, today, most motherboards have three types of processor sockets

| ABV | FULL NAME | DESC |
|-----|-----------|------|
| ```PGA``` | Pin Grid Array | pins aligned in uniform rows around the socket|
| ```LGA``` | Land Grid Array | it uses pads (lands) rather than pins <br> (the pins are on teh socket rather than the CPU) |
|```FCLGA``` | Flip-chip Land Grid Array | the chip is flipped so the top of <br> the chip makes contact with the socket |

<br>

to make contact with the CPU, the socket has two ways

| ABV | FULL NAME | DESC |
|-----|-----------|------|
| ```SPGA``` | Staggered Pin Grid Array | The pins are staggered over the socket <br> (which allows more pins to be put) |
| ```BGA``` |  Ball Grid Array | the CPU is soldered to the motherborad



<br>
<br>

________
### 03.00 PORTS AND CONNECTORS
________________

ports that come directly off the motherboard are aclled ```ONBOARD PORTS```

* USB
* soudn
* network
* FireWire
* eSATA
* ...


<br>
<br>

________
### 04.00 SETTINGS
________________

motherboard settings can be used for many different things that touch the basic of the computer
* Enable / Disable connectors and ports
* Set CPU and buses frequency
* Control security features
* Booting configuration


<br>

#### 04.01 BIOS VS UEFI

the BIOS and UEFI serve the same purpose, the BIOS is simply the older version

There is also computers with both BIOS and UEFI to enable better backward compatibility

Everything is on and controlled in the ```BIOS chip```, and powered by the ```CMOS battery``` (Complementary metal-oxide semiconductor)

|PROCESS | BIOS | UEFI |
|--------|------|------|
| **STORAGE / PARTIONING** | ```Master Boot Record``` or ```MBR``` <br> size limit : 2.2 TB | ```GUID partition table``` or ```GPT```  <br> size limit : none |
| **BOOTLOADER** | in the ```MBR``` | on the ```EFI System Partition``` or ```ESP``` |
| **BOOT** | ```POST``` before booting | bypass ```POST``` and boots OS directly |
| **UI** | text-based | GUI |
| **SECURITY** | limited | multiple features including secure boot | 
| **DRIVER SUPPORT** | built-in ROM drivers | supports discrete driver loading for better maintenance and updating of the firmware |
| **MODE** | 16-bit mode | 64-bit mode |

```EFI``` means Estensible Firmware INterface



<br>
<br>

________
### 05.00 POWER ON SELF TEST
________________

often abreviated to ```P.O.S.T.```, it is a sery of system checks run by computers when they boot up.

it allows the computer to check if everything is working normally, and if not, to halt or even stop completly the booting process and tell the user the problem.

If an error occures, they are either displayed on the screen, through the BIOS, or through sounds and LEDs if the error happened before the screen check

examples of P.O.S.T. errors (from wikipedia and Computer Hope)

| BEEPS | MAC | 
|-------|-----|
| 1 | no RAM installed / detected |
| 2 | imcompatible RAM types |
| 3 | no good banks |
| 4 | no good boot images in the boot ROM <br> bad system configuration block |
| 5 | processor is not usable | 

<br>

|BEEPS | INTEL MAC | 
|------|-----------|
| 1 beeps every 5 seconds | no RAM installed / detected |
| 3 beeps every 5 seconds | imcompatible RAM types <br> no good banks |
| 1 long beep while the <br> power button is held down | EFI ROM update in progress (For Macs < 2012) |
| 3 long 3 short 3 long | EFI ROM corruption detected <br> ROM recovery in process | 

<br>

| BEEPS | AMI BIOS |
|-------|----------|
| 1 | memory refresh timer error |
| 2 | parity error in base memory (first 64 KiB block) |
| 3 | Base memory read / write test error |
| 4 | motherboard timer not operational |
| 5 | procesor failure |
| 6 | 8042 Gate A20 test error (cannot switch to protected mode) |
| 7 | General exception error (processor exception interrupt error) |
| 8 | Display memory error (system video adapter) |
| 9 | AMI BIOS ROM checksum fix |
| 10 | CMOS shutdown register read / write fix |
| 11 | cache memory test failed |
| continuous | motherboard does not detect a RAM module |

<br>

| CODES | IBM BIOS | |  CODES | IBM BIOS |
|-------|----------|-|--------|----------|
| 100–199	| System boards |                                         | 1700–1799   | Hard drive or adapter (or both) |
| 200–299	| Memory |                                                | 1800–1899   | Expansion unit (XT) |
| 300–399	| Keyboard |                                              | 2000–2199   | Bisynchronous communication adapter |
| 400–499	| Monochrome display |                                    | 2400–2599   | EGA system-board video (MCA) |
| 500–599	| Color / graphics display |                              | 3000–3199   | LAN adapter |
| 600–699	| Floppy-disk drive or adapter |                          | 4800–4999   | Internal modem | 
| 700–799	| Math coprocessor |                                      | 7000–7099   | Phoenix BIOS chips |
| 900–999	| Parallel printer port |                                 | 7300–7399   | 3.5-inch disk drive |
| 1000–1099	| Alternate printer adapter |                             | 8900–8999   | MIDI adapter | 
| 1100–1299	| Asynchronous communication device, adapter, or port |   | 11200–11299 | SCSI adapter |
| 1300–1399	| Game port |                                             | 21000–21099 | SCSI fixed disk and controller |
| 1400–1499	| Color / graphics printer |                              | 21500–21599 | SCSI CD-ROM system |
| 1500–1599	| Synchronous communication device, adapter, or port | | | |






