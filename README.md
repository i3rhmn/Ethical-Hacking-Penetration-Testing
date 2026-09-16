# Ethical Hacking and Penetration Testing

This repository contains my IT7301 Ethical Hacking project, demonstrating a controlled penetration testing exercise conducted in an isolated virtual laboratory environment.

The project follows the ethical hacking lifecycle from reconnaissance and information gathering through scanning, enumeration, vulnerability assessment, gaining access, maintaining access, covering tracks, and finally documenting findings and security recommendations.

# Project Overview

The main target used in the laboratory was Metasploitable 2, a deliberately vulnerable Linux virtual machine designed for penetration testing and security training.

The laboratory environment was built using Oracle VirtualBox with a NAT Network to provide controlled communication between the virtual machines. Kali Linux was used as the primary penetration testing system.

# Ethical Hacking Methodology

The project covers the following stages:

- Footprinting
- Scanning
- Enumeration
- Vulnerability Scanning
- Gaining Access
- Maintaining Access
- Covering Tracks
- Penetration Testing Report
- Security Policy Development
- Security Recommendations

# Tools and Technologies

- Kali Linux
- Metasploitable 2
- Oracle VirtualBox
- Nmap
- Angry IP Scanner
- Metasploit Framework
- Greenbone Enterprise
- Wireshark
- Scapy
- Linux
- Windows
- NAT Network

# Footprinting

The footprinting stage focused on gathering information about selected targets using reconnaissance techniques.

Examples included DNS and domain information gathering using tools such as:

- nslookup
- WHOIS
- DNS reconnaissance

# Scanning

Network and service scanning techniques were performed to identify accessible hosts, open ports, running services, and potential attack surfaces.

Nmap was used extensively for network and service discovery.

# Enumeration

Enumeration was performed to gather additional information from discovered services, including web services, FTP, SMB, and other network services.

The objective was to identify configuration weaknesses and information that could support later security assessment activities.

# Vulnerability Scanning

Vulnerability assessment was performed using vulnerability scanning tools to identify known weaknesses and insecure configurations within the controlled laboratory environment.

Greenbone Enterprise was used as part of the vulnerability assessment process.

# Gaining Access

The project demonstrated controlled exploitation of vulnerabilities identified during earlier stages of the assessment.

Metasploit and other penetration testing techniques were used within the isolated laboratory environment to demonstrate the impact of vulnerable services and configurations.

# Maintaining Access

Post-exploitation activities were documented to demonstrate how an attacker could maintain access to a compromised system in a controlled testing environment.

# Covering Tracks

The project also examined the security implications of attacker attempts to reduce or remove evidence of activity.

This stage was studied from a defensive perspective to understand the importance of logging, monitoring, and security auditing.

# Security Policies

Security policies were developed based on the findings identified during the penetration testing process.

The project included policies related to:

- System Protection Management
- Log Management
- Access Management
- Internal Network Access Management

# Defensive Recommendations

The project identified several defensive measures, including:

- System hardening
- Removing outdated services
- Restricting unnecessary network services
- Strengthening authentication
- Continuous vulnerability assessment
- Security logging and monitoring
- Regular system reviews
- Clearly defined security policies

# Laboratory Environment

All penetration testing activities were conducted within an isolated virtual laboratory environment.

The lab used Oracle VirtualBox and a NAT Network, with Kali Linux acting as the primary testing machine and Metasploitable 2 serving as the intentionally vulnerable target.

# Project Report

The complete project report is available below:

[Download the IT7301 Ethical Hacking Project Report](IT7301-Ethical-Hacking-Penetration-Testing-Report.docx)

# Academic Context

Course: IT7301 – Ethical Hacking

Institution: Bahrain Polytechnic

Assessment Type: Group Project

# Disclaimer

This project was conducted for academic and cybersecurity learning purposes in a controlled and isolated laboratory environment.

The techniques demonstrated in this project are intended for authorized security testing and educational use only.
