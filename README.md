# Task 6 — Password Strength Evaluation

## Objective
Understand what makes a password strong, test multiple examples using online password strength checkers, and summarize best practices and common password attacks.

---

## Test Results

| Password                | Score | Strength    | Feedback from Tool                        |
| ----------------------- | ----- | ----------- | ----------------------------------------- |
| password123             | 15%   | Very Weak   | Too short, common word, no symbols        |
| Sunshine@2024           | 65%   | Medium      | Better complexity but still predictable   |
| L0ng#Tr1ckyPa$$word!    | 92%   | Strong      | Excellent mix of length, symbols, numbers |
| BlueHorse!Rides77@Dawn  | 98%   | Very Strong | Long, unique, passphrase style            |
| Qw9$Bv!t3nM^yR           | 95%   | Strong      | Good complexity & length                  |

---

## Best Practices for Strong Passwords
1. **Length matters** — aim for at least 12–16 characters.
2. **Mix character types** — use uppercase, lowercase, numbers, and symbols.
3. **Avoid predictable patterns** — skip `123456`, `qwerty`, repeated characters.
4. **No personal info** — avoid birthdays, names, or anything public.
5. **Passphrases work well** — combine random unrelated words with symbols/numbers.
6. **Unique for every site** — don’t reuse passwords.
7. **Use a password manager** — securely store and generate passwords.
8. **Enable MFA** — adds a second layer of security.
9. **Change after breaches** — update compromised credentials immediately.
10. **Test strength** — use trusted password strength tools.

---

## Notes on Common Password Attacks

### 1. Brute Force
- Tries every possible combination until it finds the password.
- Defense: Long and complex passwords; limit login attempts; use MFA.

### 2. Dictionary Attack
- Uses a list of common words/passwords.
- Defense: Avoid dictionary words, use randomness.

### 3. Credential Stuffing
- Uses stolen credentials from one breach to try other sites.
- Defense: Unique passwords for every account.

### 4. Phishing
- Tricks you into revealing credentials via fake sites or emails.
- Defense: Verify URLs, avoid clicking unknown links, use MFA.

### 5. Keylogging
- Malware records your keystrokes.
- Defense: Keep systems updated, use antivirus, avoid suspicious downloads.

### 6. MITM Attack
- Intercepts data over insecure networks.
- Defense: Use HTTPS, VPN, avoid logging in on public Wi-Fi.

---

## Interview Question Answers
1. **Strong password:** Long, complex, unpredictable.
2. **Common attacks:** Brute force, dictionary, phishing, credential stuffing.
3. **Length importance:** Increases combinations exponentially, making brute force harder.
4. **Dictionary attack:** Attempts known/common passwords from a predefined list.
5. **MFA:** Multi-Factor Authentication adds a second verification step beyond a password.
6. **Password managers:** Store/generate strong unique passwords securely.
7. **Passphrases:** Sequence of random words, longer and easier to remember.
8. **Common mistakes:** Short passwords, reusing passwords, using personal info.

---
