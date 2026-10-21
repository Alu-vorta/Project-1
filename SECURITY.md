# Security Policy

## Supported Versions

Only the latest version of this site, live at [11project1.netlify.app](https://11project1.netlify.app) and on the `main` branch, receives security fixes.

| Version | Supported |
|---------|-----------|
| Latest (`main`) | ✅ |
| Older commits | ❌ |

## Reporting a Vulnerability

If you find a security issue in this project, please **don't open a public issue**.

Instead, report it privately in one of these ways:

- **GitHub:** use the **"Report a vulnerability"** button in this repository's **Security** tab
- **Email:** [armanashab69@gmail.com](mailto:armanashab69@gmail.com)

Please include:
- what the issue is and where you found it
- the steps to reproduce it
- the possible impact

I'll try to reply within **3 days** and fix confirmed issues as soon as I can. Thank you for helping keep this project safe! 🔒

## Security Measures in This Project

- Static site with no backend, no database and no stored user data
- Security headers (CSP, anti-clickjacking, HTTPS-only) set through Netlify's `_headers` file
- No API keys, passwords or secrets stored in the repository
- `.gitignore` blocks common secret files (such as `.env`) from being committed
