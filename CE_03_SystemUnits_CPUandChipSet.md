# CE REVISION SHEET 02
## SYSTEM UNITS : CPU AND CHIPSET
<br>

the Central Processing Unit is often refered to as the brain of the computer

it is often abrviated to ```CPU```

all the other chips that work with the CPU are called the ```CHIP SET```



<br>

________
### 01.00 CPU
________________


<br>

#### 01.01 SYSTEM CLOCK
 
also called the system timer, it times all the activities on the motherboard

it also shows the speed at which the computer is running, which is measured in ```HERTZ``` or ```Hz```
today, computer runs in ```GHz```, or Gigahertz, which is one billion cycles per second


<br>
<br>

________
### 02.00 BUS
________________

the ```BUS``` is the sytem of pathways used for communication

the bus carries multiple things including 
* power 
* control signals
* memory addresses
* data
* ...

the size (width) of the bus is determined by the data path size, for example, an 8-bit bus will have 8 wires (lines)

<br>

#### 02.01 PCI BUS

a ```PCI``` bus stands for ```Peripheral Component Interconnect```, it is a computer bus designed to connect hardware devices to the motherboard
if it is not specified as ```SERIAL```, the bus is ```PARALLEL```

| BUS | TYPE | DATA PATH (bits / lanes) | ADDRESS LINES | BANDWITH | 
|-----|------|--------------------------|---------------|----------|
|     |      | in bits / lanes max      | in lanes max  | speed max| 
||
| PCI Express 3.0 | Local Video <br> Local I/O | Serial <br> Max : 32 | Max : 32 | Max 32 GB/sec <br> For : 16 lanes |
| PCI Express 2.0 | Local Video <br> Local I/O | Serial <br> Max : 32 | Max : 32 | Max 16 GB/sec <br> For : 16 lanes |
| PCI Express 1.1 | Local Video <br> Local I/O | Serial <br> Max : 16 | Max : 16 | Max 8 GB/sec <br> For : 16 lanes |
| PCI-X | Local I/O | Max : 64 | Max : 32 | Max 8.5 GB/sec |
| PCI | Local I/O | Max : 32 OR 64 | Max : 32 OR 64 | Max 133 MB/sec <br> OR 266 MB/sec <br> OR 532 MB/sec |
||
| *PCI Express 4.0* | L*ocal Video <br> Local I/O* | *Serial <br> Max : 32* | *Max : 32* | *Max 64 GB/sec <br> For : 16 lanes* |
||
| FireWire 400 | Local I/O <br> Expansion | Max : 1 | Serial | Max : 302 Gbps |
| FireWire 800 | Local I/O <br> Expansion | Max : 1 | Serial | Max : 302 Gbps |
||
| USB 1.1 | Expansion | Max : 1 | Serial | Max 12 Mbps <br> OR 480 Mbps <br> OR 5.0 Gbps |
| USB 2.0 | Expansion | Max : 1 | Serial | Max 12 Mbps <br> OR 480 Mbps <br> OR 5.0 Gbps |
| USB 3.0 | Expansion | Max : 1 | Serial | Max 12 Mbps <br> OR 480 Mbps <br> OR 5.0 Gbps |




<br>

#### 02.02 DATA BUS


<br>

#### 02.03 FRONT SIDE BUS

often abreviated to ```FSB```, is is the bus that connects the ```CPU``` to the ```NORTHBRIDGE```

<br>
<br>

________
### 03.00 CHIPSET : NORTHBRIDGE
________________

also called the ```MCH``` or ```Memory Controller Hub```, the northbridge

<br>
<br>

________
### 04.00 CHIPSET : SOUTHBRIDGE
________________







