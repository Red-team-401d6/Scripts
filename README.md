# Script Repo
This repository contains all scripts and commands used to  gather information and test vulnerabilities during Red Team Exercise

## Tools & Technologies
| Name     | Description | Link |
| -------- | -------------- | ------- |
| Nmap | Nmap is a network exploration tool used to discover hosts and services on a network and analyze their vulnerabilities. | <img height="38" src="https://nmap.org/images/nmap-logo-256x256.png"></a>&nbsp;&nbsp; |<a href="https://nmap.org/" target=" _blank" rel="noopenernoreferrer"> |
| Wireshark | Wireshark is a network protocol analyzer that captures and examines network traffic in real-time. | <img height="38" src="https://www.wireshark.org/assets/img/sflogo-front.png"></a>&nbsp;&nbsp; |<a href="https://www.wireshark.org/" target=" _blank" rel="noopenernoreferrer" |
| Metasploit | Metasploit is a penetration testing framework that provides a collection of exploits, payloads, and auxiliary tools to test vulnerabilities.| <img height="38" src="https://www.kali.org/tools/metasploit-framework/images/metasploit-framework-logo.svg"></a>&nbsp;&nbsp; |<a href="https://www.metasploit.com/" target=" _blank" rel="noopenernoreferrer"> |

## Nmap
* Description TEMPLATE!!!!
```{code Language}
command/script here
```

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
