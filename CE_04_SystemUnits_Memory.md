# CE REVISION SHEET 04
## SYSTEM UNITS : MEMORY
<br>

________
### 01.00 HARD DISK DRIVE
________________

A Hard Disk Drive or ```HDD``` is the primary archival system of a compter

It is a long term memory that has a few factors that come into play :

* physical size
* capacity
* speed
* technologies used inside the drive
* interface standards

<br>

#### 01.01 MAGNETIC HARD DRIVE

made with one or multiple plated disks that are stacked together to spin inside a sealed metal housing

Firmware controls data reading, writing, and the motherboard communication

the read / write heads are controlled by an actuator

the tracks are devided in sectors (4096-bytes) and concentric circles (tracks) in which the data is written into

<br>

#### 01.02 SOLIDE STATE DRIVE

also called ```SSD```

theres no moving parts compared to the magnetic hard drive

it is built using nonvolative memory (a bit like USB flash drives) called ```NAND flash memory```, which does not need power to retain data

its life span is based on the number of write operations the drive has
it is expressed in ```TBW``` (TeraBytes Written) or ```DWPD``` (Drive Writes Per Day)

<br>

#### 01.03 HYBRID HARD DRIVE

often called ```H-HDD``` or ```SSHD``` (Solid-state hybrid drive)

it contains a magnetic drive that permanently holds data AND a flash component that serves as a buffer

the OS MUST support a hybrid drive for it to function

the computer uses ```Logical Block Addressing``` or ```LBA``` to address all hard drive sectors

<br>

#### 01.04 INTERFACE STANDARDS

the port used to connect the drive to the motherboard

| NAME(S) | ABV | USED? | DESCRIPTION |
|------|-----|-----|-------------|
| Inegrated Drive Electronics <br> Parallel ATA | IDE <br> PATA | OUTDATED | one or two by motherboard <br> 40-pin data cable (40 or 80 wires) |
| Small Computer System Interface | SCSI | OUTDATED | can support up to 7 or 15 compliant devices |
| Serial AT Attachment | SATA | YES | serial data path <br> 3 standards (SATA I, SATA II, and SATA III) <br> supports hot-swapping (hot plugging) <br> 7-pin data cable (15-pin power connector) |
| External SATA | eSATA | YES | like a SATA cable, but for expansion |
| Non-Volatile Memory Express | NVMe | YES | used by SSDs only <br> way faster than SATA (6Gb / sec for SATA III while 32Gb / sec for NVMe) | 



<br>
<br>

________
### 02.00 SELF MONITORING ANALYSIS AND REPORTING TECHNOLOGY
________________

abreviated to ```S.M.A.R.T.```, it is a system used to predict when a drive is likely to fail

the BIOS / UEFI use SMART to monitor the drive according to different factors like

* performance
* temperature

* spin-up time
* distance between the head and the disk

it will display a warning message if it suspects a drive failure


<br>
<br>

________
### 03.00 HARD DRIVE SELECTION
________________

the motherboard and the hard drive must support the same interface standard

other things to consider 

* technology
* form factor
* capacity
* data transfer rate
* spindle speed (HDD)
* cache or buffer size (H-HDD)

<br>
<br>

________
### 04.00 RANDOM ACCESS MEMORY
________________

also called ```RAM``` is it the system unit location where the OS, application programs, and data in current use are kept

the data is fast to access but only stays there as long as there is power

it is called RANDOM ACCESS because any storage location can be accessed at any time (not a sequential memory)

on the motherboard, there is two types of memory modules : ```Single In-line Memory Modules``` or ```SIMMs``` and ```Dual In-line Memory Modules``` or ```DIMMs```

the RAM is often devided into two main categories : main RAM and video RAM, the first one for all the data, the second one for the display screen

while the RAM is fast, it is not close nor fast enough for the CPU when it executes its cycles, therefore, the CPU itself has its RAM called ```cache``` which has different levels

<br>

#### 04.01 ARCHITECTURE AND ACCESS

each cell in the RAM has a unique address which can be found by counting the columns, then the rows

there is an address line for each row and column

to access the data in the RAM, the RAM controller sends the column / row address down the address line 

the data is read then sent to the CPU's L1 cache (level 1) through the data lines

<br>

#### 04.02 STATIC RAM

static RAM, also called ```SRAM``` is part of the main RAM, more often used for ```L1 cache``` and ```L2 cache```

it uses 4-6 transistors for each cell, but not a capacitor for every cell

it does not need to be power-refreshed before being access, and is therefore faster to access (25 ns compared to the DRAM's 60 ns)

it is more expansive and requires 4 times the amount of space for a given data amount than DRAM

* the L2 cache uses ```Async Static RAM``` or ```ASRAM```, which is a SRAM simply not synced to the system's clock (therefore, the CPU must wait for the data, about 8.5 ns)

* another type of RAM used for L2 Cache would be the ```Bust Static RAM``` or ```BSRAM```, which is synced to the cache bus clock. It is not often used, and does not work over 66 MHz, so it will probably die soon

* using the same technology as BSRAM, ```Pipeline Burst Static RAM``` or ```PB SRAM``` it created a pipeline for the SRAM request so that they are more instantaneous. it works well with bus speed of over 75 MHz

the best results are 

ASRAM for low bus speed (33 MHz)
BSRAM for med bus speed (50-66 MHz)
PB SRAM for high bus speed (> 75 MHz)

<br>

#### 04.02 DYNAMIC RAM

Dynamic RAM, also called ```DRAM``` is part of the main RAM

each memory cell is pared with a transistor and a capacitor

it requires constrant refreshing as reading discharge the contents, and to maintain a constant charge, it must be refreshed every 15 microseconds

* ```Parity DRAM``` is the name for the 9th bit added to each byte of memory of the DRAM as a parity to verify correct transmissions

* ```Enhanced DRAM``` or ```EDRAM``` is a combination of SRAM and DRAM in a single package, usually for a L2 cache



<br>
<br>

________
### 05.00 SECURE DIGITAL CARDS
________________

often called ```SD Cards``` they are the most popular memory cards

there is 3 standards for SDs :

| NAME | ABV | VERSION | FILE SYSTEM |
|------|-----|---------|-------------|
| regular SD | SD | 1.x | FAT |
| SD High Capacity | SDHC | 2.x | FAT |
| SD eXtended Capacity | SDXC | 3.x | exFAT |

and they come in 3 sizes :
* full-size
* miniSD
* microSD




