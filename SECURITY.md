# SECURITY.md — Security & Privacy Policy

---

## 🔐 Core Security Principles

- 100% local data storage — no cloud storage required or used.
- Full user data sovereignty — users fully own, control, and manage their data.
- Offline-first architecture — complete functionality without any network connection.
- Full-disk encryption (LUKS) strongly recommended for all installations.
- No telemetry, no analytics, no third-party data transmission.

---

## 🔍 Threat Model

Nous-OS is designed for:

- Private, personal self-reflection usage.
- Single-user or small-group private environments.
- Extremely high privacy requirements.

Nous-OS is not designed for:

- Multi-user corporate deployments.
- Shared network environments without appropriate safeguards.
- Clinical, medical, or diagnostic usage.

---

## 🔒 AI Model Security

- All AI models operate locally by default (LLaMA.cpp, DeepSeek, Whisper.cpp).
- External AI APIs (e.g. ChatGPT) are optional, fully transparent, and require explicit user consent.
- No AI models transmit personal data to any third party.
- No AI-driven automated decisions, clinical evaluations, or behavioral modifications are performed.

---

## ⚠ User Responsibility

- Users are fully responsible for their local device security, including:
  - Operating system updates.
  - Physical access control.
  - Backup management.
  - Malware protection.
- Nous-OS provides tools but cannot protect against physical device access or user misconfiguration.

---

## 🐞 Vulnerability Reporting

If you discover any security vulnerability or privacy issue:

- Please report it responsibly via GitHub Issues or contact the project maintainer directly.
- All reports will be handled confidentially and with highest priority.
- Security fixes will be provided for the latest stable branch only.

---

## 🔏 No Remote Access

- No remote administration interfaces exist.
- No background network activity occurs without user initiation.
- No automatic update mechanisms that bypass user control are implemented.

---

**Security is not a feature — it is a foundation.**  
Nous-OS empowers users to maintain full control over their data and system.

