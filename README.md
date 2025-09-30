# Task 6 — Create a Strong Password and Evaluate Its Strength

**Author:** Kush Thaker (kthaker442@gmail.com)  
**Purpose:** Demonstrate password-strength concepts by creating sample passwords of varying complexity, testing them with online checkers, and summarizing best practices.

---

## Objective
Understand what makes a password strong, generate example passwords at different strength levels, test them using online password-strength tools, record results, and derive actionable tips for creating secure passwords.

---

## Tools (suggested)
- Password strength checkers: [passwordmeter.com], Bitwarden password strength tester, or any reputable online checker.  
- Local files in this repo:
  - `password.txt` — contains example passwords used for demonstration.  
  - `Task6Report.pdf` — full detailed report and practical test results.  
  - `images/` — screenshots of the password checks and tests.

---

## Deliverables
1. **This README.md** — summary and example passwords (this file).  
2. **password.txt** — plain list of passwords used (for example/testing).  
3. **Task6Report.pdf** — full, detailed report with methodology, test screenshots, and analysis (see main branch).  
4. **images/** — screenshots of online tool output and any other evidence.

---

## Password Examples

> **Note:** These are example passwords created for learning/testing only. Do **not** use them for real accounts.

### 🔴 Weak passwords (10 examples)
1. password  
2. 123456  
3. qwerty  
4. kush123  
5. abc123  
6. iloveyou  
7. admin  
8. football  
9. welcome  
10. 111111  

---

### 🟡 Medium passwords (10 examples)
1. Kush@123  
2. Hello2025  
3. MyPass!1  
4. Thaker#9  
5. Summer2024  
6. AbcD@456  
7. Secure99  
8. Rajkot#7  
9. College@22  
10. Pass@Word8  

---

### 🟢 Strong passwords (10 examples)
1. Ku$hTh@k3r_2004!  
2. !R@jK0t_2o25#Xx  
3. 9p*Lw@Q7#tZm!8  
4. C0ll3g3$@Tr!p99  
5. Th@k3rK#2025!$  
6. #Xx9zLp!7Qw$@4t  
7. My$3cur3_P@ssw0rd2025!  
8. Tr@v3l&P@ck#909  
9. !S3cur!ty_#L0cks77  
10. Qw!ErTy#2025@99$  

---

## How to test
1. Open an online password strength checker (e.g., passwordmeter.com or Bitwarden).  
2. Copy one password from `password.txt` and paste it into the tool.  
3. Record the **score / percentage** and any feedback (e.g., “too short”, “common pattern”, “add symbols”, “use more length”).  
4. Repeat for each example password.  
5. Save screenshots to `images/` and summarize results in your report (`Task6Report.pdf`).  

---

## Suggested Result Table
| Password example       | Tool used      | Score (%) | Feedback from tool         | Notes (crackability estimate) |
|------------------------|---------------|-----------|----------------------------|--------------------------------|
| kush123                | passwordmeter | 12        | Too short, common word     | Very weak — dictionary attack  |
| Kush@123               | Bitwarden     | 45        | Add length, less predictable | Medium — pattern-based risk    |
| Ku$hTh@k3r_2004!       | passwordmeter | 92        | Good length & complexity   | Strong — high brute-force cost |

*(Fill this table with each test’s actual results and attach screenshots in `images/`.)*

---

## Key Findings
- **Length matters most:** Longer passwords (≥12 characters) drastically increase time-to-crack.  
- **Character variety reduces guessability:** Use uppercase, lowercase, numbers, and symbols.  
- **Avoid dictionary words & predictable substitutions:** Simple substitutions (`o`→`0`, `a`→`@`) are well-known to attackers.  
- **Randomness and non-personal content** improve security.  
- **Password managers** help generate and store high-entropy passwords safely.

---

## Best Practices
- Use a **passphrase** or a long random string (12+ characters recommended).  
- Mix character types: uppercase, lowercase, numbers, symbols.  
- Avoid common words, repeated characters, or sequences.  
- Use a **password manager** to generate/store unique passwords for every site.  
- Change important passwords periodically and after any suspected compromise.  
- Enable multi-factor authentication (MFA).

---

## Where to find more details
For the **complete, detailed report** with methodology, full test results, and screenshots, see **`Task6Report.pdf`** in the main branch of this repository.  
Screenshots of the tests are available in the `images/` folder.  
The example passwords used for demonstration are stored in `password.txt`.

---

## Contact
For clarifications or customized strong password sets, contact: **kthaker442@gmail.com**.

---

**End of README.md**
