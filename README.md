# oscp_prep

## Enumeration 
### 1. Port scan<br>
Below are some useful nmap scan commands<br>

**Default Scripts, enumerate version, output in 3 format files**<br>
  nmap –sC –sV –oA <output_file> <target><br>
**Default Scripts, enumerate version,sync scan, all TCP ports**<br>
  nmap -sS -p- -A <target><br>
**Default Scripts, enumerate version,sync scan, all TCP+UDP ports**<br>
  nmap -sU -sS -p- -A <target><br>
**Scan with Scripts**<br>
  nmap -sV --script=ftp\* <target>
** scan targets from text file **
  nmap -iL list-of-ips.txt
