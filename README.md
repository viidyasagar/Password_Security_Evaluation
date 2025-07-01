# Password_Security_Evaluation
This project demonstrates how different types of passwords affect security and how to evaluate their strength using tools available in Kali Linux.

## 🛠️ Tools Used

- 🐧 Kali Linux (2024.1)
- 🔎 `cracklib-check` for password strength evaluation
- 📄 `rockyou.txt` wordlist for dictionary attack insight
- 💻 Shell scripting
- (Optional) 🌐 Online Password Strength Checker: [passwordmeter.com](https://www.passwordmeter.com)

---

## 📂 Files Included

| File Name              | Description                                           |
|------------------------|-------------------------------------------------------|
| `passwords.txt`        | Sample passwords of varying complexity               |
| `results.txt`          | Output of password strength test using cracklib-check|
| `password_tips.txt`    | Best practices and tips learned                       |
| `password_summary.txt` | Summary of how password complexity affects security   |
| `README.md`            | This documentation file                               |
| `screenshots/` (opt.)  | Screenshots of testing on online tools (if used)      |

---

## 🔤 Sample Passwords

Examples tested in `passwords.txt`:
- `password`
- `Password123`
- `Pass@2025!`
- `$3cur3P@ssw0rd!`
- `Very$tr0ng&LongP@ss2025!`

These passwords include variations in:
- Length
- Case sensitivity
- Special characters
- Dictionary usage

---

## 📊 Password Strength Results

Checked using `cracklib-check`.  
Weak passwords (like `password`, `123456`) failed due to:
- Being too short
- Found in dictionaries
- Lacking complexity

Strong passwords (like `$3cur3P@ssw0rd!`) passed successfully.

---

## 💡 Tips for Creating Strong Passwords

Saved in `password_tips.txt`. Key points include:

- ✅ Use at least **12+ characters**
- ✅ Combine **uppercase**, **lowercase**, **numbers**, and **symbols**
- ❌ Avoid dictionary words (`admin`, `welcome`, etc.)
- ❌ Avoid keyboard patterns (`qwerty`, `123456`, etc.)
- ✅ Use passphrases like `MyD0g@Eats$Pizza!`

---

## 🔍 Common Password Attacks

Covered in `password_summary.txt`:
- 🔨 **Brute-force attacks**: Tries all combinations
- 📚 **Dictionary attacks**: Uses known weak passwords
- 🤖 **Hybrid attacks**: Combines dictionary with patterns

---

## 🔐 Password Complexity & Security Summary

Complex passwords:
- Increase **entropy**
- Slow down brute-force attacks
- Defend against **credential stuffing**
- Are less likely to be guessed or reused

---

