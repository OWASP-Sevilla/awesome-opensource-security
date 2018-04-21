# opensource-threat-detection

A collection of open source threat detection tools

## Collections

Cryptomining

* [1lastBr3ath/drmine - Dr. Mine is a node script written to aid automatic detection of in-browser cryptojacking](https://github.com/1lastBr3ath/drmine)  

Sniffer / packet analysis

* [dirtbags/pcapdb - A Distributed, Search-Optimized Full Packet Capture System](https://github.com/dirtbags/pcapdb)
* [TravisFSmith/SweetSecurity - Network Security Monitoring on Raspberry Pi type devices](https://github.com/TravisFSmith/SweetSecurity)
* [noddos - Noddos client](https://github.com/noddos/noddos)
* [Suricata - a free and open source, mature, fast and robust network threat detection engine](https://suricata-ids.org/)
* [aol/moloch - Moloch is an open source, large scale, full packet capturing, indexing, and database system](https://github.com/aol/moloch)

Host based detection tools / endpoint tools

* [Invoke-IR/Uproot - a Host Based Intrusion Detection System (HIDS) that leverages Permanent Windows Management Instrumentation (WMI) Event Susbcriptions to detect malicious activity on a network](https://github.com/Invoke-IR/Uproot)
* [hasherezade/pe-sieve - Scans a given process, searching for the modules containing in-memory code modifications. When found, it dumps the modified PE](https://github.com/hasherezade/pe-sieve)
* [hasherezade/hollows_hunter - A process scanner detecting and dumping hollowed PE modules](https://github.com/hasherezade/hollows_hunter)
* [shellster/DCSYNCMonitor - Monitors for DCSYNC and DCSHADOW attacks and create custom Windows Events for these events](https://github.com/shellster/DCSYNCMonitor)
* [jaredcatkinson/Get-InjectedThread.ps1 - Looks for threads that were created as a result of code injection](https://gist.github.com/jaredcatkinson/23905d34537ce4b5b1818c3e6405c1d2)
  * [Understanding and Evading Get-InjectedThread](https://blog.xpnsec.com/undersanding-and-evading-get-injectedthread/)
* [TonyPhipps/THRecon - Collect endpoint information for use in incident response triage / threat hunting / live forensics using this toolkit](https://github.com/TonyPhipps/THRecon)
* [ysrc/yulong-hids - 一款由 YSRC 开源的主机入侵检测系统](https://github.com/ysrc/yulong-hids)

Webshell

* [baidu-security/webshell-scanner-client - A golang client of https://scanner.baidu.com](https://github.com/baidu-security/webshell-scanner-client)
* [nbs-system/php-malware-finder - Detect potentially malicious PHP files](https://github.com/nbs-system/php-malware-finder)
* [emposha/PHP-Shell-Detector - a php script that helps you find and identify php/cgi(perl)/asp/aspx shells](https://github.com/emposha/PHP-Shell-Detector)

Monitor

* [realparisi/WMI_Monitor - Log newly created WMI consumers and processes](https://github.com/realparisi/WMI_Monitor)
* [luctalpe/WMIMon - Tool to monitor WMI activity on Windows](https://github.com/luctalpe/WMIMon)

Powershell

* [danielbohannon/Revoke-Obfuscation - PowerShell Obfuscation Detection Framework](https://github.com/danielbohannon/Revoke-Obfuscation)

Logging

* [Scribery/tlog - Terminal I/O logger](https://github.com/Scribery/tlog)
  * [USER SESSION RECORDING - An Open Source solution](https://ruxcon.org.au/assets/2017/slides/Session%20Recording%20Ruxcon%202017.pdf)

Log analysis / Visualization

* [JPCERTCC/LogonTracer - Investigate malicious Windows logon by visualizing and analyzing Windows event log](https://github.com/JPCERTCC/LogonTracer)
* [THIBER-ORG/userline - Query and report user logons relations from MS Windows Security Events](https://github.com/THIBER-ORG/userline)
* [austin-taylor/VulnWhisperer - Create actionable data from your Vulnerability Scans](https://github.com/austin-taylor/VulnWhisperer)

Windows event forwarding

* [palantir/windows-event-forwarding - A repository for using windows event forwarding for incident detection and response](https://github.com/palantir/windows-event-forwarding)
  * [Windows Event Forwarding for Network Defense](https://medium.com/@palantir/windows-event-forwarding-for-network-defense-cb208d5ff86f)
* [iadgov/Event-Forwarding-Guidance - Configuration guidance for implementing collection of security relevant Windows Event Log events by using Windows Event Forwarding. iadgov](https://github.com/iadgov/Event-Forwarding-Guidance)
* Active directory
  * [shellster/DCSYNCMonitor - Monitors for DCSYNC and DCSHADOW attacks and create custom Windows Events for these events](https://github.com/shellster/DCSYNCMonitor)

FE

* [leizongmin/js-xss - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist](https://github.com/leizongmin/js-xss)

Sandbox analysis

* [phdphuc/mac-a-mal-cuckoo - This analyzer extends the open-source Cuckoo Sandbox (legacy) with functionality for analyzing macOS malware in macOS guest VM(s)](https://github.com/phdphuc/mac-a-mal-cuckoo)

Uncategorized

* [phishai/phish-protect - Chrome extension to alert and possibly block IDN/Unicode websites and zero-day phishing websites using AI and Computer Vision](https://github.com/phishai/phish-protect)
* [MiSecurity/x-patrol - Github 泄露扫描系统](https://github.com/MiSecurity/x-patrol)
* [Cyb3rWard0g/HELK - The Hunting ELK](https://github.com/Cyb3rWard0g/HELK)
   * [toolsmith #131 - The HELK vs APTSimulator - Part 1](https://holisticinfosec.blogspot.com.au/2018/02/toolsmith-131-helk-vs-aptsimulator-part.html)
* [endgameinc/ClrGuard - a proof of concept project to explore instrumenting the Common Language Runtime (CLR) for security purposes - CLR动态加载检测](https://github.com/endgameinc/ClrGuard)

## Attack Simulation

Tools

* [redhuntlabs/RedHunt-OS - Virtual Machine for Adversary Emulation and Threat Hunting](https://github.com/redhuntlabs/RedHunt-OS)
* [vysec/CACTUSTORCH - Payload Generation for Adversary Simulations](https://github.com/vysec/CACTUSTORCH)
* [NextronSystems/APTSimulator - A toolset to make a system look as if it was the victim of an APT attack](https://github.com/NextronSystems/APTSimulator)
* [redcanaryco/atomic-red-team - Small and highly portable detection tests mapped to the Mitre ATT&CK Framework](https://github.com/redcanaryco/atomic-red-team)
* [mitre/caldera - An automated adversary emulation system](https://github.com/mitre/caldera)
   * [INSTALL/SETUP MITRE CALDERA THE AUTOMATED CYBER ADVERSARY EMULATION SYSTEM](https://holdmybeersecurity.com/2018/01/13/install-setup-mitre-caldera-the-automated-cyber-adversary-emulation-system/)
* [uber-common/metta - An information security preparedness tool to do adversarial simulation](https://github.com/uber-common/metta)
* [endgameinc/RTA - RTA provides a framework of scripts designed to allow blue teams to test their detection capabilities against malicious tradecraft, modeled after MITRE ATT&CK.](https://github.com/endgameinc/RTA)
* [TryCatchHCF/DumpsterFire - DumpsterFire Toolset - "Security Incidents In A Box!"](https://github.com/TryCatchHCF/DumpsterFire)
* [jymcheong/AutoTTP - Automated Tactics Techniques & Procedures](https://github.com/jymcheong/AutoTTP)
* [Cyb3rWard0g/Invoke-ATTACKAPI - A PowerShell script to interact with the MITRE ATT&CK Framework via its own API](https://github.com/Cyb3rWard0g/Invoke-ATTACKAPI)

Dataset

* [daveherrald/botsv1 - Splunk Boss of the SOC v1 data set](https://github.com/daveherrald/botsv1)

## Books

* [OWASP - Automated Threat Handbook - Web Applications](https://www.owasp.org/images/3/33/Automated-threat-handbook.pdf)

## Tutorials

* [Tales of a Threat Hunter 2 - Following the trace of WMI Backdoors & other nastiness](https://www.eideon.com/2018-03-02-THL03-WMIBackdoors/)
* [awslabs/aws-security-automation - Collection of scripts and resources for DevSecOps and Automated Incident Response Security](https://github.com/awslabs/aws-security-automation)



