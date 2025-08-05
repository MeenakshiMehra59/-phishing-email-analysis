
 # 📧 Phishing Email Analysis Report

Analyzing Phishing emails using Google Admin Toolbox-Internship Task 2
**Intern Name:** Meenakshi Mehra  
**Role:** Cybersecurity Intern  
**Organization:** Elevate Labs  
**Date:** 5 August 2025

---

## 📝 Overview

Two suspicious emails were analyzed to assess potential phishing threats.  
This report summarizes phishing indicators and provides security recommendations.

---

## 📩 Email 1: "Contoso Corp HR Shared an Item"

**Details:**
- **From:** support@cont0so-c0rp.org  
- **Subject:** Contoso Corp HR shared an item  
- **Attachment:** Updated Company Org Chart - Contoso Corp.pdf  

**Message:**
> "Contoso Corp Human Resources (HR) has shared the following item:  
> Due to unforeseen circumstances, changes have been made to the current management structure.  
> Download the new org chart below to understand how these changes impact you."

### 🔍 Phishing Indicators:
- ⚠️ **Fake Domain:** `cont0so-c0rp.org` mimics `contoso.com`
- ⚠️ **Urgency Tactic:** "Unforeseen circumstances"
- ⚠️ **Suspicious PDF attachment**
- ⚠️ **No personalization**
- ⚠️ **Header Failures:**  
  - SPF: Failed  
  - DKIM: None  
  - DMARC: Failed  
  - IP: 185.129.62.77 (Foreign)

### ✅ Recommendations:
- Do not open or download the attachment.
- Report to IT/Security.
- Mark sender as spam and block.

---

## 📩 Email 2: "Google Notifications – Sign-in Attempt Blocked"

**Details:**
- **From:** google-support@webnotifications[.]net  
- **To:** john.doe@mybusiness.com  
- **CTA:** “Check activity” button

**Message:**
> "Someone just used your password to try to sign in to your account from a non-Google app.  
> Google blocked them, but you should check what happened."

### 🔍 Phishing Indicators:
- ⚠️ **Fake Google domain:** `webnotifications.net`
- ⚠️ **Fear tactic**: Suggests account is compromised
- ⚠️ **Malicious link**
- ⚠️ **No personalization**
- ⚠️ **Header Failures:**  
  - SPF: Failed  
  - DKIM: None  
  - DMARC: Failed

### ✅ Recommendations:
- Don’t click suspicious links.
- Mark as phishing.
- Verify via official Google pages.

---

## 🔒 Conclusion

Both emails demonstrate common phishing tactics:
- Lookalike domains
- Social engineering
- Header failures
- Lack of personalization

🛡️ Always analyze headers using tools like [Google Admin Toolbox](https://toolbox.googleapps.com/apps/messageheader/).

> 📝 *Note: Both emails were simulated for training. Headers were created manually for analysis.*

---
