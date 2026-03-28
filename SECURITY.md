# Security Policy

## Supported Versions

| Version | Supported          |
|---------|--------------------|
| latest  | ✅                 |
| < latest | ⚠️ Best effort    |

## Reporting a Vulnerability

**Do NOT open a public issue for security vulnerabilities.**

Instead, please report them via:
- GitHub Security Advisories (preferred): Use the "Security" tab → "Report a vulnerability"
- Email: Create a private issue on GitHub

## Response Time

- **Critical/High:** 24-48 hours
- **Medium:** 1 week
- **Low:** 2 weeks

## Automated Security

This repository uses:
- ✅ GitHub CodeQL analysis
- ✅ Dependabot security updates
- ✅ Secret scanning
- ✅ Dependency review on PRs
- ✅ Automated SAST via Bandit (Python repos)

## Security Best Practices

- All dependencies are pinned to specific versions
- Automated dependency updates via Dependabot
- CI/CD pipeline includes security scanning
- Branch protection requires PR reviews
