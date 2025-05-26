# Port-Scanning-with-Nmap
Network port scanning with Nmap and security analysis.

//Verify Nmap Installation

nmap --version

//Expected output should show:

Nmap version 7.97 ( https://nmap.org )
Platform: x86_64-apple-darwin

//Find Your Local IP Range

ifconfig

//Try TCP SYN Scan (requires root)

sudo nmap -sS 192.168.1.0/24
