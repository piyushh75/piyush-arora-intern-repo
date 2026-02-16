# AI Usage Guidelines & Reflection: Cybersecurity Analyst

## 🔍 Research & Learn

### 1. What AI tools are typically used for your role?
* **AI-Enhanced SIEM/SOAR**: Platforms like Microsoft Sentinel or Splunk that use machine learning to filter alert "noise" and prioritize critical incidents.
* **Security-Specialized Copilots**: LLMs such as Google Security AI Workbench, specifically trained to summarize threat actor behaviors and draft remediation scripts.
* **Log Analysis via General LLMs**: Leveraging Gemini, ChatGPT, or Claude to parse, normalize, and interpret complex unstructured logs (e.g., Syslog, CloudTrail) to identify unauthorized access patterns.
* **Automated Malware Analysis**: AI-driven sandboxes that "detonate" suspicious files to predict malicious behavior based on historical heuristics.

### 2. What are the benefits and risks of using AI in a professional setting?
* **Benefits**: Significantly reduces Mean Time to Respond (MTTR), automates high-velocity tasks like log parsing, and provides 24/7 scalability for monitoring.
* **Risks**: Potential for "Adversarial AI" where hackers scale attacks, AI "hallucinations" that provide false security justifications, and the critical risk of proprietary data leakage.

### 3. What types of information should NEVER be entered into AI tools?
* **Network Infrastructure**: Internal IP ranges, firewall rules, or detailed network topology maps.
* **Confidential Vulnerabilities**: Unpatched scan results or internal penetration test findings.
* **Security Credentials**: API keys, GitHub tokens, passwords, or SSH keys.
* **Unanonymized Data**: Raw logs containing Personal Identifiable Information (PII) or active session tokens.

### 4. How can you fact-check and validate AI-generated content?
* **Threat Intel Cross-Referencing**: Always verify AI findings against authoritative sources like MITRE ATT&CK, VirusTotal, or Cisco Talos.
* **Manual Script Audit**: Perform a line-by-line review of any AI-generated patch or code before deployment to ensure no backdoors are introduced.
* **Evidence Tracing**: Trace every AI conclusion back to the original raw log source to ensure the finding is not a hallucination.

---

## 📝 Reflection

### When to use AI vs. Own Skills
* **Use AI Assistance**: For deobfuscating complex scripts, summarizing massive log datasets, or drafting initial incident reports.
* **Rely on Own Skills**: For final risk assessments, ethical security decisions, and high-level architecture that requires specific business context.

### How to Avoid Over-reliance
* **15-Minute Rule**: I will attempt manual analysis or troubleshooting for at least 15 minutes before seeking AI help to keep my security intuition sharp.
* **Blind Testing**: I will occasionally perform tasks manually and then compare the results with AI output to identify potential blind spots in the model.

### Steps to Ensure Data Privacy
* **Mandatory Anonymization**: I will use data masking to remove real IPs, hostnames, and usernames before any analysis.
* **Local Processing**: Wherever possible, I will utilize local scripts or offline tools for sensitive data instead of public cloud-based LLMs.

---

## 🛠️ Task Execution

### Task Improved: Log Analysis & Script Adaptation
I utilized an LLM to adapt a repository setup script for a Windows environment.
* **Critical Review**: The AI initially suggested a Linux command (`cp`) which was incompatible. I manually identified and corrected it to the Windows equivalent (`copy`), confirming that AI technical advice requires human validation.

### Best Practice for Focus Bear
**"Zero-Trust Prompting"**: I will treat every prompt as a public post. No sensitive Focus Bear infrastructure details (Internal IPs, specific hostnames, or private keys) will be shared without strict, verified anonymization.
