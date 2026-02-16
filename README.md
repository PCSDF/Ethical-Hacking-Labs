# ⚔️ Ethical Hacking Labs & Tutorials
## Official Training Course | Pakistan Cyber Security Defense Foundation (PCSDF)

[![PCSDF](https://img.shields.io/badge/Organization-PCSDF-green)](https://github.com/pcsdf)
[![Domain](https://img.shields.io/badge/Domain-Offensive%20Security-red)](#-ethical-hacking)
[![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-blue)](#-core-knowledge)

> **A complete, hands-on collection of labs for ethical hacking students, network administrators, and cybersecurity enthusiasts. These tutorials guide you from the basics of Linux and Networking to advanced exploitation and forensics.**



---

## ⚠️ Ethical & Legal Disclaimer
> **This repository is for Educational and Authorized Professional use only.**
> 
> * DO NOT attempt these techniques on any public network or system you do not own.
> * Unauthorized access is a serious cybercrime.
> * **PCSDF** is not responsible for any misuse of the techniques described herein. Practice **only** on your local lab environment.

---

## ✅ Prerequisites

Before starting, ensure your lab environment is ready:
* **RAM:** 8GB minimum (16GB recommended).
* **Storage:** At least 80GB of free disk space.
* **Virtualization:** Hardware-based virtualization enabled (Intel VT-x / AMD-V).
* **Software:** VirtualBox or VMware Workstation.

---

## ⚙️ Module 0: Core Knowledge
*Build the foundation before you break the walls.*

If you are new to IT, do not skip this. You need to understand how systems work before you can exploit them.

* [Networking 101](./0-Core-Knowledge/0-Networking-101.md)
* [Lab Building & Virtualization](./0-Core-Knowledge/1-Lab-Building.md)
* [Introduction to Linux](./0-Core-Knowledge/2-Intro-to-Linux.md)
* [Information Security 101](./0-Core-Knowledge/4-Infosec-101.md)

---

## ⚔️ Module 1: The Ethical Hacking Lifecycle

### 1. Footprinting & Reconnaissance
Gathering intelligence on your target.
* [Introduction to Footprinting](./1-Footprinting-and-Reconnaissance/0-What-is-Footprinting.md)
* [Windows Command Line Recon](./1-Footprinting-and-Reconnaissance/1-Windows-CommandLine.md)
* [Maltego Basics](./1-Footprinting-and-Reconnaissance/2-Maltego-Basics.md)
* [Recon-ng Framework](./1-Footprinting-and-Reconnaissance/3-Recon-ng.md)
* [OSRFramework](./1-Footprinting-and-Reconnaissance/4-OSRFramework.md)
* [Metasploit Basics](./1-Footprinting-and-Reconnaissance/5-Metasploit-Basics.md)
* [The Harvester](./1-Footprinting-and-Reconnaissance/6-theHarvester.md)

### 2. Scanning Networks
Discovering live hosts and open ports.
* [Scanning Methodologies](./2-Scanning-Networks/0-Scanning-a-Target-Network.md)
* [hping3](./2-Scanning-Networks/1-hping3.md)
* [OS Detection via TTL](./2-Scanning-Networks/2-TTL.md)
* [Mega Ping](./2-Scanning-Networks/3-MegaPing.md)
* [Nmap Basics](./2-Scanning-Networks/4-Nmap.md)
* [Evading Detection (Nmap Decoy)](./2-Scanning-Networks/5-NmapDecoyIP.md)

### 3. Enumeration
Extracting user names, machine names, and network resources.
* [Enumeration Concepts](./3-Enumeration/0-Introduction.md)
* [Nmap Scripting Engine (NSE)](./3-Enumeration/1-Enumerating-with-Nmap.md)
* [SNMP Enumeration](./3-Enumeration/2-SNMP-Enumeration.md)
* [Enum4Linux (Samba)](./3-Enumeration/3-Enum4linux-Win-and-Samba-Enumeration.md)

### 4. Vulnerability Analysis
* [Overview & Tools](./4-Vulnerability-Analysis/Overview-and-Tools.md)

### 5. System Hacking
Gaining access, escalating privileges, and covering tracks.
* [LLMNR / NBT-NS Spoofing](./5-System-Hacking/1-LLMNR-NBT-NS.md)
* [Cracking SAM Hashes](./5-System-Hacking/2-SAM-Hashes.md)
* [Rainbow Tables](./5-System-Hacking/3-Rainbow-tables.md)
* [Escalating Privileges](./5-System-Hacking/5-Escalating-Privileges.md)
* [Hacking via Malicious Office Files](./5-System-Hacking/6-Hacking-Windows-with-Doc-file.md)
* [Post-Exploitation (Meterpreter)](./5-System-Hacking/7-Hacking-Windows-with-Metasploit-PostExploitation.md)
* [Hiding Data (NTFS Streams)](./5-System-Hacking/8-NTFS-Streams.md)
* [Steganography](./5-System-Hacking/9-Steganography.md)

### 6. Malware Threats
* [Using njRAT](./6-Malware/1-Using-njRAT.md)
* [HTTP RAT Trojan](./6-Malware/2-HTTP-Trojan.md)
* [Obfuscation (SwayzCryptor)](./6-Malware/3-Obfuscating-Trojan-SwayzCryptor.md)
* [Malware Analysis Lab](./6-Malware/4-Malware-Analysis-Lab.md)

### 7. Sniffing & MITM
* [MITM with BetterCAP](./7-Sniffing/1-MITM-with-Bettercap.md)
* [MAC Address Spoofing](./7-Sniffing/2-Spoofing-MAC-address.md)

### 8. Social Engineering
* [Using SET (Social Engineering Toolkit)](./8-Social-Engineering/1-Using-SET.md)

### 9. Denial of Service (DoS)
* [SYN Flooding](./9-Denial-of-Service/1-SYN-Flooding.md)
* [DDoS using HOIC](./9-Denial-of-Service/2-DDoS-using-HOIC.md)
* [Detecting DoS Traffic](./9-Denial-of-Service/3-Detecting-DoS-Traffic.md)

### 10. Session Hijacking
* [Using OWASP ZAP](./10-Session-Hijacking/1-Using-ZAP.md)
* [Intercepting HTTP Traffic](./10-Session-Hijacking/2-Intercepting-HTTP-Traffic.md)

---

## 🔬 Bonus: Digital Forensics Approach
Understand how blue teams analyze attacks.
* [TCPDump Tutorial](./11-Bonus/TCPDump-Tutorial.md)
* [Dissecting Packets](./11-Bonus/Dissecting-packets.md)
* [ExifTool (Metadata Analysis)](./11-Bonus/ExifTool-Tutorial.md)
* [Recovering Deleted Partitions](./11-Bonus/Recovering-Deleted-Partition.md)
* [Recovering Deleted Files](./11-Bonus/Recovering-Deleted-Files.md)

---

## 🚧 Roadmap & Status
![](https://img.shields.io/badge/Status-Active%20Development-orange)

* [x] Core Networking & Linux
* [x] System Hacking & Malware
* [ ] Active Directory Attacks (Coming Soon)
* [ ] Web Application Bug Hunting (Coming Soon)
* [ ] Wireless Hacking (WPA/WPA2)

---

## 🏆 Credits & Maintainers

**Maintained by:** [Pakistan Cyber Security Defense Foundation (PCSDF)](https://github.com/pcsdf)

* **Original Labs:** Adapted from open-source community contributions (Samsar4).
* **Curriculum Lead:** PCSDF Offensive Security Team.

**Connect with us:**
* 🌐 **GitHub:** [github.com/pcsdf](https://github.com/pcsdf)
* 🛡️ **Motto:** *Defending Digital Borders through Intelligence.*
