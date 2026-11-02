### F-03: Unauthorized Sensitive Data Exposure

**OWASP Category:** Select according to root cause.

**API Endpoint:** /rest/user/whoami

**Testing Steps:**
1. Logged in with the test account.
2. Inspected the API response.
3. Logged out.
4. Requested the API endpoint again.
5. Compared both responses.

**Potential Impact:**
Unauthorized disclosure of private user information
may affect confidentiality and user privacy.

**Remediation:**
- Enforce server-side authorization.
- Return only necessary user fields.
- Do not expose passwords, secrets or private data.
- Verify access permissions for every API request.