# CE REVISION SHEET 08
## SECURING DATA
<br>

________
### 01.00 ENCRYPTING FILE SYSTEM
________________

also called ```EFS```, it is a way to protect by encryption folders and files

it can only work on drives and partition formatted to the NTFS file system

the encryption is also linked parent-child folder

it encrypts the files according to the user (each user can have independent encrypted files) BUT it is not possible to encrypt files to a group

only a user who has the EFS certificate can move an encrypted file from NTFS to a FAT system

**copying or moving an encrypted file to a non-NTFS partition will decrypt it**


<br>
<br>

________
### 02.00 BITLOCKER
________________

it is an encryption that works on the partition itself, not on the folder or file level

since it is on the partition level, it is either on or off for all users

it can also be used to encrypt a USB drive (make it password restricted)
