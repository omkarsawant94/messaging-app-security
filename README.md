# Enhancing Security in Messaging Applications

> ⚠️ **Disclaimer:** All lab exercises were conducted on authorised platforms and test environments. Signal protocol analysis used a controlled test setup. APK analysis was performed on a publicly available messaging application for educational research purposes only.

## Overview

A comprehensive security framework for messaging applications covering end-to-end encryption, authentication, file & voice security, and privacy policy — validated through two hands-on labs including real Wireshark network capture and Android APK security analysis.

## Key Highlights

- 🔐 **Signal Protocol** — Live E2E encryption verification via Wireshark `.pcapng` traffic capture
- 📱 **Android APK Security Audit** — Deep-dive permission, service, receiver and provider analysis across 8 modules
- 📄 **8 Deliverables** — Full security lifecycle from architecture to user training
- 📊 **41 Architecture Diagrams** — Visual documentation of every security component

## Deliverables — 8 Documents

| # | Document | Focus |
|---|---|---|
| 1 | Security Architecture Document | High-level design, threat model, security layers |
| 2 | Encryption Integration Plan | E2E encryption, key management, Signal protocol |
| 3 | Authentication & Authorization Guide | MFA, RBAC, biometric auth, session lifecycle |
| 4 | File & Voice Security Documentation | Secure file transfer, SRTP, DTLS voice encryption |
| 5 | Secure Communication Configuration | TLS, certificate validation, perfect forward secrecy |
| 6 | Privacy & Data Retention Policy | Privacy-by-design, data classification, GDPR alignment |
| 7 | Monitoring & Incident Response Plan | SIEM, threat detection, incident handling |
| 8 | User Training Materials | Security awareness, secure workflows, threat recognition |

## Labs

### Lab 1 — Signal Protocol Encryption Verification
- **89 screenshots** documenting end-to-end encrypted messaging verification
- **Live Wireshark `.pcapng` capture** — real network traffic proving encryption in transit
- Verified Signal protocol implementation including message encryption, key exchange, and traffic obfuscation

### Lab 2 — Android APK Security Analysis
- **200+ screenshots** across 8 modules and sub-categories
- Deep analysis of app permissions — Network, Storage, Camera, Microphone, Notifications, Foreground Services, Custom Permissions
- Component analysis — Services, Receivers, Providers
- Module-by-module security audit of messaging app behaviour

## Repository Structure

```
messaging-app-security/
│
├── Deliverables/
│   ├── PDFs/     (8 final PDF documents)
│   └── DOCs/     (8 editable Word versions)
│
├── Figures/
│   └── (41 architecture diagrams)
│
├── Labs/
│   ├── Lab-1-Signal-Encryption/
│   │   ├── Screenshots/   (89 screenshots)
│   │   ├── Wireshark/     (Lab1_Signal_Traffic.pcapng)
│   │   └── Reports/       (Lab report PDF + DOCX)
│   └── Lab-2-APK-Analysis/
│       ├── Services/
│       ├── Receivers/
│       ├── Providers/
│       ├── Permissions/
│       └── Modules/
│
├── Assets/
│   └── (App icons and visual assets)
│
└── README.md
```

## Key Security Concepts Demonstrated

- End-to-end encryption (Signal Protocol, Double Ratchet Algorithm)
- TLS 1.3, certificate pinning, perfect forward secrecy
- DTLS-SRTP for secure voice calls
- Android permission model and security analysis
- Biometric authentication and RBAC
- Privacy-by-design and GDPR data lifecycle
- SIEM-based monitoring and incident response

## Tech Stack

- Wireshark · Signal Protocol · Android APK Analysis
- TLS · DTLS-SRTP · SHA-256 · AES-256
- RBAC · MFA · Biometric Authentication
- SIEM · Privacy-by-Design · GDPR

## Author

**Omkar Sawant** — Cybersecurity Analyst & Ethical Hacker  
[LinkedIn](https://www.linkedin.com/in/omkarsawant94) · [GitHub](https://github.com/omkarsawant94)
