# oscp_prep

## Enumeration 
### 1. Port scan<br>
Below are some useful nmap scan commands<br>

**Default Scripts, enumerate version, output to file in nmap format**<br>
  nmap –sC –sV –oN <output_file> target <br>
**Default Scripts, enumerate version,sync scan, all TCP ports**<br>
  nmap -sS -p- -A target <br>
**Default Scripts, enumerate version,sync scan, all TCP+UDP ports**<br>
  nmap -sU -sS -p- -A target <br>
**Scan with Scripts**<br>
  nmap -sV --script=ftp* target <br>
**Scan targets from file**<br>
  nmap -iL list-of-ips.txt
**
