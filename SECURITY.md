# Security Policy

## Reporting a vulnerability

Do not disclose security vulnerabilities, credentials, tokens, customer data, private infrastructure details, or other sensitive information in a public issue.

Report security-sensitive findings to an HY-Intelligence organization owner through an existing private communication channel. Include the affected repository or component, impact, reproduction steps, and any relevant logs with secrets removed.

If a repository provides more specific security reporting instructions, follow that repository's policy instead.

## Sensitive material

Before committing or attaching files, verify that they do not contain:

- credentials, API keys, tokens, or private certificates,
- customer or personal data,
- proprietary imagery or datasets without redistribution rights,
- internal hostnames, filesystem paths, or infrastructure details that should remain private,
- confidential third-party source code or binaries.

If sensitive information is committed accidentally, treat credential rotation or other containment as the first priority; deleting the visible file alone may not remove it from Git history.
