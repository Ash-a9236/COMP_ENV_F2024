# CE REVISION SHEET 00
## INTRODUCTION TO COMPUTERS
<br>

________
### 01.00 COMPUTER BASES
________________

```A computer is a machine that manipulates data according to a set of instructions```
```A computer is a programmable machine```

#### 01.01 BASIC OPERATIONS

there is 5 basic operations a computer can do : ```INPUT```, ```OUTPUT```, ```PROCESS```, ```STORAGE```, and ```CONTROL```

|OPERATION | |
------|------|
| ```INPUT```   | Capturing or aquiring data / information |
| ```OUTPUT```  | Result when the ```INPUT``` is processed |
| ```PROCESS``` | Transformation process to convert the ```INPUT``` <br> into ```OUTPUT``` | 
| ```STORAGE``` | Retaining data for later retrieval | 
| ```CONTROL``` | Directing the maner and sequence (how) operations are performed |


#### 01.02 CATEGORIES OF COMPUTERS : MOBILE

small computers that are used for personal users, they are not fixed to a location


#### 01.03 CATEGORIES OF COMPUTERS : MICRO

small computers used by personal users, they include workstation and PCs


#### 01.04 CATEGORIES OF COMPUTERS : MAINFRAME

large and powerful computers used by big organizations to process large amount of data


#### 01.05 CATEGORIES OF COMPUTERS : SUPER

the most powerful and expensive, they are used for complex tasks such as scientific research or data analysis


<br>
<br>

________
### 02.00 COMPUTER HARDWARE
________________

computers are divided into two parts : ```HARDWARE``` and ```SOFTWARE```, the hardware is the physical parts of the computer

for more information go to revision sheet CE_01_SystemUnits

#### 02.01 SYSTEM UNITS

they are the core components of a computer sytem

almost all parts of the computer connect to the system units using cables that go into specific ports

examples of system units are
* case
* hard disk
* CPU
* RAM
* fan(s)
* motherboard
...

#### 02.02 INPUT DEVICES

input devices are any peripheral piece of hardware used to provide data, put data, and control signals to the computer

examples of input devices are
* keyboard
* mouse
* touchscreen
* scanner
* webcam

#### 02.03 OUTPUT DEVICES

output devices are any harware component used to commuicate the results of data processing results

examples of ouput devices are
* monitor
* printer
* speakers
* projector

#### 02.04 STORAGE DEVICES

any device capable of storing data

example of storage devices are
* floppy disk
* hard disk
* pen drive
* optical disk


<br>
<br>

________
### 03.00 COMPUTER SOFTWARE
________________

it is the collection of computer programs, procedures, and documentation that perform the different tasks on a computer system

#### 03.01 OPERATING SYSTEM

often abreviated to ```OS```, it is the collectino of software that manages computer hardware ressources and provides common services for computer programs

you cannot run a computer without an OS

examples of OSs
* Windows
* Mac OS
* Linux
* Unix
* Solaris
* Android


#### 03.02 APPLICATION SOFTWARE 

it is often just known as an application or app

it is a software designed to help the user perform a specific task

examples of apps
* Word
* Speadsheet
* Video games
* Graphic editor
* presentation software


#### 03.03 UTILITY SOFTWARE 

it is software designed to help analyze, configure, optimize, or maintain a computer

examples of utility software
* antivirus
* disk defragment
* screensaver
* file manager
* disk cleaner


<br>
<br>

________
### 04.00 COMPUTER PERFORMANCE
________________

there is two types of speeds : the response time (wall-clock time, execution time, or latency), and the throughput (bandwith)

the response time is often what the end-user is worried about, while teh throughput, the number of tasks executed in a certain amount of time, is what the computer cares about

it is often not really possible to describe the performance of a computer with either in terms of constant values, so we useually give them in a ```statistical distribution```

* best-case access time
* worst-case access time

#### 04.01 COMPARING EXECUTION TIME

to compare the execution time of two computers, we use the following formula : 


```math

\frac{Execution..Time..B}{Execution..Time..A} = 1 + \frac{n}{100}

```
<br>

which is the same as saying

```math

\frac{Performance..B}{Performance..A} = 1 + \frac{n}{100}

```
<br>

to find n%, we can use the following : 

```math

n = 100 * \frac{Execution..Time..B - Execution..Time..A}{Execution..Time..A}

```

#### 04.02 COMPARING CPU PERFORMANCE

Be careful! You cannot rely on the specs of the CPU to calculate everything, you need to mesure it yourself

<br>

| VAR |   |   |
|-----|---|---|
| CC | Clock Cycles | A complete CPU cycle :  <br> * Fetch <br> * Decode <br> * Execute <br> * Store |
| CPI | Clock Cycles per Instructions | The number of Cycles it takes to perform an instruction <br> * RISC tries to reduce this to raise efficiency|
| T<sub>ck</sub> | Clock Cycle Time | the interval in between two clock cycles <br> * modern CPUs operate at approximatively 0.33ns (nanoseconds)|


<br>

**Clock Cycle Time**

```math
T_{ck} = \frac{CPU_{time}}{Clock..Cycles}
```
<br>

**Time it takes for a CPU to perform a program**

```math
CPU_{time} = Clock..Cycles * T_{ck}
```

<br>

**Clock Cycles Per Instructions or CPI**

```math
CPI = \frac{CC}{IC} 
```

**CPU time**
```math
CPU_{time} = IC * CPI * T_{ck}
```




