# Security Policy — TwitchLift Twitch View Bot

## Supported Versions

| Version | Supported |
|---------|-----------|
| 2.5.x   | ✅ Current |
| 2.4.x   | ✅ Security fixes |
| 2.3.x   | ⚠️ End of life |
| < 2.3   | ❌ No longer supported |

## Reporting a Vulnerability

If you discover a security vulnerability in TwitchLift's Twitch viewer bot service, please report it responsibly:

1. **DO NOT** create a public GitHub issue for security vulnerabilities
2. Email us at: **security@twitchlift.com**
3. Or contact us via Telegram: [@twitchlift](https://t.me/twitchlift)

### What to Include
- Description of the vulnerability
- Steps to reproduce
- Potential impact assessment
- Suggested fix (if any)

### Response Timeline
- **Initial Response:** Within 24 hours
- **Status Update:** Within 72 hours
- **Fix Deployment:** Within 7 days for critical issues

## Security Measures

TwitchLift implements the following security measures for our Twitch view bot:

- **HTTPS/TLS** encryption for all data in transit
- **Bcrypt** password hashing with per-user salts
- **CSRF** protection on all form submissions
- **Rate limiting** on authentication and API endpoints
- **No credential storage** — we never store Twitch passwords
- **Automatic session expiration** for inactive accounts
- **IP-based abuse prevention** for trial system
- **Encrypted webhook** verification for payment processing

## Responsible Disclosure

We appreciate security researchers who help keep TwitchLift safe. Responsible disclosure of vulnerabilities will be acknowledged in our changelog.
