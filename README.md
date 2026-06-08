# Hi, I'm Joseph Reanzares

IT support professional in training, based in Auckland, NZ. I'm a final-year Bachelor of Computer and Information Sciences student at AUT (graduating June 2026), majoring in Software Development with a minor in Networks and Cybersecurity. I build home labs to develop real hands-on skills across Windows Server, networking, security, and automation — the kind of experience you don't get from certifications alone.

---

## Education & certifications

**Bachelor of Computer and Information Sciences** · Auckland University of Technology · 2022 – Jun 2026
Major in Software Development · Minor in Networks and Cybersecurity

**CCNA: Enterprise Networking, Security, and Automation** · Cisco Networking Academy · Oct 2024
OSPFv2 · Network Security · IPv4 ACLs · NAT · WAN Scalability · QoS · SD-WAN

**Certificate in Science and Technology** · Auckland University of Technology · 2021 – 2022

🇳🇿 New Zealand Permanent Resident

---

## Featured projects

### Windows Server Enterprise Lab — Contoso
> A fully functional enterprise network built on Microsoft Hyper-V, simulating a real-world IT environment for a fictional company called Contoso.

**What's running:**
- 2 x Windows Server 2025 domain controllers with verified AD replication
- DNS, DHCP, Group Policy (6 GPOs), OU structure, 8 domain users provisioned via PowerShell
- File server (FS01) — SMB shares, DFS namespace, disk quotas, NTFS permissions
- IIS intranet web server (WEB01) — custom site, SSL certificate, DNS A record
- WSUS patch management server — GPO-targeted client updates
- pfSense CE firewall — NAT routing, stateful inspection, custom rules
- PowerShell automation — bulk user creation, AD reporting, home folder provisioning
- Windows Server Backup — system state and full volume backup with DR runbooks

**Full documentation with screenshots for every component:**
[hallowseph.github.io/windows-server-lab](https://hallowseph.github.io/windows-server-lab/) · [github.com/hallowseph/windows-server-lab](https://github.com/hallowseph/windows-server-lab)

---

### osTicket Helpdesk Lab — Contoso IT Support
> A hands-on helpdesk lab built on top of the Contoso AD environment, simulating real-world L1 and L2 IT support workflows using osTicket on Ubuntu Server.

**What's running:**
- Ubuntu Server 26.04 LTS VM on Hyper-V — LAMP stack (Apache 2.4.66, MySQL, PHP 8.5.4)
- osTicket v1.18.2 — departments, SLA plans, help topics, agents, and teams configured
- 3 departments — Support, IT Support, Systems Administration
- 4 SLA plans — Sev-1 Critical (1hr/24-7) through Sev-3 Normal (8hr/business hours)
- 7 help topics with automatic department routing and SLA assignment
- 4 end-to-end ticket scenarios — password reset, hardware issue, VPN access, system outage (resolved in 13 min)
- L1 agent (Sarah Miller) and L2 agent (James Carter) across two support teams
- LDAP integration attempted — PHP 8.5 compatibility findings fully documented

**Full documentation with screenshots for every component:**
[hallowseph.github.io/osticket-helpdesk-lab](https://hallowseph.github.io/osticket-helpdesk-lab/) · [github.com/hallowseph/osticket-helpdesk-lab](https://github.com/hallowseph/osticket-helpdesk-lab)

---

### Vulnerability Assessment Lab
> A full vulnerability assessment across MySQL and HTTP services, using Kali Linux as the attacker machine against intentionally vulnerable targets in an isolated VirtualBox environment.

**Targets assessed:**
- Windows Server 2016 — MySQL on port 3306 (Nmap, Metasploit, Hydra)
- Metasploitable 2 — Apache HTTP on port 80 (Nikto, Dirb, SQLmap, Burp Suite)

**Each assessment covers:**
- Reconnaissance → vulnerabilities found → exploitation → remediation
- Full documentation with CVE references and OWASP links

**Tools used:** Nmap · Metasploit · Hydra · Nikto · Dirb · SQLmap · Burp Suite · Wireshark

[github.com/hallowseph/vuln-assessment-lab](https://github.com/hallowseph/vuln-assessment-lab)

---

## Skills

| Category | Tools & Technologies |
|---|---|
| Operating systems | Windows Server 2025, Ubuntu Server 26.04, Windows 11, Kali Linux |
| Directory services | Active Directory, DNS, DHCP, Group Policy, LDAP |
| Helpdesk & ITSM | osTicket, SLA management, L1/L2 ticket workflows, incident management |
| Networking | TCP/IP, pfSense, VLANs, NAT, OSPFv2, firewall rules |
| Linux administration | Ubuntu Server, Apache, MySQL, PHP, systemctl, SSH |
| File services | SMB, DFS, NTFS permissions, FSRM |
| Web services | IIS, Apache, SSL/TLS, HTTP/HTTPS |
| Patch management | WSUS, GPO-based client targeting |
| Scripting | PowerShell — user provisioning, reporting, automation |
| Security | Nmap, Nikto, Metasploit, Hydra, Dirb, SQLmap, Burp Suite, Wireshark |
| Backup & recovery | Windows Server Backup, system state, DR planning |
| Virtualisation | Microsoft Hyper-V, VirtualBox |
| Development | Java, PHP, JavaScript, SQL, Node.js, HTML/CSS |
| Documentation | Technical runbooks, step-by-step lab guides, troubleshooting logs |

---

## Contact

📧 josephreanzares12@gmail.com
