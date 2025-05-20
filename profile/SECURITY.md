# Security Policy

We take the security of our users and systems seriously. If you discover a vulnerability, please report it responsibly.

## 📨 Contact

Email us at: [security@hacken.io](mailto:security@hacken.io)  

## 🎯 Scope

The table below lists the assets that are officially **in scope** for security testing and are eligible for rewards under this program.

Any vulnerabilities reported on **out-of-scope (❌)** assets will be **ignored**, regardless of their nature or potential impact. We do not evaluate, acknowledge, or pay for issues found outside the defined scope.

If you're unsure whether a target is in scope, please contact us at [security@hacken.io](mailto:security@hacken.io) **before starting any testing**.


| Asset / Application                                                                 | Scope | Type    | Severity     | Rewards | Notes                                   |
|--------------------------------------------------------------------------------------|-------|---------|--------------|---------|-----------------------------------------|
| `*.hacken.io`                                                                        | ✅    | Web     | Medium–Critical | ✅      | Main corporate site and subdomains      |
| [HAI Android App](https://play.google.com/store/apps/details?id=com.hackenai.hackenaiapp) | ✅ | Mobile  | Medium–Critical | ✅      | Official Android app                    |
| [HAI iOS App](https://apps.apple.com/us/app/hai-by-hacken/id1501384789)             | ✅    | Mobile  | Medium–Critical | ✅      | Official iOS app                        |
| `*.hacken.ai`                                                                        | ❌    | Web     | Any           | ❌      | Out of scope — separate project         |
| `*.trustarmy.com`                                                                    | ❌    | Web     | Any           | ❌      | Out of scope — separate project         |
| `*.extractor.live`                                                                   | ❌    | Web     | Any           | ❌      | Out of scope — separate project         |
| Third-party services or platforms not owned by Hacken                                | ❌    | Web/API | Any           | ❌      | Includes cloud/SaaS infrastructure      |
| Assets not explicitly listed above                                                   | ❌    | Any     | Any           | ❌      | Treated as out of scope by default      |


## ✅ Qualifying Vulnerabilities

We are interested in:

- Business logic issues
- Payments manipulation
- Remote code execution (RCE)
- Injection vulnerabilities (SQL, XXE)
- File inclusions (LFI/RFI)
- Access Control Issues (IDOR, Privilege Escalation)
- Information leakage
- SSRF
- CSRF
- XSS
- Directory traversal
- Open redirects
- Other high-impact vulnerabilities

## 🚫 Out of Scope (Non-qualifying findings)

Unless exceptional, the following are not eligible:

- Third-party apps/assets
- Best practice issues
- Outdated software notices without POC
- Automated scanner reports
- Low-impact DoS/Spam
- Social engineering or phishing
- Vulnerabilities needing outdated browsers
- Missing HTTP headers
- Clickjacking, self-XSS, or error messages
- Theoretical or no-impact issues

## 💰 Bounty Rewards

We offer monetary rewards for valid, high-impact vulnerability reports.

- Bounty amounts are determined on a case-by-case basis.
- Factors include severity, business impact, quality of the report, and exploitability.
- Only submissions that meet all program requirements will be eligible for rewards.

Note: All rewards are issued at our sole discretion.

## 🧭 Rules

- No DoS, spam, or scanner floods
- Do not access or alter others' data
- Localize tests to your own account
- Report responsibly and only through approved channels
- Don’t publicly disclose issues without permission
- All tests must stay within defined scope

## 🤝 Eligibility

To receive a bounty:

- Report only in-scope valid bugs
- Submit within 24h of discovery
- Include clear, reproducible steps with POC

## 📝 How to Report a Vulnerability

If you discover a vulnerability affecting Hacken services or applications in scope, please follow the steps below:

1. **Send your report to:**  
   [security@hacken.io](mailto:security@hacken.io)  
   Please include:
   - A clear and concise description of the issue
   - Step-by-step instructions to reproduce it
   - Impact analysis (what an attacker could achieve)
   - Any relevant proof-of-concept code, screenshots, or logs

2. **Await validation from our security team**  
   We will review your report to assess its validity and severity.  
   If additional information is needed, we may contact you for clarification.

3. **Receive confirmation**  
   If the issue is confirmed and considered in-scope, we will notify you and proceed with internal classification.

4. **Reward decision**  
   The bounty amount (if applicable) will be determined based on impact, severity, and report quality — all at our discretion.

5. **Payment coordination**  
   If eligible for a bounty, our finance team will reach out to coordinate payment through your preferred channel (subject to compliance and verification).


Thank you for helping us keep Web3 secure.

