# CE REVISION SHEET 02
## SYSTEM UNITS : MOTHERBOARD
<br>

also known as ```MAIN BOARD```, ```SYSTEM BOARD```, and ```PLANAR```

it connects all the components inside the computer case


<br>

________
### 01.00 FORM FACTOR
________________

the motherboard needs to be compatible with multiple othe system units, including the case, the power supply, etc.


<br>
<br>

________
### 02.00 PROCESSOR SOCKET
________________

the CPU is attached to the motherboard, therefore it needs to fit the socket the motherboard has installed on

all processor sockets use ```ZIF``` or Zero Insertion Force sockets

on the market, today, most motherboards have three types of processor sockets

| ABV | FULL NAME | DESC |
|-----|-----------|------|
| ```PGA``` | Pin Grid Array | pins aligned in uniform rows around the socket|
| ```LGA``` | Land Grid Array | it uses pads (lands) rather than pins |
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
