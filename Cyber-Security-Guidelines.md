# Cyber Security Guidelines

## 🔍 Research & Learn

### 1. What are common cyber security threats in a remote work environment?

**Phishing and Social Engineering:** Attackers use deceptive emails or messages to trick employees into revealing credentials or downloading malware.

**Unsecured Networks:** Working from public Wi-Fi without a VPN can expose data to "man-in-the-middle" attacks.

**Adversarial AI:** Threat actors utilize AI to scale sophisticated phishing campaigns and automate malware development.

**Credential Stuffing:** Hackers use stolen passwords from other breaches to try and gain access to company accounts.

### 2. What are best practices for keeping your devices and accounts secure?

**Regular Updates:** Keep your operating system and software updated to patch known vulnerabilities.

**Device Encryption:** Ensure your hard drive is encrypted so that data is unreadable if the device is lost or stolen.

**Principle of Least Privilege:** Access only the data and systems required for your current task.

**Local Security:** Use antivirus software and maintain a "Zero-Trust" posture for all incoming files.

### 3. Why is it important to lock your computer when away from your desk?

**Prevent Unauthorized Physical Access:** Locking your screen ensures that no one else can view sensitive user data or internal infrastructure details while you are away.

**Session Protection:** It prevents "session hijacking" where an unauthorized person could send messages or access secure portals using your active login.

### 4. How should you handle phishing attempts and suspicious links?

**Verification:** Never click a link or download an attachment from an unsolicited source without verifying the sender via a separate channel.

**Report and Delete:** Immediately report the suspicious activity to the security lead and delete the message.

**Hover Before Clicking:** Hover your mouse over links to see the actual destination URL before clicking.

### 5. What makes a strong password, and why should you use a password manager?

**Complexity and Length:** A strong password is long (12+ characters) and uses a mix of uppercase, lowercase, numbers, and symbols.

**Unique for Every Account:** You should never reuse passwords across different platforms to prevent a single breach from compromising all your accounts.

**Password Managers:** These tools securely store and generate complex passwords so you don't have to remember them, significantly reducing the risk of credential theft.

### 6. Why is two-factor authentication (2FA) important, and when should you enable it?

**The Second Layer of Defense:** 2FA ensures that even if a hacker steals your password, they still cannot access your account without the second factor (like an authenticator app code).

**Mandatory Usage:** 2FA should be enabled on all accounts, especially for primary work tools like GitHub, Email, and Slack.

---

## 📝 Reflection

### 1. What security measures do you currently follow, and where can you improve?

**Current Measures:** I currently use two-factor authentication (2FA) for all primary accounts and follow a strict "Zero-Trust" policy when opening attachments or links from external sources.

**Areas for Improvement:** I plan to improve my workflow by implementing a more rigorous schedule for auditing my active sessions and clearing browser cookies/cache daily to minimize the risk of session hijacking.

### 2. How can you make secure behaviour a habit rather than an afterthought?

**Physical Habit:** I will adopt the "Win + L" (Lock) muscle memory every time I step away from my workstation, even in a home environment, to prevent unauthorized access.

**Digital Hygiene:** I will make "Anonymization First" a standard part of my log analysis process, ensuring that no raw PII ever touches an external tool or AI agent.

**Continuous Learning:** I will stay updated on the latest remote-work threats, such as sophisticated phishing and adversarial AI, so that spotting red flags becomes a natural reflex.

### 3. What steps will you take to ensure your passwords and accounts are secure?

**Password Complexity:** I will ensure every work-related account has a unique, high-entropy password (12+ characters) that includes a mix of character types.

**Manager Adoption:** I will use a professional password manager to generate and store these credentials, eliminating the risk of password reuse.

**Mandatory 2FA:** I will enable 2FA on every service that supports it, prioritizing hardware-based or authenticator app factors over SMS to increase the barrier against credential theft.

### 4. What would you do if you suspected a security breach or suspicious activity on your account?

**Isolate and Contain:** I would immediately disconnect the affected device from the network to prevent lateral movement or data exfiltration.

**Credential Rotation:** I would immediately change my master password and rotate API keys or session tokens from a known-secure device.

**Official Escalation:** I would follow the Focus Bear escalation protocol by reporting the activity to the security lead via the most urgent channel available (SMS or Call for emergencies).

**Forensic Review:** I would review account logs to identify the entry point and the extent of the unauthorized activity to prevent a recurrence.

---

## 🛠️ Task Execution

### 1. Secure Account Configuration

**Strong Passwords & 2FA:** I have audited my work accounts (GitHub, Email, Slack) and ensured they use high-entropy passwords of at least 12 characters.

**Multi-Factor Authentication:** I will integrate the use of 2FA wherever possible, especially for primary work tools, to add a critical second layer of defense.

### 2. Password Storage Method

**Password Manager Integration:** I will integrate the use of a professional password manager to securely store and generate complex passwords so I don't have to remember them.

**Risk Reduction:** Using a manager significantly reduces the risk of credential theft and ensures I never reuse passwords across different platforms.

### 3. Automatic Locking Setup

**Device Configuration:** I have set up my computer and phone to automatically lock after a few minutes of inactivity, requiring a biometric or password login.

**Physical Security:** I have adopted the habit of manually locking my screen (Win + L) every time I step away from my desk to prevent unauthorized access.

### 4. New Cyber Security Habit

**Credential Integrity:** I commit to the habit of integrating the use of password managers and 2FA wherever possible. By using these tools to generate and store unique, 12+ character passwords, I am significantly reducing the risk of credential theft and ensuring my accounts remain secure.
