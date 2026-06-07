# Hi, I'm Joseph Reanzares

IT support professional in training, based in Auckland, NZ. I build home labs to develop real hands-on skills across Windows Server, networking, security, and automation — the kind of experience you don't get from certifications alone.

---

## Featured projects

### Windows Server Enterprise Lab — Contoso
> A fully functional enterprise network built on Microsoft Hyper-V, simulating a real-world IT environment for a fictional company called Contoso.

**What's running:**
- 2 x Windows Server 2025 domain controllers with verified AD replication
- DNS, DHCP, Group Policy (6 GPOs), OU structure, 8 domain users
- File server (FS01) — SMB shares, DFS namespace, disk quotas, NTFS permissions
- IIS intranet web server (WEB01) — custom site, SSL certificate, DNS A record
- WSUS patch management server — GPO-targeted client updates
- pfSense CE firewall — NAT routing, stateful inspection, custom rules
- PowerShell automation — bulk user creation, AD reporting, home folder provisioning
- Windows Server Backup — system state and full volume backup with DR runbooks

**Full documentation with screenshots for every component:**
[hallowseph.github.io/windows-server-lab](https://hallowseph.github.io/windows-server-lab/) · [github.com/hallowseph/windows-server-lab](https://github.com/hallowseph/windows-server-lab)

---

### Vulnerability Assessment Lab
> A home lab simulating a real-world vulnerability assessment against intentionally vulnerable targets using industry-standard tools.

**What was used:**
- Kali Linux as the attacker machine
- Nmap for network discovery and port scanning
- Nikto for web server vulnerability scanning
- Metasploit for exploitation and verification

[github.com/hallowseph/vuln-assessment-lab](https://github.com/hallowseph/vuln-assessment-lab)

---

## Skills

| Category | Tools & Technologies |
|---|---|
| Operating systems | Windows Server 2025, Windows 11, Kali Linux |
| Directory services | Active Directory, DNS, DHCP, Group Policy |
| Networking | TCP/IP, pfSense, VLANs, NAT, firewall rules |
| File services | SMB, DFS, NTFS permissions, FSRM |
| Web services | IIS, SSL/TLS, HTTP/HTTPS |
| Patch management | WSUS, GPO-based client targeting |
| Scripting | PowerShell — user provisioning, reporting, automation |
| Security | Nmap, Nikto, Metasploit, vulnerability assessment |
| Backup & recovery | Windows Server Backup, system state, DR planning |
| Virtualisation | Microsoft Hyper-V |
| Documentation | Technical runbooks, step-by-step lab guides |

---

## Currently building

- osTicket helpdesk lab — simulating L1/L2 ticket workflows integrated with Active Directory
- Azure AD Connect — hybrid identity and cloud integration

---

## Contact

📧 xxg8089@autuni.ac.nz
