# Data Privacy & Confidentiality

## 🔍 Research & Learn

### 1. Key Takeaways from Focus Bear’s Privacy Policy
* **GDPR & Legal Compliance:** Focus Bear processes data under the GDPR (EU) 2016/679 and Australian regulations, ensuring all handling is fair, lawful, and transparent.
* **Data Minimization:** The company strictly adheres to collecting only the personal data necessary for specific and clear purposes.
* **Double Encryption:** Sensitive "Special Category" data (like health-related habits) is double-encrypted so that even Focus Bear staff cannot access it unless explicitly requested by the user for troubleshooting.
* **User Control:** Users maintain the right to access, correct, delete, or restrict the processing of their data at any time.
* **Specialized Vendors:** The policy utilizes two distinct categories of third-party processors:
    * **Category A (Authentication & IT):** Auth0 and Zoho for secure login and email management.
    * **Category B (Financial & Analytical):** Stripe for payments (no card data stored internally) and PostHog/Brevo for technical analytics.

### 2. Confidential Data Types at Focus Bear

| Data Category | Examples |
| :--- | :--- |
| **Identification Data** | Email addresses, phone numbers. |
| **Special Category Data** | Health status (ADHD/Autism), religious beliefs. |
| **Technical Data** | Device types, operating systems, error logs. |
| **Economic/Financial** | Credit card numbers (managed by Stripe). |
| **Social & Profile** | Lifestyle characteristics, habit preferences, survey feedback. |

### 3. Best Practices for Handling Confidential Data
* **Anonymization:** Occupation and survey data are kept anonymous and never linked back to individual personal details.
* **Least Privilege Access:** Access to contact details is restricted to team members who strictly need it for communication or bug fixes.
* **Restricted Habit Access:** Staff are prohibited from viewing user habits unless the user explicitly grants permission during a support request.
* **Outsourced Risk:** High-risk data is handled by specialized global processors to reduce the internal attack surface.

### 4. Responding to a Data Breach
1.  **Evaluation:** Immediate assessment of the impact of any potential security breach.
2.  **Regulatory Reporting:** Reporting breaches to the OAIC (Australia) or AEPD (Spain) per GDPR timelines.
3.  **Rapid Restoration:** Maintaining systems to quickly restore data availability following an incident.
4.  **Continuous Auditing:** Regular assessment of security measure effectiveness.

---

## 📝 Reflection

### Daily Tasks & Security
I will follow the principle of **Data Minimization**, accessing only the specific data required to complete a task. I will perform **Local Anonymization** by manually stripping out PII (emails/device identifiers) before using log data for troubleshooting. Furthermore, I will perform a **Verification of Encryption** to ensure "Special Category" data remains double-encrypted and never exists in plain text during analysis.

### Storage, Sharing, and Disposal
* **Storage:** I will never store confidential Focus Bear data on personal devices. I will only use company-approved secure environments (Auth0/Zoho).
* **Sharing:** Technical data shared with vendors (PostHog/Brevo) will be sent via encrypted channels with the minimum info required.
* **Disposal:** I will follow strict retention criteria to delete or permanently anonymize data once it is no longer necessary.

### Avoiding Common Mistakes
* **Over-sharing in Support:** I will use automated scripts to mask sensitive fields in raw logs.
* **Mismanaging Vendor Access:** I will ensure vendors only receive data they are contracted to handle.
* **Inadequate Anonymization:** I will ensure survey data is handled in aggregate form only.

---

## 🛠️ Task Execution

### Habit to Adopt: "Anonymization First"
As a Cybersecurity intern, I am adopting a strict **"Zero-PII" rule** for my digital workspace. I commit to never passing raw logs containing emails, IP addresses, or session tokens to AI agents or external platforms without first performing a manual and scripted anonymization pass.

### Security Measure: Standardized Anonymization Checklist
I will use the following checklist before exporting any technical data for troubleshooting:

- [ ] **Removal of PII:** Strip all email addresses and usernames.
- [ ] **Infrastructure Masking:** Redact internal IP addresses and device hostnames.
- [ ] **Credential Scrubbing:** Remove session tokens, API keys, and authorization headers.
- [ ] **Technical Validation:** Confirm the remaining data is purely technical and anonymous.
