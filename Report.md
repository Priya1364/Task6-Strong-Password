Task 6 — Create a Strong Password and Evaluate Its Strength

**Objective:** Understand what makes a password strong and test it with online password strength tools.

**Tools used:** Mobile browser (Chrome), Password strength checker (e.g., passwordmeter.com), screenshots, GitHub (mobile), Google Forms for submission.

---

## Method
1. Created several example passwords with different complexity levels.
2. Tested each password on a password strength checker (enter password, note score and feedback).
3. Took screenshots of the strength-meter results.
4. Recorded findings in a table and wrote best-practices based on the feedback.
5. Prepared this report and uploaded screenshots to GitHub.

---

## Passwords tested (examples — **do not use these exact passwords**; they are examples only)
| # | Example password (example only)        | Length | Char types used                 | Example evaluation |
|---|---------------------------------------|--------:|---------------------------------|--------------------|
| 1 | password123                            | 11     | lowercase + digits              | Very weak — common, easily guessed |
| 2 | P@ssw0rd!                              | 9      | upper, lower, digit, symbol     | Weak — short and common pattern    |
| 3 | CorrectHorseBatteryStaple              | 25     | only letters (phrase)           | Strong — long passphrase, good length |
| 4 | Blue!Fish7_RiseMoon                    | 18     | upper, lower, digit, symbols    | Very strong — length + varied chars |
| 5 | green-apple-tree-7-hike                 | 23     | lowercase, symbols, digits      | Strong — passphrase style, readable & long |

**Notes:** The exact numeric score depends on the tool. Common feedback from password meters:
- Increase length for large gains in strength.
- Use uncommon words and symbols, and avoid personal info.
- Avoid simple substitutions (e.g., 'password' → 'P@ssw0rd' is predictable).

---

## Example (sample) password-meter feedback (what the tool may show)
- “Weak: too common” — avoid dictionary words alone.
- “Add length for much better protection.”
- “Use a mix of upper, lower, numbers and symbols.”
- “Avoid repeated characters and keyboard patterns.”

---

## Best practices & recommendations
1. **Prefer long passphrases** (3–4 random words or a phrase) — length helps more than complex substitutions.  
2. **Length rule of thumb:** ≥ 12 characters, preferably ≥ 16 for important accounts.  
3. **Use a mixture** of uppercase, lowercase, digits and symbols when possible.  
4. **Avoid personal info** (names, birthdays, favorites).  
5. **Unique password per account** — never reuse.  
6. **Use a password manager** (KeePass, Bitwarden) to generate/store unique strong passwords.  
7. **Enable MFA** (authenticator apps are preferred over SMS).  
8. **Use passphrases** made of unrelated words or a random word generator.  
9. **Check passwords with a reputable tool**, but never enter real working passwords into untrusted sites — use example/test passwords or a local password manager’s strength estimator.  
10. **Regularly audit** important accounts (email, banking) and enable recovery options.

---

## Short summary of password attacks (why complexity matters)
- **Brute force:** tries every possible combination — longer passwords increase time required exponentially.  
- **Dictionary attack:** uses common words/phrases from lists — avoid dictionary words and obvious variants.  
- **Credential stuffing:** uses leaked credentials from other sites — safeguards: unique passwords + MFA.  

---

## Conclusion
Using a long, unique passphrase plus MFA and a password manager provides strong, practical protection. Screenshots of actual tool results are included in `/screenshots`.

---

## Files in this repo
- `report.md` (this file)
- `README.md`
- `/screenshots/` — screenshots of password-meter results
