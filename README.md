# password-strength-evaluation
# Password Strength Evaluation Report

## Objective
To create and test multiple passwords of varying complexity using an online password strength checker and identify best practices for secure password creation.

## Passwords Tested

| Password Example       | Score  | Complexity   | Length | Uppercase | Lowercase | Numbers | Symbols | Notable Deductions |
|------------------------|--------|--------------|--------|-----------|-----------|---------|---------|--------------------|
| password123            | 43%    | Good         | 11     | 0         | 8         | 3       | 0       | Consecutive lowercase, sequential numbers |
| Pass@2024              | 92%    | Very Strong  | 9      | 1         | 3         | 4       | 1       | Consecutive lowercase, consecutive numbers |
| S3cur!Ty#Key           | 100%   | Very Strong  | 12     | 3         | 6         | 1       | 2       | Consecutive lowercase |
| H@rd2Cr@ck!Passw0rd    | 100%   | Very Strong  | 19     | 3         | 11        | 2       | 3       | Consecutive lowercase |

---

## Key Observations
1. **Length matters** — passwords over 12 characters with varied symbols score highest.
2. **Mixing character types** (upper, lower, numbers, symbols) is essential for maximum score.
3. **Avoid consecutive or repeated characters** to prevent deductions.
4. **Symbols in the middle** give additional points compared to only at the start or end.

---

## Best Practices Learned
- Use at least **12–16 characters**.
- Combine **uppercase, lowercase, numbers, and special symbols**.
- Avoid **common words, names, or predictable patterns**.
- Use **creative substitutions** (`E` → `3`, `A` → `@`, `O` → `0`).
- Avoid personal info (birthdays, names, etc.).
- Create **passphrases** with unrelated words (e.g., `Sun@Boat#Tiger%2025`).
- Use a **password manager** for unique passwords on each account.

---

## Common Password Attacks

| Attack Type | How It Works | Impact of Strong Passwords |
|-------------|--------------|----------------------------|
| Brute Force Attack | Tries every possible combination until the correct one is found. | Longer and more complex passwords exponentially increase the time needed. |
| Dictionary Attack | Uses a list of common words and variations. | Avoiding dictionary words and adding randomness makes this ineffective. |
| Phishing | Tricks the user into giving the password. | Complexity doesn’t help directly; awareness and 2FA are key. |
| Credential Stuffing | Uses stolen passwords from one site on another. | Unique passwords for each account prevent damage from leaks. |

---

## Conclusion
The **strongest password** in this evaluation was:  
`H@rd2Cr@ck!Passw0rd` — **100% score**, excellent length, high complexity, and minimal deductions.

**Strong password creation + multi-factor authentication = significantly reduced hacking risk.**
