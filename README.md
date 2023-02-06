### oscp_prep

## Enumeration 
# 1. Port scan<br>
Below are some useful nmap scan commands<br>
**Default Scripts, enumerate version, output in 3 format files**<br>
Nmap –sC –sV –oA <output_file> <target><br>
**Default Scripts, enumerate version,sync scan, all TCP ports**\n<br>
nmap -sS -p- -A <target><br>
**Default Scripts, enumerate version,sync scan, all TCP+UDP ports**<br>
nmap -sU -sS -p- -A <target><br>


