# Task 6 — Create a Strong Password & Evaluate Its Strength  
Cyber Security Internship — Password Security Analysis  

This repository contains my solution for **Task 6**, where I created multiple passwords, tested them using **PasswordMonster.com**, and analyzed their strength, crack time, and security level.

---

## 🔐 Password Test Results (Based on Screenshot Evidence)

Below are the results from the password tests I performed on **PasswordMonster.com** using different complexity levels.

---

### ❌ 1. Weak Password (Personal + Short)
**Password:** `Rahul12`  
**Strength:** Weak  
**Length:** 7 characters  
**Crack Time:** **1 hour**  
**Reason:**  
- Contains a dictionary name (“Rahul”)  
- Only one uppercase letter  
- No symbols  
- Too short  
- Predictable structure

📸 *Screenshot:* `screenshots/Rahul12.png`

---

### ⚠️ 2. Medium Password (Name + Year Pattern)
**Password:** `rahul@2025`  
**Strength:** Medium  
**Length:** 10 characters  
**Crack Time:** **10 days**  
**Reason:**  
- Contains personal info (name + year)  
- Basic symbol  
- Predictable pattern  
- Vulnerable to dictionary and targeted attacks  

📸 *Screenshot:* `screenshots/rahul2025.png`

---

### ✅ 3. Very Strong Password (Random Mixed)
**Password:** `R@hU!92_xyQ`  
**Strength:** Very Strong  
**Length:** 11 characters  
**Crack Time:** **12 million years**  
**Reason:**  
- Contains uppercase, lowercase, numbers, and symbols  
- High randomness  
- No dictionary words  
- Good entropy despite shorter length  

📸 *Screenshot:* `screenshots/R@hU.png`

---

### ✅ 4. Very Strong Password (Passphrase Style)
**Password:** `cat-horse-yellow-road`  
**Strength:** Very Strong  
**Length:** 21 characters  
**Crack Time:** **1,000 years**  
**Reason:**  
- Long passphrase  
- Easy to remember  
- Hard to brute force  
- Uses hyphens to separate words  

📸 *Screenshot:* `screenshots/passphrase.png`

---

### 🔥 5. Very Strong Password (Highly Complex & Random)
**Password:** `W!nT3r_R3d$N0w#A9`  
**Strength:** Very Strong  
**Length:** 17 characters  
**Crack Time:** **9,000 years**  
**Reason:**  
- High complexity  
- Fully random  
- Contains all character types  
- Strong entropy  

📸 *Screenshot:* `screenshots/W!nT3r.png`

---

## 📊 Summary Table

| Password | Strength | Crack Time | Notes |
|----------|----------|------------|-------|
| `Rahul12` | Weak | 1 hour | Short, dictionary word |
| `rahul@2025` | Medium | 10 days | Name + predictable pattern |
| `R@hU!92_xyQ` | Very Strong | 12 million years | Random mixed pattern |
| `cat-horse-yellow-road` | Very Strong | 1,000 years | Long passphrase |
| `W!nT3r_R3d$N0w#A9` | Very Strong | 9,000 years | Highly complex & random |

---

## 🧠 What I Learned

### ✔ Password complexity matters  
Longer and more complex passwords dramatically increase crack time.

### ✔ Passphrases are powerful  
Easy to remember but highly secure because of length.

### ✔ Avoid personal information  
Names, DOB, years, phone numbers → unsafe.

### ✔ Randomness > Substitution  
Simple tricks like replacing "a" → "@" are not enough.

### ✔ Use mixed character types  
Uppercase, lowercase, numbers, symbols.

---

## 🛡 Why Length Is Crucial  
Cracking time increases exponentially with length:

- **7 characters → hours**  
- **10 characters → days**  
- **17+ characters → thousands of years**  

---

## 🔒 Best Practices for Strong Passwords  
- Minimum **12–16 characters**  
- Mix character types  
- Avoid names & predictable sequences  
- Use **password managers**  
- Enable **Multi-Factor Authentication (MFA)**  
- Prefer **long random passphrases**

---

## 📁 Screenshots Folder

All test results are included in:

