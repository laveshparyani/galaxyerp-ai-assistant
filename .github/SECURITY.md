# Security Policy

## Supported versions

This is a portfolio/bootcamp project. Only the latest version on the `main` branch is maintained.

| Version | Supported |
|---------|:---------:|
| Latest (`main`) | Yes |
| Older commits | No |

## Reporting a vulnerability

Please **do not open a public issue** for security problems.

Instead, use GitHub's private reporting:

1. Go to the [Security tab](https://github.com/laveshparyani/galaxyerp-ai-assistant/security).
2. Click **Report a vulnerability**.
3. Describe the issue, steps to reproduce, and potential impact.

You can expect an acknowledgement within a few days. Thank you for helping keep the project safe.

## Notes on this project

GalaxyERP AI Assistant is a static landing page served by a small Flask app (and hostable on GitHub
Pages). The conversational "ERP Buddy" is a **Dialogflow Messenger** widget embedded client-side that
talks to a Google Cloud (Vertex AI Agent Builder) agent; the web app itself stores no user data and
has no server-side database. The JavaScript is scanned by CodeQL on every push.
