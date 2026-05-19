# Enterprise Homelab Infrastructure

## Overview
Built a multi-VM enterprise infrastructure lab using:

- Windows Server 2022
- Active Directory Domain Services (AD DS)
- DNS Server
- Windows 10 Client
- Ubuntu Server
- Kali Linux
- SSH
- Bridged Networking
- VirtualBox
- UTM

---

## Infrastructure

| Machine | Role | IP Address |
|---|---|---|
| DC01 | Domain Controller + DNS | 192.168.1.10 |
| CLIENT101 | Domain Client | Dynamic DHCP |
| Ubuntu Server | Linux Server | 192.168.1.x |
| Kali Linux | Security Testing VM | 192.168.1.x |

---

## What I Configured

- Installed and configured Active Directory
- Promoted DC01 to Domain Controller
- Configured DNS
- Joined Windows client to domain
- Enabled VM communication with bridged networking
- Configured SSH on Ubuntu Server
- Performed connectivity tests using ping
- Performed network discovery using Nmap
- Troubleshooted firewall and DNS issues

---

## Skills Demonstrated

- System Administration
- Active Directory
- Networking
- DNS
- Virtualization
- Linux Administration
- Troubleshooting
- Cybersecurity Fundamentals

---

## Screenshots

Screenshots available in `/screenshots`
