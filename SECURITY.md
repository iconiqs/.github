# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in any iconiqs repository, please do **not** open a public GitHub issue.

Instead, please report it privately via GitHub's built-in security advisory feature:
1. Go to the affected repository on GitHub
2. Click **Security** → **Advisories** → **Report a vulnerability**

We will acknowledge your report within 48 hours and aim to release a fix within 14 days for critical issues.

## Supported Versions

Only the latest version on the `main` branch is actively maintained and receives security updates.

## Security Best Practices for Contributors

- Never commit secrets, API keys, tokens, or credentials
- Use environment variables or GitHub Secrets for sensitive values
- Keep dependencies up to date (Dependabot alerts are enabled)
- Review third-party dependencies before adding them
