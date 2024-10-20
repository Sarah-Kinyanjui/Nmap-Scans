# Nmap Scan

## Overview
This project showcases  the use of Nmap, a powerful open-source tool for network scanning and security assesment. Nmap helps in discovering hosts and services on a computer network, thus providing essential insights for network security.


## Description

Nmap is widely used for network discovery and security auditing. This project. This project includes various types of scans that demonstrate how to assess network security effectively.


## Scans Conducted
The following types of scans were performed as part of this project:

**Ping Scan**
**TCP Connect Scan**
**TCP SYN Scan**
**Service Version Detection**
**Operating System Detection**
**Aggressive Scan**

## How to Use Nmap

To run an Nmap scan, use the following command format:

'''bash
nmap [options] [target] e.g

**nmap -sn 10.0.2.0/24** -This command performs a ping scan on the entire subnet

**nmap -sT -p 80,443 10.0.2.0/24** -This command a full TCP connection scan on port 80 and 443 of specified targets.

**nmap -sS 10.0.2.0/24** -This command performs a stealth scan to identify open ports without establishing a full connection.

**nmap -sV 10.0.2.0/24** -This command detects the version of services running on the target's open ports.

**nmap -O 10.0.2.0/24** -This command determines the operating system of the target host.

**nmap -A 10.0.2.0/24** -This command performs an aggressive scan enabling OS detection, version detection and more.
 
