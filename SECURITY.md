# Security and safe handling

This repository may contain third-party code that has not been fully audited.

- Never commit API keys, access tokens, passwords, private keys, Telegram sessions, or personal data.
- Store credentials locally in environment variables or an untracked configuration file.
- Do not run unknown scripts or install dependencies before reviewing their source and install hooks.
- Review network requests, subprocess/command execution, file access, persistence mechanisms, and dependency provenance.
- Test untrusted code in a disposable, isolated environment without access to personal files or accounts.
- Do not assume that a clean archive scan proves the project is safe.
- Report suspected vulnerabilities responsibly and do not use the software to access systems or data without authorization.

## Upload note

Only add source files and archives that you have the right to redistribute. Include the original project's license and attribution where applicable.
