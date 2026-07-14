# 📘 Common Nmap Commands

| Command |                     Purpose                                              |
|---------|---------  |
| `nmap <IP>`         | Scan the default ports of a target.                          |
| `nmap -sn <IP>`     | Discover active hosts without scanning ports.                |
| `nmap -sV <IP>`     | Detect service versions.                                     |
| `sudo nmap -O <IP>` | Detect the operating system.                                 |
| `nmap -A <IP>`      | Perform aggressive scan (OS, services, scripts, traceroute). |
| `nmap -F <IP>`      | Perform a fast scan.                                         |
| `nmap -p 80 <IP>`   | Scan a specific port.                                        |
| `nmap -p- <IP>`     | Scan all TCP ports.                                          |
| `nmap -Pn <IP>`     | Skip host discovery and scan the target directly.            |
| `nmap --version`    | Display the installed Nmap version.                          |

---

## Note

Practice these commands only on systems and networks that you own or have permission to test.
