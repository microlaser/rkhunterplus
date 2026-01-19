# rkhunter MITM Detection Extension

Advanced detection scripts for ISP-level surveillance, packet replay attacks, 
and Deep Packet Inspection (DPI) infrastructure - extending rkhunter capabilities.

## Background
These scripts were developed in response to documented MITM attacks including:
- NFQUEUE packet diversion for DPI
- VPN packet replay attacks (300+ AEAD decrypt errors)
- Content filtering via firewall rules
- DNS interception

## License
GNU GPL v2.0 - same as rkhunter

This project extends [rkhunter (Rootkit Hunter)](https://rkhunter.sourceforge.net/)
which is licensed under GPL v2.0, copyright Michael Boelen.

## Legal Notice
This tool is designed to detect constitutional violations of the Fourth Amendment
