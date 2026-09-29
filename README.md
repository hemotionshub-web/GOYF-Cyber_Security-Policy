# OLAZ Foundation: Cybersecurity Policy Framework

**Document Version:** 1.2  
**Effective Date:** September 29, 2026  
**Applicability:** All Global Staff, Volunteers, Field Contractors, and Third-Party Partners.

---

## 1. Document Objective & Scope

The purpose of this policy framework is to establish strict security standards to protect the **OLAZ Foundation's** digital infrastructure, donor records, and sensitive beneficiary data. 

This policy applies universally to all information technology systems, field networks, and cloud applications owned, operated, or utilized by or on behalf of the OLAZ Foundation.

---

## 2. Core Policies

### 2.1 Access Control & Identity Management
* **Multi-Factor Authentication (MFA):** MFA is strictly mandatory across all core cloud platforms, including Google Workspace, Microsoft 365, donor databases, and financial portals.
* **Password Complexity:** All user accounts must enforce a minimum length of **12 characters**, containing uppercase letters, lowercase letters, numbers, and special symbols. Passwords must not contain easily guessable organizational terms.
* **Account Revocation Rule:** Upon employee separation or volunteer offboarding, network access and cloud software permissions must be revoked within **2 hours** of termination.

### 2.2 Device Security & Remote Field Operations
* **Full Disk Encryption (FDE):** All organizational laptops and tablets must utilize native hardware encryption (e.g., BitLocker or FileVault) using **AES-256 standards** to protect offline data if a device is stolen.
* **Public Network Restrictions:** Staff working remotely or in field deployment areas are forbidden from connecting to open, unencrypted public Wi-Fi networks unless an **Enterprise Virtual Private Network (VPN)** tunnel is fully initialized first.
* **Mobile Patch Management:** Mobile devices running organization-linked applications must have automatic security updates enabled. Devices running unsupported or rooted operating systems are blocked from accessing internal resources.

### 2.3 Beneficiary Privacy & Data Handling
* **Data Minimization:** The foundation will only collect Personally Identifiable Information (PII) absolutely necessary for grant fulfillment, medical outreach, or case tracking. 
* **Data Disposal Lifecycle:** Sensitive PII regarding program beneficiaries must be completely and securely purged from active production servers exactly **12 months** after the official closing date of a specific grant cycle.
* **Access Isolation:** Beneficiary case notes must be compartmentalized; access is restricted exclusively to authorized field caseworkers directly assigned to the program.

### 2.4 Financial Fraud Safeguards
* **Dual-Channel Verification:** Prior to modifying any existing vendor banking accounts, donor routing information, or executing any outbound financial disbursement exceeding **$500 USD** (or local currency equivalent), a secondary validation step must be completed via an out-of-band communication channel (e.g., a phone call to a pre-verified contact number).
* **Phishing Awareness Training:** All personnel, including long-term volunteers, must complete an interactive phishing and social engineering defense module during initial onboarding.

---

## 3. Incident Response Matrix

In the event of a suspected breach, data leak, or physical loss of an authorized device, personnel must immediately activate the following sequential response protocol:

| Phase | Action Item | Target Window | Responsible Party |
| :--- | :--- | :--- | :--- |
| **1. Identification** | Detect anomalous behavior, malware indicators, or report a missing hardware device. | Immediate | Discovering Party |
| **2. Reporting** | Flag the incident to the designated Security Administrator via the internal helpline or secure portal. | Within **1 hour** | Discovering Party |
| **3. Assessment & Isolation** | Isolate affected machines from local field networks; disable compromised cloud user tokens. | Within **4 hours** | Security / IT Lead |
| **4. Regulatory Notification** | Formulate and transmit breach notification letters to affected donors, beneficiaries, and privacy authorities if legal criteria are met. | Within **72 hours** | Executive Director / Legal Counsel |

---

## 4. Policy Compliance and Enforcement

Non-compliance with these safety guidelines exposes the GOY Foundation to severe financial penalties and reputational damage. Violations of this framework are subject to escalating disciplinary action up to immediate contract termination or legal prosecution.

