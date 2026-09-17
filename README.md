Ethical Hacking and Penetration Testing
=======================================

Project Overview
----------------

This repository contains my **IT7301 – Ethical Hacking** group project at **Bahrain Polytechnic**.

The project demonstrates a complete **penetration testing lifecycle** against **Metasploitable 2**, an intentionally vulnerable Linux system, within an isolated virtual laboratory.

The assessment covered reconnaissance, scanning, enumeration, vulnerability assessment, controlled exploitation, post-exploitation, covering tracks, risk assessment, security policies, and defensive recommendations.

Methodology
-----------
```
Footprinting
     ↓
Scanning
     ↓
Enumeration
     ↓
Vulnerability Scanning
     ↓
Gaining Access
     ↓
Maintaining Access
     ↓
Covering Tracks
     ↓
Risk Assessment
     ↓
Security Policies
     ↓
Defensive Recommendations
```
Laboratory Environment
----------------------

The laboratory was built using **Oracle VirtualBox** with a controlled **NAT Network**.

ComponentPurposeKali LinuxPenetration TestingMetasploitable 2Vulnerable TargetOracle VirtualBoxVirtualizationNAT NetworkIsolated Communication

Tools & Technologies
--------------------

*   **Kali Linux**
    
*   **Metasploitable 2**
    
*   **Oracle VirtualBox**
    
*   **Nmap**
    
*   **Angry IP Scanner**
    
*   **Metasploit Framework**
    
*   **Medusa**
    
*   **Greenbone Enterprise**
    
*   **Wireshark**
    
*   **Scapy**
    
*   **Linux / Windows**
    

Reconnaissance & Enumeration
----------------------------

### Footprinting

Information gathering was performed using:

*   nslookup
    
*   WHOIS
    
*   DNS reconnaissance
    

### Scanning

Network and service discovery was performed using **Nmap** and **Angry IP Scanner** to identify hosts, open ports, running services, and potential attack surfaces.

### Enumeration

Discovered services were further investigated, including:

*   SSH
    
*   FTP
    
*   SMB
    
*   RSH
    
*   DistCC
    
*   Web services
    

Vulnerability Assessment
------------------------

**Greenbone Enterprise** was used to identify known vulnerabilities and insecure configurations within the controlled laboratory environment.

The findings were then used to support the exploitation and risk assessment stages.

Gaining Access
==============

The project demonstrated multiple controlled attack scenarios against Metasploitable 2.

### SSH Authentication Attack

A controlled password attack was performed against the SSH service using **Medusa**, demonstrating the security risks associated with weak/default authentication.

### vsftpd Backdoor

The vulnerable **vsftpd 2.3.4** service was assessed using the **Metasploit Framework**.

**CVE:** CVE-2011-2523

The exploitation demonstrated how a vulnerable service can result in remote shell access.

### DistCC Remote Command Execution

The exposed DistCC service was assessed using Metasploit.

**CVE:** CVE-2004-2687

The exercise demonstrated remote command execution without normal authentication.

### RSH Authentication Weakness

The legacy RSH service was assessed using Metasploit.

**CVE:** CVE-1999-0651

The exercise demonstrated the risks of insecure trust-based authentication and legacy remote access protocols.

Maintaining Access & Privilege Escalation
=========================================

Post-exploitation activities were performed to verify access and privileges.

The assessment demonstrated how excessive privileges and insecure configurations can allow an attacker with an initial foothold to obtain administrative-level access.

Commands such as:

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   whoami  id   `

were used to verify the obtained privileges.

Covering Tracks
===============

The project examined how local shell history can be removed or modified after compromise.

This was studied from a **defensive and forensic perspective**, highlighting the importance of:

*   Centralized logging
    
*   SIEM
    
*   Real-time monitoring
    
*   Tamper-resistant logs
    
*   Audit trails
    

Risk Assessment
===============

The project included a risk assessment based on likelihood and impact.

FactorAssessmentLikelihoodHighImpactHighOverall RiskHigh

Security Policies
=================

Based on the penetration testing findings, four security policies were developed:

### Access Management Policy

Focuses on secure authentication, authorization, least privilege, and privileged access.

### Internal Access Control Policy

Focuses on restricting unnecessary and insecure internal network services.

### System Protection Management Policy

Focuses on system hardening, secure configurations, patching, and vulnerability management.

### Log Management Policy

Focuses on centralized logging, monitoring, protection of logs, and security alerts.

Defensive Recommendations
=========================

The project recommended:

*   System hardening
    
*   Removing outdated and unnecessary services
    
*   Strong authentication
    
*   Least privilege
    
*   Network access restrictions
    
*   Regular vulnerability assessments
    
*   Security logging and monitoring
    
*   SIEM implementation
    
*   Regular configuration reviews
    
*   Clearly defined security policies
    

Key Findings
============

AreaFindingImpactAuthenticationWeak/default credentialsUnauthorized accessFTPVulnerable vsftpd serviceRemote shell accessDistCCInsecure exposed serviceRemote command executionRSHLegacy authenticationAdministrative accessPrivilegesExcessive privilegesRoot-level accessLoggingLocal history can be removedReduced forensic visibility

My Contribution
===============

My contribution to the group project included:

*   **Enumeration**
    
*   **Gaining Access**
    
*   **Maintaining Access / Post-Exploitation**
    
*   Technical documentation and evidence
    

**Workload:** 25%**Completion:** 100%

Key Learning Outcomes
=====================

This project provided practical experience in:

*   Ethical hacking methodology
    
*   Network reconnaissance
    
*   Nmap scanning
    
*   Service enumeration
    
*   Vulnerability assessment
    
*   Metasploit
    
*   Authentication attacks
    
*   Post-exploitation
    
*   Privilege escalation
    
*   Risk assessment
    
*   Security policies
    
*   System hardening
    
*   Security monitoring
    

Project Report
==============

The complete academic report contains the detailed methodology, screenshots, evidence, vulnerability analysis, risk assessment, security policies, recommendations, and references.

[**Download the IT7301 Ethical Hacking Project Report**](IT7301-Ethical-Hacking-Penetration-Testing-Report.docx)

Academic Context
================
```
Category            Details
Course              IT7301 – Ethical Hacking
Institution         Bahrain Polytechnic
Assessment          Group Project
Primary Platform    Kali Linux
Target              Metasploitable 2
Environment         Oracle VirtualBox
```
Disclaimer
==========

> **Educational and Authorized Use Only**
> 
> This project was conducted exclusively for academic and cybersecurity learning purposes within an isolated virtual laboratory.
> 
> The techniques demonstrated are intended only for authorized security testing. Unauthorized access, exploitation, or credential attacks against systems without permission may be illegal and harmful.
