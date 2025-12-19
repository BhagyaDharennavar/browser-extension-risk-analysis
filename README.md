# Identify and Remove Suspicious Browser Extensions

## 📌 Introduction
Web browsers like Google Chrome support small add-on programs called **browser extensions**.  
These extensions add extra features to the browser, but they can also introduce **security risks** if not managed properly.

This task focuses on learning how to **review, analyze, and manage browser extensions safely**, which is an important real-world cybersecurity skill.

---

## 🧠 What is a Browser Extension?
A **browser extension** is a small software component that runs inside a web browser to extend its functionality.

### Examples:
- Ad blockers
- Grammar checkers
- Password managers
- Screenshot tools
- Security warning tools

### Why extensions are risky:
Extensions can:
- Read website data
- Track browsing activity
- Access typed information
- Run in the background continuously

Because of this, **malicious extensions** can steal data or spy on users.

---

## 🛠 Tools Used
- Google Chrome Browser
- Chrome Extensions Manager (`chrome://extensions`)

---

## 🔍 Screenshot: Installed Browser Extensions

The screenshot below shows all extensions installed in the browser **before analysis**.

![https://github.com/BhagyaDharennavar/browser-extension-risk-analysis/blob/main/Screenshot%202025-12-19%20150635.png)

### Screenshot Explanation:
From the extensions manager, I could see:
- Extension name
- Developer
- Enable/Disable status
- Options to view details or remove extensions

This page is used to manage browser security related to extensions.

---

## 📋 Extensions Identified
During review, the following extensions were found installed:

1. Application Launcher for Drive (by Google)
2. Google Docs Offline
3. McAfee® WebAdvisor

Each extension was analyzed individually.

---

## 🔎 Detailed Extension Analysis

### 1️⃣ Application Launcher for Drive (by Google)

**What is it?**  
This extension allows users to open Google Drive files directly in desktop applications installed on the system.

**Developer:** Google  
**Status:** Disabled  
**Usage:** Not actively used

**Security Analysis:**
- Developed by a trusted source (Google)
- Not malicious
- However, it was unused and unnecessary

**Why it was removed:**
- Unused extensions increase browser attack surface
- Even safe extensions can be exploited if compromised
- Following the **Principle of Least Privilege**, unused extensions should be removed

**Action Taken:** ✅ Removed

---

### 2️⃣ Google Docs Offline

**What is it?**  
Allows users to view and edit Google Docs, Sheets, and Slides without an internet connection.

**Developer:** Google  
**Status:** Enabled  
**Usage:** Actively useful

**Security Analysis:**
- Official Google extension
- Requests only necessary permissions
- Widely used and trusted

**Action Taken:** ✅ Kept (Safe extension)

---

### 3️⃣ McAfee® WebAdvisor

**What is it?**  
A security extension that warns users about dangerous websites, phishing links, and malicious downloads.

**Developer:** McAfee (Security Vendor)  
**Status:** Enabled  

**Security Analysis:**
- Requires browsing access (expected for security tools)
- Developed by a reputable cybersecurity company
- Helps improve browsing safety

**Action Taken:** ✅ Kept (Trusted extension)

---

## 🔐 Why Browser Extensions Can Be Dangerous
Malicious or poorly designed extensions can:
- Steal saved passwords
- Track browsing history
- Inject phishing links or advertisements
- Redirect users to fake websites
- Monitor keystrokes and user behavior

Many users get compromised **without downloading malware**, just by installing unsafe extensions.

---

## 🔑 Security Best Practices Followed
- Reviewed all installed extensions
- Checked developer authenticity
- Evaluated permissions
- Removed unused extensions
- Reduced browser attack surface

---

## 🎯 Outcome of This Task
- Improved awareness of browser security risks
- Learned how to audit browser extensions
- Understood permission abuse risks
- Practiced real-world cybersecurity hygiene

---

## 🧠 Key Concepts Learned
- Browser security
- Extensions and permissions
- Malware risks
- Principle of Least Privilege
- User-side security responsibility

---

## ✅ Conclusion
This task demonstrated how even legitimate browser extensions must be reviewed regularly.  
By removing unused extensions and understanding permissions, users can significantly improve their browsing security.
