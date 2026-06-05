# Security Policy

**My Food Forest B.V.**
Last updated: June 5, 2026

We take the security of our services and our users' data seriously. We value the work of security researchers and welcome reports of vulnerabilities, in line with the [NCSC Coordinated Vulnerability Disclosure guideline](https://english.ncsc.nl/publications/publications/2019/juni/01/coordinated-vulnerability-disclosure-the-guideline).

## Reporting a Vulnerability

If you believe you have found a security vulnerability in any of our systems, please report it to:

**Email**: <security@myfoodforest.nl>

Reports may be written in **English or Dutch**. Please include:

- A description of the vulnerability and where you found it (URL, app version, repository)
- Steps to reproduce the issue (a proof of concept helps us greatly)
- The potential impact, as you assess it
- Your name/handle and contact details, so we can keep you informed (anonymous reports are accepted)

Please do **not** report security vulnerabilities through public GitHub issues.

## Scope

This policy applies to:

- The My Food Forest mobile apps (iOS and Android)
- Our APIs and backend services
- Our website at [www.myfoodforest.nl](https://www.myfoodforest.nl)
- Repositories in the [MyFoodForest](https://github.com/MyFoodForest) GitHub organization

**Out of scope:**

- Vulnerabilities in third-party services we use (Microsoft Azure, Microsoft Entra, Microsoft Forms, Mailchimp) — please report these to the vendor; do let us know as well if our configuration is affected
- Denial-of-service or volumetric attacks
- Spam, phishing, or social engineering of our team or users
- Findings without security impact (e.g. missing best-practice headers without a demonstrated exploit, version disclosure)

## Rules of Engagement

While researching, please:

- Do not access, modify, or delete data that is not your own — use test accounts where possible
- Do not go further than necessary to demonstrate the vulnerability
- Do not share the vulnerability with others until it has been resolved
- Delete any data obtained during your research once the report is resolved

## What You Can Expect From Us

- **Acknowledgement** of your report within **3 business days**
- An **initial assessment** and expected resolution timeline within **10 business days**
- Updates on our progress until the issue is resolved; we aim to resolve confirmed vulnerabilities within **90 days**
- **Credit** for your finding (with your consent) once it is fixed — we currently do not offer a monetary bug bounty
- **No legal action** against you for security research conducted in good faith and in accordance with this policy

## security.txt

A machine-readable version of this policy will be available at `https://www.myfoodforest.nl/.well-known/security.txt` (RFC 9116).

---

For non-security questions, see our [Terms and Conditions](https://github.com/MyFoodForest/.github/blob/main/TERMSANDCONDITIONS_EN.md) and [Privacy Policy](https://github.com/MyFoodForest/.github/blob/main/PRIVACY_EN.md), or contact <hello@myfoodforest.nl>.
