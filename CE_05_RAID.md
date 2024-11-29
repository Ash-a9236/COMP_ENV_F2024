# CE REVISION SHEET 05
## REDUNDANT ARRAY INDEPENDENT DISK


<br>


________
### 01.00 RAID
________________

abreviated to ```RAID```, it is a way of storing data on multiple physical disks for fault tolerance (redundancy), improved performance, or both

it is arranged in an array of disks that will only appear as one disk in the host system

**RAID should not replace server backups**

to manage RAID arrays, there is hardware (RAID controller), and/or software

there is 7 levels of RAID, from RAID 0 to RAID 6


<br>

#### 01.01 HARDWARE RAID

to implement hardware RAID, we install a ```RAID controller``` in the server, then it is possible to configure RAID by using the configuration tool

<br>

#### 01.02 SOFTWARE RAID

to implement software RAID, you need to 

1. expose all the disks available on the server to the OS 
2. manually configuring RAID from within the OS


<br>
<br>

________
### 02.00 SPANNED VOLUMNE
________________

also known as ```JBOD```, it is a special formatted partition for data that is stored on more than one disk

```JBOD``` partition will make it appear as the data only comes from one disk

it stores the data sequentially (as if each disk is a continuation of the previous one)

| ADVANTAGE | DISADVENTAGE |
|-----------|--------------|
| easy expansion <br> availability of 100 % of the disks total capacity | all data will be lost if one disk fails |


<br>
<br>

________
### 03.00 RAID 0
________________

also known as ```STRIPPING```

it maps data across the physical drives in an arra to create a large virtual disk
the data is then divided into consecutive segments or stripes that are written sequentially across the drives

improved performance (fastest RAID mode)

no disk failure possible without the loss of data


<br>
<br>

________
### 04.00 RAID 1
________________

also known as ```MIRRORING```

it needs to have two disks of equal capacity

all the data will be written on both disks

it will cut the disk capacity by 50% since each bit of data is stored on both (it is the same as having one disk)


<br>
<br>

________
### 05.00 RAID 2 TO 4
________________

<br>

#### 05.00 RAID 2

Bit-level striping with Hamming code for error correction, providing good read and write performance

fault tolerance for one drive failure.

<br>

#### 05.01 RAID 3

Byte-level striping with dedicated parity, providing good read and write performance

fault tolerance for one drive failure.

<br>

#### 05.02  RAID 4

Block-level striping with dedicated parity, providing good read and write performance

with fault tolerance for one drive failure.

<br>
<br>

________
### 06.00 RAID 5
________________

it writes the data across al disks in the volume and has a parity block for each data block

a minimum of three disks is required (one disk will be used to maintain fault tolerance)

if one physical disk fails, the data from the failed disk can be rebuilt

one drive fault tolerance


<br>
<br>

________
### 07.00 RAID 6
________________

it writes data across all disks in the array and has two (2) parity blocks for each data block

a minimum of four (4) disks is required (two (2) disk will be used to maintain fault tolerance)

two drives fault tolerance

<br>
<br>

________
### 08.00 RAID 10 OR 1+0
________________

combination of RAID 1 and RAID 0

takes at least 4 disks

the data is mirroired accross pairs of disks




