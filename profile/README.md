# 4 Assistant — remote desktop, support & administration software

<p align="center">
  <a href="https://4-assistant-remote-desktop.github.io/.github">
    <img src="https://img.shields.io/badge/Download_4_Assistant-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Download 4 Assistant">
  </a>
</p>

---

## What is 4 Assistant

**4 Assistant** is a professional remote access and support solution for desktop control, file transfer, chat, audio/video calls, remote deployment and diagnostics. It provides secure, auditable and flexible remote sessions for IT support teams, service centers and administrators who need dependable tools for managing user workstations and servers.

---

## Development background

Originally created as an in-house support tool for enterprise customers, 4 Assistant evolved into a full product offering centralized session management, role-based permissions, session recording for audits, multi-session handling and powerful automation via scripts and APIs. Version 4 introduced improved security, TLS 1.3, 2FA, and enterprise integrations with LDAP/AD and SSO.

---

## Key features

- 🔌 Full remote desktop control (mouse & keyboard) with multi-monitor support  
- 📁 Fast and reliable file transfer (Drag & Drop, SFTP integration)  
- 💬 Built-in chat, audio and video calls between operator and client  
- 🧰 Remote execution of scripts and installers (PowerShell, Bash)  
- 🛠 Diagnostic tools: process viewer, log browser, service control  
- ⏱ Session recording and operator action logs for compliance  
- 🗂 Role profiles (admin/operator/viewer) and fine-grained permissions

---

## Advanced capabilities

- 🔐 Two-factor authentication and hardware key support (YubiKey)  
- 🔁 Key rotation, one-time token links and expiring access URLs  
- ☁ Cloud and on-premises directory integration (LDAP, Active Directory, SAML)  
- 🧩 Public API / SDK for ticketing and CMDB integration  
- 📊 Centralized logging server and admin dashboard with reports  
- 🛰 NAT traversal and secure relay service for clients behind strict firewalls  
- ⚙ Kiosk and unattended access modes for servers and remote kiosks

---

## Security & privacy

Security is core: session encryption uses TLS 1.3, with optional end-to-end encryption. Secrets can be stored in HSM or Key-Vaults. Admins define session recording policies, enable watermarking, restrict clipboard/file transfer and enforce strict authentication policies. Relay nodes operate without access to decrypted payloads when E2E is enabled.

---

## Benefits

| Benefit | Description |
|--------|-------------|
| ✅ Reliability | Auto-reconnect, session multiplexing and relay fallback |
| 🔒 Security | 2FA, HSM integration, role-based access |
| ⚡ Performance | Optimized screen codecs and file transfer acceleration |
| 🧩 Flexibility | Clients for Windows/macOS/Linux/Android/iOS |
| 🧾 Compliance | Full audit trails, session export and retention policies |
| 🤝 Integrations | API, LDAP/AD, SSO, ticketing systems |

---

## System requirements

| Component | Minimum | Recommended |
|----------|---------:|-----------:|
| Client OS | Windows 7 / macOS 10.13 / Ubuntu 18.04 | Windows 10/11, macOS 12, Ubuntu 20.04+ |
| Server OS | Linux x86_64 or Windows Server 2016+ | Linux x86_64 (LTS) |
| CPU | 2 cores | 4+ cores (server) |
| RAM | 2 GB | 8+ GB (server) |
| Network | 1 Mbit/s | 10+ Mbit/s for video |
| Storage | 200 MB + logs | SSD for session recording |

---

## Quick start

1. Download the 4 Assistant installer and deploy client and server.  
2. Create admin accounts and configure roles in the admin console.  
3. Connect directory services (LDAP/AD) and enable SSO if required.  
4. Start a support session via an one-time link or direct connect.  
5. Use session recording and logs for audits and training.

---

## Integrations & use cases

- ✅ IT helpdesk & remote troubleshooting  
- ✅ Unattended server maintenance and remote lab access  
- ✅ Customer support for SaaS and enterprise software  
- ✅ Training and onboarding with recorded live sessions  
- ✅ Bulk deployment of updates and security patches

---

## FAQ

**Can I disable session recording?** Yes — admins control recording policies per user/group.  
**How secure is relay mode?** Relay uses TLS tunnels; with E2E enabled the relay cannot decrypt session contents.  
**Is there API access for ticket systems?** Yes — REST API and SDKs available for common ticketing platforms.

---

## SEO Keywords

4 assistant, 4 ассистент, remote desktop software, удалённый доступ, remote support tool, unattended access, удалённая поддержка, remote admin tool, it helpdesk software, secure remote desktop, rdp alternative, remote file transfer, session recording, remote diagnostics, ldap ad integration, 2fa remote access
