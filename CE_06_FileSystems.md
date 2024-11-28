# CE REVISION SHEET 06
## FILE SYSTEMS


<br>


________
### 01.00 FILE SYSTEMS
________________

computer use different and particular file systems to store, organize, and to be able to later retrieve data or media

the different format a file system can have is called a ```file system type```
the format determines how the information is stored as files and directories


<br>
<br>

________
### 02.00 FILE ALLOCATION TABLE
________________

also called ```FAT```, it was the primary file system used by Microsoft

nowdays, we use ```FAT``` and ```FAT32``` when file need to be accessed by multiple versions of Windows

| NAME | VERSION | MAX DRIVE SIZE | DATE |
|------|---------|----------------|------|
| FAT12 | 12-bit | 32MB  | 1977 |
| FAT16 | 16-bit | 2GB | 1988 |
| FAT32 | 32-bit | 8TB (theory) <br> 137GB (real) | 1996 | 



<br>
<br>

________
### 03.00 NEW TECHNOLOGY FILE SYSTEM
________________

also called ```NTFS```, it is the primary file system used by Microsoft today

it should always be used for files over 4GB

| NAME | MAX DRIVE SIZE | DATE |
|------|----------------|------|
| NTFS | 256TB | 1993 |

The main difference between ```FAT``` and ```NTFS``` is that NTFS is more secure since it allows to define file and folder permission for users and groups

#### 03.00 FILE PERMISSIONS

the standard permission is the most commonly used

the special permissions are more complex to manage but allow to completly control who does what with each file or folder

When a child folder is created, it inherit the parent folder's permission set (which means that permission can be created and added at key points only)

If you change a folder or file of place, they will take the new parent folder's permission set BUT **deny permission will override allow**

** (a ' - ' means ' view ')

| PERMISSION LEVEL | FILE | ATTRIBUTES | OWNERSHIP | PERMISSION SET |
|------------------|------|------------|-----------|----------------|
| READ | read | - | - | - |
| WRITE | read <br> overwrite | change | - | - |
| LIST FOLDER CONTENT | read all folders connected | - | - | - |
| READ & EXECUTE | read <br> run <br> execute | - | - | - |
| MODIFY | read <br> run <br> execute <br> modify <br> delete | change | - | - |
| FULL CONTROL | all | change | take | change |




