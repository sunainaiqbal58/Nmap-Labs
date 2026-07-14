# 🔍 Host Discovery

## Overview

Host discovery is the first step in network scanning. It helps identify which devices are active on a network before performing detailed scans.

---
## Ping Scan
**Command**

```bash
nmap -sn 192.168.1.0/24
```
**Purpose**
Scans the network to identify live hosts without scanning ports.
---

## Scan a Single Host
**Command**
```bash
nmap -sn 192.168.1.10
```
**Purpose**
Checks whether a specific host is online.
---

## Why Host Discovery Matters

- Identifies active devices.
- Saves time by avoiding offline hosts.
- Helps prepare for further network scanning.

---

## Summary

Host discovery is commonly used before port scanning to determine which systems are available on a network.
