# SECURITY.md — Nous-OS Security Policy

---

## Core Security Philosophy

Nous-OS is built on strong privacy and data sovereignty principles.  
User safety, data protection, and full local control are fundamental design priorities.

---

## Key Security Features

- 🔒 Full disk encryption (LUKS, system-level)
- 🔒 Encrypted local journaling files (YAML/JSON with optional fscrypt integration)
- 🔒 No cloud storage or external data transmission by default
- 🔒 No telemetry, no external tracking, no background analytics
- 🔒 All AI models run locally without external API calls
- 🔒 Offline-first architecture minimizes attack surface

---

## Threat Model

Nous-OS is designed for:

- Protection against unauthorized local access
- Protection against third-party data harvesting
- Protection from cloud-based surveillance models
- Protection against non-consensual data export

Nous-OS is **not designed for:**

- Military-grade national security levels
- Active defense against highly targeted zero-day exploits
- Adversarial state-level attacks

---

## Vulnerability Disclosure

As Nous-OS is open-source, responsible disclosure is encouraged:

- Please open security-related issues via GitHub Issues.
- Private disclosures can be initiated via secure communication channels (to be provided as community grows).

---

## Security Roadmap (Early Phase)

- Full system encryption defaults (LUKS-2 standard)
- User-level journaling encryption (per-folder or per-file fscrypt integration)
- Secure key management (user-controlled passphrases)
- Optional secure export & backup functionality (encrypted archives)
- Regular peer code reviews and open audit culture

---

## Guiding Principle

*Security is not a feature — it is a responsibility.*

Nous-OS aims to give users full ownership of both their personal data — and their personal therapeutic journey.
