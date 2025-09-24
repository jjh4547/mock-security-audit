# mock-security-audit
Security audit simulation assessing access controls, risk management, and compliance gaps.
# Botium Toys Security Audit Project

## Project Overview
This project documents a security audit performed for **Botium Toys**, a growing toy retailer. The audit identifies risks, evaluates current security controls, and assesses compliance with industry standards and regulations.  

The purpose of this audit is to strengthen Botium Toys’ security posture, protect customer data, and ensure adherence to compliance frameworks such as **PCI DSS, GDPR, and SOC**.

---

## Scope and Goals

### Scope
- Conduct an internal security audit of Botium Toys’ systems, processes, and assets.  
- Assess both **digital** (customer data, payment systems, network infrastructure) and **physical** (office, storefront, warehouse) security measures.  
- Identify potential risks and provide actionable recommendations to reduce vulnerabilities.

### Goals
- Protect customer data (PII, SPII, and payment card data).  
- Safeguard digital and physical assets.  
- Ensure compliance with relevant regulatory frameworks (PCI DSS, GDPR, SOC).  
- Provide recommendations to improve Botium Toys’ security posture.

---

## Risk Assessment

| Threat | Risk Level | Impact if Not Addressed |
|--------|------------|--------------------------|
| Insider threats | High | Employees could access or misuse sensitive customer data |
| Unpatched software vulnerabilities | High | Increases the likelihood of malware or ransomware attacks |
| Weak password practices | Medium | Increases the risk of unauthorized access |
| Lack of disaster recovery planning | High | Business operations could be severely disrupted in the event of a breach or system failure |
| Physical break-ins | Medium | Could result in stolen assets or compromised customer information |

---

## Control Categories
The audit examined the following types of controls:

- **Preventive controls** – Stop security incidents before they occur (e.g., firewalls, password policies, encryption).  
- **Detective controls** – Identify when a security event occurs (e.g., IDS, CCTV).  
- **Corrective controls** – Respond to and recover from incidents (e.g., backups, disaster recovery plans).  
- **Compensating controls** – Alternative safeguards when primary controls are not feasible (e.g., manual monitoring of legacy systems).  

---

## Controls Assessment Checklist

| Control | In Place? |
|---------|-----------|
| Least Privilege | No |
| Disaster Recovery Plans | No |
| Password Policies | Yes |
| Separation of Duties | No |
| Firewall | Yes |
| Intrusion Detection System (IDS) | No |
| Backups | No |
| Antivirus Software | Yes |
| Manual Monitoring (legacy systems) | Yes |
| Encryption | No |
| Password Management System | No |
| Locks (offices, storefront, warehouse) | Yes |
| CCTV Surveillance | No |
| Fire Detection/Prevention | Yes |

---

## Compliance Checklist

### PCI DSS
| Best Practice | In Place? |
|---------------|-----------|
| Only authorized users have access to customers’ credit card information | Yes |
| Credit card information stored/processed in a secure environment | No |
| Data encryption at transaction touchpoints | No |
| Secure password management policies adopted | Yes |

### GDPR
| Best Practice | In Place? |
|---------------|-----------|
| E.U. customers’ data is kept private/secured | No |
| Plan in place to notify E.U. customers within 72 hours of a breach | No |
| Data properly classified and inventoried | No |
| Privacy policies, procedures, and documentation enforced | No |

### SOC 1 & SOC 2
| Best Practice | In Place? |
|---------------|-----------|
| User access policies established | No |
| Sensitive data (PII/SPII) is confidential/private | No |
| Data integrity validated (complete, accurate, consistent) | No |
| Data available to authorized users | Yes |

---

## Recommendations
Based on the audit findings, Botium Toys should prioritize the following:

1. **Implement a Disaster Recovery Plan (High Priority)**  
   Ensures business continuity during outages, breaches, or disasters.  

2. **Adopt Data Encryption (High Priority)**  
   Protects sensitive customer and payment information from interception and misuse.  

3. **Deploy an Intrusion Detection System (Medium-High Priority)**  
   Enhances ability to detect and respond to cyberattacks in real time.  

4. **Enforce GDPR Compliance (High Priority for E.U. customers)**  
   Create breach notification procedures and data privacy policies.  

5. **Introduce Separation of Duties (Medium Priority)**  
   Reduces risk of insider threats by limiting excessive access privileges.  

6. **Upgrade Physical Security (Medium Priority)**  
   Add CCTV monitoring to safeguard warehouse and office environments.  

---

## Summary
The Botium Toys security audit identified **critical gaps** in encryption, recovery planning, and compliance with **PCI DSS, GDPR, and SOC frameworks**. Implementing the above recommendations will help the company:  

- Protect customer data.  
- Strengthen resilience against cyber and physical threats.  
- Achieve compliance with regulatory requirements.  
- Improve overall trust and brand reputation.  

---

## How to Use This Repo
This repository is part of my **cybersecurity portfolio**. You can explore it to see examples of my work in:  

- **Risk Assessments** – Identifying and prioritizing threats.  
- **Controls Assessments** – Evaluating technical, administrative, and physical safeguards.  
- **Compliance Mapping** – Checking adherence to PCI DSS, GDPR, and SOC standards.  
- **Recommendations** – Actionable security improvements for real-world organizations.  

Clone or download the repo to review the audit documents, or view directly in GitHub for a structured overview of my cybersecurity projects.
