# Security Policy

## 🛡️ Supported Versions

We actively maintain security for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| Latest (main branch) | ✅ |
| Previous releases    | ❌ |

**Note**: As an open-source educational tool, we recommend always using the latest version from the main branch for the most up-to-date security patches.

## 🚨 Reporting a Vulnerability

We take the security of the VUSA Individual Voting System seriously. If you discover a security vulnerability, please follow these guidelines:

### ⚡ For Critical Security Issues

**Critical issues include:**
- Exposed API keys or credentials
- Authentication bypass vulnerabilities  
- Data injection attacks
- Cross-site scripting (XSS) vulnerabilities
- Access to other users' voting data

**Report immediately via:**
- **Email**: virtualgovownership@gmail.com
- **Subject**: `[SECURITY] Critical Vulnerability in VUSA Voting System`
- **Response time**: We aim to respond within 24 hours

### 📧 For Non-Critical Security Issues

**Non-critical issues include:**
- Minor information disclosure
- Low-impact authentication issues
- Potential denial of service vectors
- Configuration improvements

**Report via:**
- **GitHub Security Advisory**: [Create a private advisory](https://github.com/yourusername/vusa-voting/security/advisories/new)
- **Email**: virtualgovownership@gmail.com with subject `[SECURITY]`
- **Response time**: We aim to respond within 72 hours

## 📋 What to Include in Your Report

To help us understand and resolve the issue quickly, please include:

### Required Information
- **Vulnerability type** (e.g., XSS, injection, authentication bypass)
- **Affected component** (e.g., voting system, Google Sheets integration, authentication)
- **Steps to reproduce** the vulnerability
- **Potential impact** (who could be affected and how)
- **Suggested severity** (Critical, High, Medium, Low)

### Helpful Additional Information
- **Screenshots or proof-of-concept** (if safe to create)
- **Browser and device information**
- **Network environment** (if relevant)
- **Suggested fix** (if you have ideas)

### ⚠️ Please DO NOT Include
- **Actual exploit code** that could harm users
- **Real user data** or credentials
- **Information that could help others exploit the vulnerability**

## 🔒 Our Security Response Process

### 1. **Acknowledgment** (24-72 hours)
- We'll confirm receipt of your report
- We'll provide a tracking identifier
- We'll give an initial assessment of severity

### 2. **Investigation** (1-7 days)
- We'll reproduce the vulnerability
- We'll assess the impact and scope
- We'll develop a fix or mitigation

### 3. **Resolution** (3-14 days)
- We'll implement and test the fix
- We'll prepare a security advisory
- We'll coordinate disclosure timing with you

### 4. **Disclosure** (After fix is deployed)
- We'll publish a security advisory
- We'll credit you (if desired) for the responsible disclosure
- We'll notify users of the update

## 🏆 Recognition and Rewards

### Security Researcher Recognition
- **Public acknowledgment** in our security advisories (if desired)
- **Contributor status** in our README and GitHub
- **Priority support** for future security questions
- **Direct communication channel** for ongoing security collaboration

### What We Can't Offer
- **Monetary rewards** (we're an open-source educational project)
- **Swag or physical rewards** (no budget for this currently)
- **Legal protection** (though we won't pursue legal action for good-faith research)

## 🔍 Security Scope

### In Scope
- **Web application security** (XSS, CSRF, injection attacks)
- **Authentication and authorization** vulnerabilities
- **Data privacy** issues (especially student/educational data)
- **API security** (Google Sheets integration, OAuth flow)
- **Client-side security** (localStorage, session management)

### Out of Scope
- **Physical security** of hosting infrastructure
- **Social engineering** attacks
- **Denial of service** via excessive legitimate use
- **Issues in third-party dependencies** (report to the dependency maintainers)
- **Missing security headers** (unless they lead to actual exploitation)

## 🚫 Security Testing Guidelines

### ✅ Acceptable Testing
- **Testing on your own data** and Google Sheets
- **Using test accounts** and isolated environments
- **Analyzing client-side code** and network requests
- **Fuzzing inputs** in a controlled manner

### ❌ Prohibited Testing
- **Accessing other users' data** or sessions
- **Disrupting service** for other users
- **Automated scanning** that might impact performance
- **Testing on production educational sessions** without permission
- **Social engineering** attacks against users

## 📚 Educational Considerations

### Student Data Protection
Since this tool is used in educational settings:
- **FERPA compliance** issues are considered security vulnerabilities
- **Student privacy** breaches are treated as critical
- **Educational session isolation** failures are high priority
- **Instructor data access** problems require immediate attention

### Responsible Disclosure for Educational Tools
- **Consider academic calendar** when planning disclosure
- **Minimize disruption** to ongoing educational use
- **Provide clear guidance** for educators on security updates
- **Offer assistance** with data migration if needed

## 📞 Contact Information

### Primary Security Contact
- **Email**: virtualgovownership@gmail.com
- **PGP Key**: [Link to your PGP key if you have one]
- **Response SLA**: 24-72 hours depending on severity

### Alternative Contacts
- **GitHub Issues**: For non-sensitive security discussions
- **Project Maintainer**: randlesinc@gmail.com

### Emergency Contact
For critical vulnerabilities that pose immediate risk to user data:
- **Priority Email**: virtualgovownership@gmail.com
- **Subject Line**: `[URGENT SECURITY] [Brief Description]`

## 🔄 Security Updates

### How We Communicate Security Updates
- **GitHub Security Advisories** for documented vulnerabilities
- **Release notes** for security-related updates
- **Application notifications** for critical updates requiring user action
- **Email notifications** to known educational users (when possible)

### Staying Informed
- **Watch our GitHub repository** for security advisories
- **Follow releases** to get notifications of security updates
- **Check our README** for any security-related announcements

## ⚖️ Legal

### Safe Harbor
We support safe harbor for security researchers who:
- **Act in good faith** to identify and report vulnerabilities
- **Avoid accessing or modifying** other users' data
- **Follow responsible disclosure** practices
- **Don't violate any laws** in their security research

### Limitations
- **No legal advice**: This policy doesn't constitute legal advice
- **No warranty**: Security research is at your own risk
- **Report to appropriate authorities**: We may report illegal activities

---

## 🙏 Thank You

Security researchers who help improve the VUSA Individual Voting System make online civic education safer for everyone. Your responsible disclosure helps protect:

- **Students** learning about democratic processes
- **Educators** using technology in their classrooms  
- **Civic organizations** promoting political engagement
- **Developers** building educational technology

**Together, we're making democracy more accessible and secure.** 🏛️
