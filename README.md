# M365 Email Security and Deliverability Configuration

Enterprise documentation for securing a Microsoft 365 tenant’s email infrastructure — covering authentication protocols, threat protection, identity hardening, and monitoring.

## Contents

| Document | Description |
|---|---|
| [Email Security Configuration](docs/Email-Security-Configuration.md) | Full configuration guide following 8-section enterprise documentation standard |
| [Email Security (PDF)](Email-Security-Configuration.pdf) | Downloadable PDF version for client delivery |

## Key Highlights

- **Email Authentication**: SPF, DKIM, and phased DMARC enforcement to prevent domain spoofing
- **9 Defender for Office 365 threat policies** including Safe Links, Safe Attachments, Anti-Phishing, and Anti-Malware
- **Plan 1 vs Plan 2 comparison** for Microsoft Defender for Office 365 licensing decisions
- **Identity hardening** via Entra ID Conditional Access — MFA enforcement and legacy authentication blocking
- **Centralised logging and alerting** with Purview audit logs, mailbox auditing, SIEM integration, and security alerts
- **User awareness** — Attack Simulation Training and incident response procedures

## Documentation Standard

This project follows an 8-section enterprise documentation template:

1. Name
2. Purpose
3. Scope
4. Configuration Details
5. Dependencies
6. Impact
7. Risks / Considerations
8. Notes

## Author

Prepared by **Olu Adelokiki** — [LinkedIn](https://www.linkedin.com/in/olukunmi-adelokiki)

---

*Generated: 2026-03-22*
