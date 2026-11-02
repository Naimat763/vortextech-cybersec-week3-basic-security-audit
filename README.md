# Part 1 — OWASP Juice Shop Setup & Inspection

**Learning Program:** Vortex Tech Academy  
**Environment:** Ubuntu Linux VM  
**Status:** Completed

## Description

Set up a local OWASP Juice Shop practice environment using Docker and explored the application through Firefox and OWASP ZAP.

## Tools Used

- Ubuntu Linux
- Docker
- OWASP Juice Shop
- Firefox Developer Tools
- OWASP ZAP

## Setup Commands

Download the application image:

```bash
docker pull bkimminich/juice-shop
```

Run the local practice container:

```bash
docker run -d --name juice-shop -p 127.0.0.1:3000:3000 bkimminich/juice-shop
```

Open the practice website:

```text
http://127.0.0.1:3000
```

## What I Practiced

- Docker image and container basics.
- Accessing the practice website through localhost.
- Firefox DevTools and Network inspection.
- OWASP ZAP installation and interface exploration.
- Observing HTTP and WebSocket traffic.
- Understanding the difference between HTTP responses and WebSocket messages.

## Learning Outcome

Gained practical familiarity with a local web security training environment and the tools used for initial website inspection.

## Security Scope

Testing was limited to my local OWASP Juice Shop practice environment.

## References

- https://owasp.org/www-project-juice-shop/
- https://www.zaproxy.org/
- https://developer.mozilla.org/en-US/docs/Tools

**Note:** Store only safe screenshots and test evidence. Do not upload passwords, tokens, session cookies, or other sensitive information.
