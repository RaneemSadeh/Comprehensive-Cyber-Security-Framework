# Comprehensive Cybersecurity Framework for Modern Business

This repository presents a complete cybersecurity framework designed for modern organizations. It uses **CyberBlast Crispy** as a case study to demonstrate a practical, holistic approach to managing security across physical, network, and human layers. It integrates international standards, policy development, incident recovery, and audit procedures.

---

## 🧱 Framework Structure

The framework includes four core components:

1. **Risk Assessment** — Based on ISO 31000
2. **Security Policies** — Covering access, encryption, passwords, and servers
3. **Disaster Recovery Plan (DRP)** — For resilience and continuity
4. **IT Security Audit** — To uncover weaknesses and improve compliance

---

## 1. Risk Assessment (ISO 31000-Based)

Follows the ISO 31000 cycle:

- **Risk Identification**: Finds threats to physical, network, and human assets
- **Risk Analysis**: Analyzes causes and likelihoods
- **Risk Evaluation**: Rates risk level by defined criteria
- **Risk Treatment**: Suggests controls to reduce risk
- **Monitoring & Review**: Tracks risk posture changes

### Key Risks Identified

| Asset           | Threat / Vulnerability                                           | Risk Level |
|-----------------|------------------------------------------------------------------|------------|
| Devices         | No anti-malware or host intrusion detection                      | Extreme    |
| Network         | Expired firewall, no DMZ, unsecured HR/Finance access            | Extreme    |
| Web Server      | OpenSSH version vulnerable to known exploits                     | Extreme    |
| Data Center     | No physical access control or environmental safeguards           | Extreme    |
| Company Policy  | Missing password and physical access policies                    | Extreme    |
| Employees       | Vulnerable to phishing and ransomware                            | Medium     |

---

## 2. Security Policies

Policies define controls for secure system use and access.

- **Remote Access Policy**: Rules for external connections
- **VPN Policy**: Secures remote access using encrypted tunnels
- **Server Security Policy**: Covers configuration and ownership of company servers
- **Password Protection Policy**: Mandates strong passwords and change cycles
- **Acceptable Encryption Policy**: Requires use of trusted algorithms (e.g., AES, RSA)

---

## 3. Disaster Recovery Plan (DRP)

Ensures business can recover IT services after a major disruption.

### DRP Components

- **Contingency Plans**:
  - Incident Response
  - Business Continuity
  - Data Backup & Recovery

- **RTO (Recovery Time Objective)**:
  - Maximum downtime acceptable per system

- **RPO (Recovery Point Objective)**:
  - Maximum data loss tolerance in time

- **Testing Requirement**:
  - Plan must be tested annually through simulations

---

## 4. IT Security Audit

Audits current systems to detect vulnerabilities and assess compliance.

### Audit Findings Summary

| Area              | Key Weaknesses                                                   |
|-------------------|------------------------------------------------------------------|
| Physical Security | Uncontrolled data center access, unsecured endpoint devices      |
| Network Security  | Missing network segmentation, expired firewalls                 |
| App Security      | Poor configuration, no encryption during data transmission       |
| Human Factor      | Low employee awareness of phishing, weak social engineering defense |

---

## 🎯 Stakeholder Roles

Security depends on coordinated roles across departments.

| Stakeholder        | Responsibility                                                   |
|--------------------|------------------------------------------------------------------|
| CEO                | Promote security culture, allocate resources                     |
| CISO               | Lead security program and incident response                      |
| IT Security Manager| Enforce policies, conduct audits                                 |
| Employees          | Follow security rules and report incidents                       |
| Risk Owners        | Collaborate with IT to manage specific risks                     |

---

## 📘 How to Use This Repository

This repository is a complete template for building or upgrading a cybersecurity program. You can:

- Use the included risk model to assess your environment
- Adopt or adapt the policy templates
- Build your own disaster recovery and continuity plans
- Conduct an internal audit using the listed control areas

All documents can be customized to suit different industries or company sizes.
