# Cybersecurity Internship – Task 2

## Overview
This repository contains the deliverables and evidence for **Cybersecurity Internship Task 2**.

The task focuses on network reconnaissance, vulnerability assessment, traffic analysis, firewall configuration, and documentation of security findings.

## Target
- **Target machine:** Metasploitable2
- **Target IP:** `192.168.56.101`

## Tools Used
- Nmap
- OpenVAS / Greenbone Vulnerability Manager
- GitHub
- Wireshark
- iptables / Firewall

## Task Deliverables

### 1. Network Scanning
Performed Nmap scans against the target to identify:
- Open TCP ports
- Open UDP ports
- Running services
- Service versions
- Operating system information

### 2. Vulnerability Assessment
A vulnerability assessment was performed using **OpenVAS / Greenbone**.

The report identified:
- **13 Critical**
- **9 High**
- **40 Medium**
- **6 Low**
- **90 Log**

These findings were reviewed to understand the exposed services and associated security risks.

### 3. Vulnerability Analysis
The identified vulnerabilities were analyzed based on:
- Affected service
- Severity
- Potential security impact
- Available evidence
- Possible mitigation/remediation

### 4. GitHub Security Analysis
The repository and relevant security configuration/evidence were reviewed and documented as part of the task.

### 5. Wireshark Traffic Analysis
Wireshark was used to capture and analyze network traffic.

The evidence demonstrates relevant packets/traffic observed during the testing process.

### 6. Firewall / iptables
Firewall rules were examined/configured using `iptables`.

Evidence of the firewall configuration and its effect is included in the repository screenshots.

## Evidence

Screenshots and supporting evidence are stored in the `screenshots/` directory.

Expected evidence files include:

```text
screenshots/
├── 01-whois.jpg
├── 02-...
├── ...
└── 15-...
```

> Keep the screenshot filenames consistent with the references used in this README so that GitHub displays them correctly.

## Security Note
All testing described in this repository was performed against the designated lab target, **Metasploitable2 (`192.168.56.101`)**, in an authorized learning environment.

## Demo
A short **5-minute demonstration** covers the main scans, vulnerability findings, traffic/firewall evidence, and the final documented results.

## Conclusion
This task demonstrates practical experience with:
- Network reconnaissance
- Port and service enumeration
- Vulnerability scanning
- Vulnerability analysis
- Packet/traffic analysis
- Firewall fundamentals
- Security documentation and evidence collection
