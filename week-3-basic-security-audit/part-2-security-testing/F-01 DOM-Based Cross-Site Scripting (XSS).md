### F-01: DOM-Based Cross-Site Scripting (XSS)

**OWASP Category:** A05:2025 - Injection

**Affected Feature:** Search

**Testing Steps:**
1. Opened local OWASP Juice Shop.
2. Opened the Search feature.
3. Entered the XSS test payload used in the lab.
4. A JavaScript alert popup appeared.

**Evidence:**
XSS alert popup screenshot.

**Potential Impact:**
An attacker may execute JavaScript in another user's browser
through vulnerable application content. This may allow
unauthorized page manipulation or access to data available
to the application's browser context.

**Remediation:**
- Do not trust user input as HTML.
- Avoid unsafe HTML rendering functions.
- Use safe text rendering and context-aware output encoding.
- Sanitize HTML when rich HTML content is genuinely required.