# 7911
These files are supposed to be placed at the root of the TFTP server specified in the DHCP.

## Mac Address :
The mac address in the SEP<mac>.cnf.xml has to be given in shift and attached.
For example : ```SEP0021A02C38B5.cnf.xml```
Operation has to be repeated for every phone.

## List XML :
This file is used to give a list of thumbnails to be putted as logo (has to be done manually on every phone)
File has to be at root of TFTP and images are to be precisely on spec. (will not work otherwise)

## Dialplan.xml
Still needing to understand why it doesn't work if the file doesn't exist but why the phone ignores the content inside...

## Note :
The software version in the file needs to be set to the exact version you are flashing the phones on. If you have the firmwares vor version X but your SEP<Mac>.cnf.xml says Y, it's going to bootloop.
