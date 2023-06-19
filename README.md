# Script Repo
This repository contains all scripts and commands used to  gather information and test vulnerabilities during Red Team Exercise

## Tools & Technologies
* Nmap
* Wireshark
* Metasploit

## Nmap
* Description
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

## WireShark
* Description
```{code Language}
command/script here
```

## Metasploit
* Description
```{code Language}
command/script here
```
