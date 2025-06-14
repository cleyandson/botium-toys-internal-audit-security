# Analysis and Internal Audit Security - Botium Toys
<p align="right">
  <a href="./README-PT.md">Ver em Português 🇧🇷</a>
</p>

Portfolio project developed as part of the <a href="https://www.coursera.org/google-certificates/cybersecurity-certificate">Google's Cybersecurity Course</a>

### About the Project
This project simulates a complete security audit for "Botium Toys", a fictional toy company. The objective is to transform a high-risk scenario (8/10 score) into a security fortress by applying real-world cybersecurity concepts.

---

### Project Summary
Botium Toys, a toy company with both a physical and online presence had a risk score of 8 out of 10 due to a lack of security controls and regulatory compliance. The scopre of this audit covered the company's entire security program, including its IT assets, internal network, and systems. The analysis focused on identifying existing controls, assessing compliance with standards like PCI DSS and GDPR, and proposing an action plan to mitigate the identified risks.

---

### ➤ The Challenge
Botium Toys, a growing company with e-commerce operations, faced a security risk rated as **"High"** due to a lack of essential controls. The mission was clear: to diagnose vulnerabilities, assess compliance with global standards, and create a strategic action plan to protect the company's assets and its customer data.

---

### ➤ My Approach and Analysis
To solve this challenge, i followed a structured, three-phase methodology:
1. **Control Diagnosis:** I conducted a complete assessment of the company's current security controls, comparing them against industry best patrices.
2. **Compliance Analysis:** I verified the company's adherence to **PCI DSS** regulations (for card payments) and **GDPR** (for European Union customer data).
3. **Action Plan:** I developed a set of prioritized recommendations to efficiently mitigate the most critical risks.

---

### ➤ Security Diagnosis: What Was Found

### Existing Controls ✅
The company already had basic security in place, which was a good starting point:
* Firewalls
* Antivirus
* Physical access controls (locks and CCTV)

### Major Vulnerabilities Identified ❌
* **Poor Acess Control:** The **principle of least privilege** is not implemented, allowing any employee to acess critical customer data.
*  **Lack of Business Continuity/Disaster Recovery:** A complete lack of **backups** and a **disaster recovery plan** leaves the company vulnerable to a total shutdown.
*  **Unencrypted Payment Data:** **Encryption is not used** to protect credit card data, which is a critical security failure.
*  **Weak Password Policies:** Policies are weak and there is no system to enforce them, facilitating unauthorized access.
*  **No Threat Detection Capabilities:** The company does not have an **Instrusion Detection System (IDS)**, leaving it "blind" to potential ongoing attacks.

---

### ➤ Compliance Analysis

| Regulation | Status | Analysis Details |
| :--- | :--- | :--- |
| **PCI DSS** | 🔴 **Non-Compliant** | Critical failures in protecting credit card data (lack of encryption and access control) violate fundamental requirements. |
| **GDPR** | 🟡 **Partially Compliant** | ✅ Has a breach notification plan. <br> ❌ Fails to ensure the security of personal data and to classify data properly. |

---

### ➤ Strategic Action Plan

To resolve the identified vulnerabilities, i developed an action plan focused on delivering maximum impact with the lowest initial effort.

#### **CRITICAL Priority (Immediate Implementation)**
1.  **Enable Backups and Create a Disaster Recovery Plan:** Ensure the company can recover from any incident.
2.  **Implement Access Control (Least Privilege):** Restrict data access to only those who truly need it.
3.  **Encrypt Credit Card Data:** Protect customer payments data and achieve PCI DSS compliance.

#### **HIGH Priority (Next Steps)**
4.  **Modernize the Password Policy:** Implement a robust password policy and a management system to enforce it automatically.
5.  **Deploy an Intrusion Detection System (IDS):** Gain real-time visibility into network traffic to detect and respond to potential threats.

--- 

### ➤ Project Artifacts
The reference documents that served as the basis for this audit are available at the links below:
* [Scope and Risk Report](https://github.com/cleyandson/botium-toys-internal-audit-security/blob/main/Documents/Botium%20Toys_%20Scope%2C%20goals%2C%20and%20risk%20assessment%20report.pdf)
* [Controls Categories](https://github.com/cleyandson/botium-toys-internal-audit-security/blob/main/Documents/Control%20categories.pdf)
* [Controls and Compliance Checklist (answered by me)](https://github.com/cleyandson/botium-toys-internal-audit-security/blob/main/Documents/Controls%20and%20compliance%20checklist%20-%20answered.pdf)








