# Hi, I'm Joseph Reanzares
IT support professional in training, based in Auckland, NZ. I'm a final-year Bachelor of Computer and Information Sciences student at AUT (graduating June 2026), majoring in Software Development with a minor in Networks and Cybersecurity. I build home labs to develop real hands-on skills across Windows Server, networking, security, and automation — the kind of experience you don't get from certifications alone.

---

## Education & certifications

**Bachelor of Computer and Information Sciences** · Auckland University of Technology · 2022 – Jun 2026
Major in Software Development · Minor in Networks and Cybersecurity

**CCNA: Enterprise Networking, Security, and Automation** · Cisco Networking Academy · Oct 2024
OSPFv2 · Network Security · IPv4 ACLs · NAT · WAN Scalability · QoS · SD-WAN

**Certificate in Science and Technology** · Auckland University of Technology · 2021 – 2022

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

### osTicket Helpdesk Lab — Contoso IT Support
> A hands-on helpdesk lab deployed on top of the Contoso AD environment, simulating real-world L1 and L2 IT support workflows using osTicket on Ubuntu Server.

**What's running:**
- Ubuntu Server 26.04 LTS VM on Hyper-V — LAMP stack (Apache, MySQL, PHP 8.5)
- osTicket v1.18.2 — departments, SLA plans, help topics, agents, and teams configured
- 3 departments with L1/L2 separation — IT Support and Systems Administration
- 4 SLA plans — Sev-1 Critical (1hr/24/7) through Sev-3 Normal (8hr/business hours)
- 7 help topics with automatic department routing and SLA assignment
- 4 end-to-end ticket scenarios — password reset, hardware issue, VPN access, system outage
- LDAP plugin installed and configured for AD integration — PHP 8.5 compatibility findings documented
- Full troubleshooting log — 6 real issues documented with root cause and resolution

**Full documentation with screenshots for every component:**
[hallowseph.github.io/osticket-helpdesk-lab](https://hallowseph.github.io/osticket-helpdesk-lab/) · [github.com/hallowseph/osticket-helpdesk-lab](https://github.com/hallowseph/osticket-helpdesk-lab)

---

### Vulnerability Assessment Lab
> A structured vulnerability assessment against intentionally vulnerable targets using industry-standard tools.

**What was used:**
- Kali Linux as the attacker machine
- Nmap for network discovery and port scanning
- Nikto for web server vulnerability scanning
- Metasploit for exploitation and verification
- Documented four critical vulnerabilities with a full mitigation report

[github.com/hallowseph/vuln-assessment-lab](https://github.com/hallowseph/vuln-assessment-lab)

---

## Skills

| Category | Tools & Technologies |
|---|---|
| Operating systems | Windows Server 2025, Ubuntu Server, Windows 11, Kali Linux |
| Directory services | Active Directory, DNS, DHCP, Group Policy, LDAP |
| Helpdesk & ITSM | osTicket, SLA management, L1/L2 ticket workflows, incident management |
| Networking | TCP/IP, pfSense, VLANs, NAT, OSPFv2, firewall rules |
| Linux administration | Ubuntu Server, Apache, MySQL, PHP, systemctl, SSH |
| File services | SMB, DFS, NTFS permissions, FSRM |
| Web services | IIS, Apache, SSL/TLS, HTTP/HTTPS |
| Patch management | WSUS, GPO-based client targeting |
| Scripting | PowerShell — user provisioning, reporting, automation |
| Security | Nmap, Nikto, Metasploit, vulnerability assessment |
| Backup & recovery | Windows Server Backup, system state, DR planning |
| Virtualisation | Microsoft Hyper-V, VMware |
| Development | Java, PHP, JavaScript, SQL, Node.js, HTML/CSS |
| Documentation | Technical runbooks, step-by-step lab guides, troubleshooting logs |

---

## Currently building
- Azure AD Connect — hybrid identity and cloud integration

---

## Contact
📧 josephreanzares12@gmail.com
