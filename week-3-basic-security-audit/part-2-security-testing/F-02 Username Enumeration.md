### F-02: Username Enumeration

**OWASP Category:** A07:2025 - Authentication Failures

**Testing Steps:**
1. Tested an existing lab account with an incorrect password.
2. Tested a non-existing lab email.
3. Compared the error messages.

**Potential Impact:**
An attacker may identify valid user accounts and target
them with phishing or credential attacks.

**Remediation:**
- Return generic login error messages.
- Apply login rate limiting.
- Monitor repeated failed login attempts.
- Enable multi-factor authentication.