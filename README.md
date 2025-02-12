
# RMIT-Cybersecurity-Project

## Overview

In this team project comprised of four members including myself, the primary objective is to design and implement a cybersecurity improvement and management plan for XYZ which company comprises of 20-40 employees with a basic SOHO network environment. To achieve the objective, the team is required to leverage introductory Red Team and Blue Team methods to test, verify, and establish a secure system resistant to common vulnerabilities. Note that although we worked as a team, the RMIT project assessment requires each team member to build up the virtual environment personally and demonstrates running configuration to the teacher. Thus, all screenshots provided in this portfolio are from my own labs.

Over the course of 5 weeks project duration, our team had:
- Collaborated on decision-making to outline an effective cybersecurity strategy.
- Configured and deployed lab environments for simulated attacks and defense.
- Executed tests to identify vulnerabilities and validated the system's security measures.
- Assessed and refined the cybersecurity management plan based on test results.

This project was designed to deliver a robust and actionable cybersecurity framework while fostering team collaboration, effective communication, and applying various foundational offensive and defensive security practices learned throughout the entire semesters.

### Skills Learned

- Testing concepts and procedures for cybersecurity including virtualisation (creating, configuring, and interconnecting virtual images)
- Installing and using software packages including those for testing
- Using procedures and tools to identify data traffic anomalies
- Connecting cyber security equipment and networked devices
- Utilizing basic Linux commands
- Interpreting and writing basic scripts
- Installing and configuring firewalls
- Implementing Intrusion Prevention Systems (IPS) to monitor data traffic and block malicious traffic
- Utilizing cloud computing solutions for remote access and off-premise data backup

### Tools & Software Used

- Red Teaming       : Kali Linux (NMAP Scan, Ettercap, Zphisher, SMB Map)
- Blue Teaming      : ELK Stack SIEM, Snort IPS, CCProxy
- Network Analysis  : Wireshark, Cisco Packet Tracer
- Operating System  : Windows Server 2022 + Active Directory, pfSense FW, Linux Mint
- Virtualization    : Oracle Virtualbox
- Cloud             : Microsoft Azure (Azure VM, Azure Backup)

## The Project: Summary of XYZ Company 

- The company is new to cybersecurity; it operates a subscriber website hosting and selling digitial creative contents via a web server stored in the cloud.
- Acquire Personally Identifiable Information (PII) and Personal Financial Information (PFI) from users upon subscribing; they are stored in external hard drive or office PC.
- Account access managed through usernames and passwords are issued by a director; details stored in a shared spreadsheet.
- Staff can create new accounts with other web resources and forward the login details of those accounts to the director for safekeeping and to maintain business interests too. 
- Office contains an ARLO nanny cam connected to Wi-Fi for after-hours monitoring with camera angle located behind front desk PC, overlooking the keyboard and monitor.
- IoT devices (laptops, printers, peripherals) used on-site and offsite.
- Both Guest and Staff use personal devices on the workplace network; WFH staff access company resources over various unsecured networks.
- There have been reports that some staff use the company's network or PC during work hours to play online games; they turned off Windows firewalls to access the game, and sometimes forgot to turn it back on.

![Client topology screenshot](https://github.com/user-attachments/assets/0884d27f-7384-468a-967a-1bd70291cb38)

*Ref 1: XYZ Network Topology before the improvement. The Goal is to secure existing infrastructure with security tools, software, physical infrastructure, access management, and monitoring, as well as
Developing a plan for additional security measures.*

## Project Activities & Labs

| Activities                                         | Associated Lab         |
|-----------------------------------------------|----------------------------|
| **Red Teaming:** |
| &nbsp;&nbsp;&nbsp;&nbsp;Nmap Scan | <a href="https://github.com/Kazu010101/Nmap-Scan-RMIT-Cybersecurity-Project/blob/main/README.md">Nmap Scan</a>|
| &nbsp;&nbsp;&nbsp;&nbsp;DoS Attack | <a href="https://github.com/Kazu010101/DoS-Attack-RMIT-Cybersecurity-Project/blob/main/README.md"> Ettercap DoS Attack</a>|
| &nbsp;&nbsp;&nbsp;&nbsp;Social Engineering Attack        | <a href="https://github.com/Kazu010101/Zphisher-RMIT-Cybersecurity-Project"> Zphisher Phishing Attack </a>|
| &nbsp;&nbsp;&nbsp;&nbsp;Data Exfiltration        | <a href="https://github.com/Kazu010101/SMB-Map-RMIT-Cybersecurity-Project"> Smbmap, smbclient </a>|
| **Blue Teaming:** |
| &nbsp;&nbsp;&nbsp;&nbsp;Windows Server 2022 (Virtual Machine) | <a href="https://github.com/Kazu010101/Win-Server-2022-RMIT-Cybersecurity-Project/blob/main/README.md"> Install Windows-Server 2022 VM </a>|
| &nbsp;&nbsp;&nbsp;&nbsp;Active Directory Domain Controller (ADDC)               | <a href="https://github.com/Kazu010101/Active-Directory-RMIT-Cybersecurity-Project"> Install ADDC </a>|
| &nbsp;&nbsp;&nbsp;&nbsp;Active Directory OU, Users, Group, Password Policy | <a href="https://github.com/Kazu010101/AD-Setup-OU-User-Group-Policy-RMIT-Cybersecurity-Project/blob/main/README.md"> AD Setups </a>|
| &nbsp;&nbsp;&nbsp;&nbsp;pfSense Firewall | IN PROGRESS|
| &nbsp;&nbsp;&nbsp;&nbsp;Snort IPS | IN PROGRESS|
| &nbsp;&nbsp;&nbsp;&nbsp;Elastic SIEM | IN PROGRESS|
| &nbsp;&nbsp;&nbsp;&nbsp;AD linked with CCProxy | IN PROGRESS|
