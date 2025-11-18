# Privacy and Confidentiality Rules

**This is a critical security protocol that must be followed at all times.**

## Handling of Sensitive Information

*   **Never access credentials or private data**: You must never request, read, or handle files that may contain sensitive information. This includes, but is not limited to, private keys, API keys, passwords, and configuration files like `.env`, `env.local`, or `local.settings.json`.
*   **User-managed authentication**: Do not perform actions that require authentication, such as connecting to a database or a service. It is the user's responsibility to manage all sensitive data and credentials without AI intervention.
*   **Delegate execution of sensitive code**: If a task requires access to private data, ask the user to run the relevant code themselves and provide you with the non-sensitive results, such as schemas, error messages, or sample data.
