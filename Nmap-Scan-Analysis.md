# Nmap Scan Analysis

## Target
- Target: Metasploitable2
- IP Address: 192.168.56.101
- Scanner: Kali Linux

## TCP Scan Findings

The Nmap scan identified several open TCP services on the target system:

| Port | Service |
|------|---------|
| 21 | FTP |
| 22 | SSH |
| 23 | Telnet |
| 80 | HTTP |
| 445 | SMB |
| 3306 | MySQL |
| 5432 | PostgreSQL |

## OS Detection

Nmap OS detection identified the target as a Linux system running a 2.6.x kernel. The detected kernel range was approximately 2.6.9–2.6.33.

## UDP Scan

A UDP scan was performed using:

`sudo nmap -sU --top-ports 20 192.168.56.101`

The scan was used to identify commonly used UDP services on the target.

## Security Observations

The presence of multiple network services increases the attack surface of the system. Services such as Telnet and FTP should be reviewed carefully because insecure configurations or weak authentication can expose the system to security risks.

The identified services should be checked for unnecessary exposure,  outdated software, weak credentials, and known vulnerabilities.

## Conclusion

The Nmap reconnaissance identified multiple open services and provided information about the target operating system. These findings can be used as the basis for further vulnerability assessment using OpenVAS/Greenbone.
