These files contain a minimal setup for blocking IP addresses that attempt to scan the server ports in any way.

This repository contains 4 files:
1) README.md - contains a description of this repository and files;
2) jail.local - Fail2Ban file. Contains rules related to port scanning;
3) nmap-scan.conf - is intended for use with Fail2ban and contains a filter definition for detecting various types of scans using Nmap;
4) rules.v4 - contains IPTables rules.

As you might have guessed, Fail2Ban and IPTables are used to block port scanning

The work was tested on Debian GNU/Linux 12 (bookworm)
