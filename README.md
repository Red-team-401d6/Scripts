# Script Repo
This repository contains all scripts and commands used to  gather information and test vulnerabilities during Red Team Exercise

## Tools & Technologies
| Name     | Description | Link |
| -------- | -------------- | ------- |
| Nmap | Nmap is a network exploration tool used to discover hosts and services on a network and analyze their vulnerabilities. | <a href="https://nmap.org/" target=" _blank" rel="noopenernoreferrer"><img width="50" height="50"  src="https://nmap.org/images/nmap-logo-256x256.png"></a>&nbsp;&nbsp; |
| Wireshark | Wireshark is a network protocol analyzer that captures and examines network traffic in real-time. | <a href="https://www.wireshark.org/" target=" _blank" rel="noopenernoreferrer"><img width="50" height="50"  src="https://www.wireshark.org/assets/img/sflogo-front.png"></a>&nbsp;&nbsp; |
| Metasploit | Metasploit is a penetration testing framework that provides a collection of exploits, payloads, and auxiliary tools to test vulnerabilities.| <a href="https://www.metasploit.com/" target=" _blank" rel="noopenernoreferrer"><img width="50" height="50"  src="https://www.kali.org/tools/metasploit-framework/images/metasploit-framework-logo.svg"></a>&nbsp;&nbsp; |

## Nmap
---
* Description TEMPLATE!!!!
```{code Language}
command/script here
```
---

* This command was performed on the Network IP address to find all hosts on the network.
```{bash}
sudo nmap <IP/CIDR>
```

* This command performs a TCP SYN scan (-sS) and service version detection (-sV) on the specified IP address to find all open ports.
```{bash}
sudo nmap -sS -vS <IP>
```

* This command performs a comprehensive scan on the specified IP address using Nmap, including OS detection, version detection, script scanning, and traceroute.
```{bash}
sudo nmap -A -sS -vS <IP>
```

* This command encacts a General enumeration on an anonymous session, and provides information such as: Target Information, Enumerating Workgroup/Domain, Nbtstat Information, and a Session Check.
```{bash}
enum4linux -a <target>
```

* This comman is an OS discovery script for checking status and information of a target.
```{bash}
sudo nmap -p 445 --script smb-os-discovery <Target>
```

## Wireshark
* Description
```{code Language}
command/script here
```

## Metasploit
* Description
```{code Language}
command/script here
```
