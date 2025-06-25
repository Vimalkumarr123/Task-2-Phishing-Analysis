# 🎣 Task 2 – Phishing Email Analysis (Cybersecurity Internship)

## 👋 Introduction

In this task, I analyzed a sample phishing email to understand how attackers use fake messages to trick users into giving away sensitive information. The exercise helped me recognize social engineering patterns and technical signs of email threats.

---

## 🎯 Objective

To identify phishing characteristics in a suspicious email and understand how phishing works using both human and technical analysis.

---

## 📨 Sample Email Analyzed

📄 File: `sample-email.txt`

Example content:

From: PaypaI Support support@paypaI.com Subject: Urgent: Verify Your Account Now!

Dear user,

We noticed suspicious login activity on your account.
To secure your account, please verify your identity immediately by clicking the link below:

🔗 https://paypaI-security-check.com/login

Failure to comply within 24 hours will result in account suspension.

Sincerely,
PayPal Security Team

---

## 🕵️ Phishing Traits Found

| Trait | Details |
|-------|---------|
| **Fake sender domain** | Domain `paypaI.com` looks like PayPal, but the 'I' is a spoofed character |
| **Urgent language** | “Failure to comply within 24 hours” creates pressure |
| **Suspicious URL** | Link redirects to a fake login site |
| **Grammar issues** | Slightly unnatural sentence structure |
| **Impersonation** | Pretends to be from a trusted company (PayPal) |

---

## 🛠 Tools Used

- Manual inspection (text format)
- (Optional) Online header analyzer: [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx)
- Hover-check for link mismatch

---

## 🔐 Why This Email is Dangerous

- Can steal passwords or financial information
- Tricks the user into acting quickly
- Appears legitimate at first glance

---

## 🛡️ Mitigation Steps

- Do **not click** suspicious links or download files
- Always check **sender's domain**
- Use **email header analyzers** for technical validation
- **Report** to IT/security team or email provider

---

## 📁 Files in This Repo

- `sample-email.txt` – Sample phishing email (text)
- `README.md` – This explanation/report

---

## ✅ Outcome

- I learned how to analyze and break down a phishing email
- Understood how attackers use fear and urgency
- Improved awareness of technical and social aspects of email threats

---

Made with 🧠 and ☕ by VIMAL KUMAR R
