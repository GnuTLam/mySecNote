## SCANNING - Enumeration
- Focus Scanning
- Scan non-standard entities

---

## FOOTHOLD - Stage 1
- Content Discovery
- DOM-XSS
- XSS Cross Site Scripting
- Web Cache Poison
- Host Headers
- HTTP Request Smuggling
- Brute force
- Authentication
---
## PRIVILEGE ESCALATION - Stage 2
- CSRF - Account Takeover
- Password Reset
- SQLi - SQL Injection
- JWT - JSON Web Tokens
- Prototype pollution
- API Testing
- Access Control
- GraphQL API Endpoints
- CORS - Cross-origin resource sharing
---
## DATA EXFILTRATION - Stage 3
- XXE - XML entities & Injections
- SSRF - Server side request forgery
- SSTI - Server side template injection
- SSPP - Server Side Prototype Pollution
- LFI - File path traversal
- File Uploads
- Deserialization
- OS Command Injection
---
## APPENDIX
- Focus target scanning
- Approach
- Extra Training Content

---
# Vulnerability Stages Matrix

| Category                          | Stage 1 | Stage 2 | Stage 3 |
| --------------------------------- | ------- | ------- | ------- |
| SQL Injection                     |         | ✔       | ✔       |
| [[Cross-site scripting (XSS)]]    | ✔       | ✔       |         |
| Cross-site request forgery        | ✔       | ✔       |         |
| Clickjacking                      | ✔       | ✔       |         |
| [[DOM-based vulnerabilities]]     | ✔       | ✔       |         |
| [[Cross-origin resource sharing]] | ✔       | ✔       |         |
| XML external entity (XXE)         |         |         | ✔       |
| Server-side request forgery       |         |         | ✔       |
| HTTP request smuggling            | ✔       | ✔       |         |
| OS command injection              |         |         | ✔       |
| Server-side template injection    |         |         | ✔       |
| Directory traversal               |         |         | ✔       |
| Access control vulnerabilities    | ✔       | ✔       |         |
| Authentication                    | ✔       | ✔       |         |
| Web cache poisoning               | ✔       | ✔       |         |
| Insecure deserialization          |         |         | ✔       |
| HTTP Host header attacks          | ✔       | ✔       |         |
| OAuth authentication              | ✔       | ✔       |         |
| File upload vulnerabilities       |         |         | ✔       |
| JWT                               | ✔       | ✔       |         |
