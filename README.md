# Active Directory Home Lab (Cybersecurity Lab)

## Overview

This project simulates a small enterprise network using Windows Server Active Directory inside a virtualized lab environment.
The purpose of this lab is to understand how corporate networks function and how attackers target identity infrastructure.

The lab will later be used to practice detection, monitoring, and Active Directory attacks.

---

## Lab Goals

* Build a Domain Controller
* Configure DNS & Static IP addressing
* Join client machines to the domain
* Implement Group Policy
* Simulate attacks
* Detect malicious behavior using logs

---

## Network Architecture

```
Domain Controller: 192.168.56.10
Client Machine:    (to be added)
Attacker Machine:  (to be added)
Network: Host-Only Internal Lab Network
Domain: teekay.local
```

---

## Technologies Used

* Windows Server 2025
* Active Directory Domain Services
* DNS Server
* VirtualBox
* Windows Client OS (Coming next)
* Kali Linux (Later phase)

---

## Why This Matters

In enterprise environments, Active Directory controls authentication, permissions, and access to resources.
Compromising Active Directory effectively compromises the entire organization.

This lab replicates a real corporate network to understand both administration and security monitoring perspectives.
