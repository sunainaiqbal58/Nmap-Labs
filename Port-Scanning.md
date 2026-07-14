# 🔍 Port Scanning

## Overview

Port scanning is used to identify open ports on a target system. Open ports often indicate running services that can be analyzed during network assessments.

---

## Scan Default Ports

```bash
nmap 192.168.1.10
```
Scans the most common ports on the target.

---

## Scan Specific Ports

```bash
nmap -p 22,80,443 192.168.1.10
```
Scans only the selected ports.

---

## Fast Scan

```bash
nmap -F 192.168.1.10
```
Performs a faster scan by checking fewer common ports.

---

## Scan All Ports

```bash
nmap -p- 192.168.1.10
```

Scans all 65535 TCP ports.

---
## Summary

Port scanning helps identify accessible services and is an essential step in network analysis.
