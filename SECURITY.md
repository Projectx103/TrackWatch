# Security Policy

## Supported Versions

We currently support the following versions of TrackWise with security updates:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

We take the security of TrackWise seriously. If you discover a security vulnerability, please follow these steps:

### 🔒 How to Report

**Please DO NOT create a public GitHub issue for security vulnerabilities.**

Instead, report security issues by emailing:

📧 **molinajefferson001@gmail.com**

### What to Include

Please include the following information in your report:

- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact of the vulnerability
- Any suggested fixes (if available)
- Your contact information

### Response Timeline

- **Initial Response**: Within 48 hours of report
- **Status Update**: Within 7 days
- **Fix Timeline**: Critical issues within 30 days, others within 90 days

### What to Expect

1. We will acknowledge receipt of your vulnerability report
2. We will investigate and validate the issue
3. We will work on a fix and keep you updated
4. Once fixed, we will publicly acknowledge your contribution (if you wish)

## Security Measures

### Authentication
- Firebase Authentication with email/password
- Password reset functionality
- Session management with unique session IDs
- Single device login enforcement

### Authorization
- Role-based access control (Admin, Team Leader, User, Requester)
- Account approval system
- Firestore security rules

### Data Protection
- All data encrypted in transit (HTTPS)
- Secure password storage via Firebase
- Session tokens stored securely

## Known Limitations

- Client-side role validation (server-side validation recommended)
- No rate limiting on login attempts (to be implemented)
- No two-factor authentication (planned for future release)

## Best Practices for Users

1. **Use Strong Passwords**: Minimum 8 characters with mix of letters, numbers, and symbols
2. **Don't Share Credentials**: Never share your login information
3. **Logout When Done**: Always logout when using shared computers
4. **Report Suspicious Activity**: Contact admin immediately if you notice unusual behavior
5. **Keep Browser Updated**: Use the latest version of your web browser

## Security Updates

Security updates will be announced via:
- GitHub repository releases
- Email notifications to registered users
- System notifications on login page

## Compliance

This project follows:
- OWASP Top 10 security guidelines
- Firebase security best practices
- Industry-standard authentication protocols

## Contact

For security concerns or questions:
- 📧 Email: molinajefferson001@gmail.com


---

**Last Updated**: January 13, 2026
