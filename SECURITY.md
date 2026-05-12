# Security Policy

## Reporting a Vulnerability

The DiCRA team takes the security of our platform and datasets seriously. We appreciate your efforts to responsibly disclose your findings.

**Please do NOT report security vulnerabilities through public GitHub issues.**

### How to Report

Send an email to **support@dicra.org** with the subject line: `[SECURITY] DiCRA Vulnerability Report`

Include the following information:

- Type of issue (e.g., SQL injection, cross-site scripting, authentication bypass, data exposure)
- Full paths of source files related to the issue
- Location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

### What to Expect

- **Acknowledgement** within 3 business days
- **Initial assessment** within 7 business days
- **Regular updates** on our progress at least every 14 days
- **Coordinated disclosure** once a fix is available

### Scope

Security reports are welcome for:

- All code in the `dicra-commons` GitHub organization
- The DiCRA platform (hosted services)
- Public APIs and SDKs

### Out of Scope

- Vulnerabilities in third-party dependencies (please report to upstream maintainers)
- Social engineering attacks
- Physical security issues
- Denial of service attacks

## Supported Versions

DiCRA 2.0 is currently under active development. Security updates are provided for:

| Version | Supported |
|---------|-----------|
| 2.x (current) | ✅ |
| 1.x (legacy) | ⚠️ Critical fixes only |

## Recognition

We maintain a Security Hall of Fame to recognize researchers who have responsibly disclosed vulnerabilities. With your permission, we will add your name once the vulnerability is fixed and publicly disclosed.

Thank you for helping keep DiCRA and its users safe.
