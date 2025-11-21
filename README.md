# Task 6 — Create a Strong Password & Evaluate Its Strength

This repository contains the solution for **Task 6** from the Cyber Security Internship.

The objective of this task is to understand what makes a password strong, test multiple passwords using online tools, and analyze the results.

---

## 🔐 Passwords Tested & Results

| Password | Strength Result | Notes |
|----------|-----------------|-------|
| rahul123 | ❌ Very Weak | Short, predictable, dictionary-based |
| Rahul@2025 | ⚠️ Medium | Contains uppercase + symbol but predictable pattern (name+year) |
| R@hU!92_xyQ | ✔️ Strong | Good randomness, mixed characters |
| cat-horse-yellow-road | ✔️ Very Strong | Long passphrase, hard to brute force |
| W!nT3r_R3d$N0w#A9 | 🔥 Excellent | High complexity, long, random |

Screenshots of each test result are placed inside `/screenshots`.

---

## 📘 What Makes a Password Strong?

A strong password has:
- At least **12–16 characters**
- A mix of **uppercase, lowercase, numbers, and symbols**
- No personal information (name, DOB, phone)
- Random structure or passphrase format
- Uncommon words or patterns

Password strength is primarily determined by:
✔ Length  
✔ Complexity  
✔ Unpredictability  

---

## ⚔️ Common Password Attacks

### **1. Brute Force Attack**
Attacker tries every possible character combination.  
- Short passwords get cracked instantly  
- Longer passwords increase cracking time exponentially  

### **2. Dictionary Attack**
Attacker uses a list of common words ("password", "india123", "rahul") to guess passwords.

### **3. Credential Stuffing**
Uses previously leaked username/password pairs.

---

## 🧩 Why Password Length Matters

- 8-character password → cracked in minutes  
- 12-character password → weeks to months  
- 16+ characters → years to centuries  

Even without symbols, **long passphrases are very strong**.

---

## 🔑 Multi-Factor Authentication (MFA)

MFA adds an additional layer like:
- OTP  
- Authenticator app  
- Biometrics  

Even if a password leaks, MFA prevents account access.

---

## 🧰 Password Managers

Password managers help by:
- Generating strong random passwords  
- Storing them securely  
- Preventing password reuse  

Examples: Bitwarden, 1Password, KeePass.

---

## 🧠 Passphrases

A passphrase is a long combination of unrelated words:
