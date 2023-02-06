### oscp_prep

## Enumeration 
# 1. Port scan
Below are some useful nmap scan commands
**Default Scripts, enumerate version, output in 3 format files**
Nmap –sC –sV –oA <output_file> <target>
**Default Scripts, enumerate version,sync scan, all TCP ports**
nmap -sS -p- -A <target>
**Default Scripts, enumerate version,sync scan, all TCP+UDP ports**
nmap -sU -sS -p- -A <target>


