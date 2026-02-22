# Security Policy

## Supported Versions

SEAO is currently in early development. Security fixes will be applied to the latest active branch.

| Version | Supported |
|---------|-----------|
| main    | ✅ Yes    |
| older branches | ❌ No |

---

## Reporting a Vulnerability

If you discover a security vulnerability, please report it responsibly.

### Preferred Reporting Method
Please open a **private security report** (if enabled on GitHub), or contact the maintainer directly before creating a public issue.

If private reporting is not available, do **not** publish exploit details publicly. Instead, open a minimal issue stating that you found a security concern and need a private channel.

---

## What to Include in a Report

Please include as much of the following as possible:

- Vulnerability type (e.g., command injection, auth bypass, secret leak)
- Affected file/module/feature
- Steps to reproduce
- Proof of concept (if safe to share)
- Expected vs actual behavior
- Impact assessment
- Suggested fix (optional)

---

## Response Timeline (Target)

SEAO aims to follow this response process:

- **Acknowledgement:** within **48-72 hours**
- **Initial triage:** within **5 business days**
- **Fix plan / status update:** within **7-14 days**, depending on severity
- **Patch release:** timeline depends on complexity and project phase

> Note: During early-stage development, timelines may vary, but all legitimate reports will be taken seriously.

---

## Responsible Disclosure

Please follow responsible disclosure practices:

- Do not publicly disclose details before a fix is available
- Do not access or modify data beyond what is necessary to demonstrate the issue
- Do not perform destructive testing or denial-of-service attacks
- Do not attempt social engineering, phishing, or physical attacks

---

## Security Priorities for SEAO

Because SEAO is a security-governed agent runtime, the project especially prioritizes:

- Prompt injection resistance
- Tool execution safety
- Secret redaction and leakage prevention
- Policy enforcement integrity
- Audit log tamper resistance

---

## Scope

This policy applies to:

- Source code in this repository
- Local runtime behavior
- Agent tool execution framework
- Security and governance modules

Third-party dependencies are out of scope, but reports about risky dependency usage are welcome.

---

Thank you for helping make SEAO safer and more trustworthy.
