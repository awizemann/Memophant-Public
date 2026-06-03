# Security policy

## Reporting a vulnerability

Please **do not** file security issues in the public tracker. Instead:

- **Email:** [security@memophant.co](mailto:security@memophant.co)
- Include: a clear description, affected Memophant + macOS versions, and
  reproduction steps. A proof-of-concept is welcome but not required.

## What to expect

- Acknowledgement within **5 business days** of your report.
- A working timeline for triage and fix within **15 business days**.
- Credit in the release notes when the fix ships, unless you prefer to remain
  anonymous.

## Scope

Memophant is a native macOS app distributed direct from
[memophant.co](https://memophant.co). In-scope:

- The Memophant app binary (.app, .dmg)
- Anything Memophant writes to your repository (`.memory/`, `wiki/`, `design/`,
  `code/`, `sessions/`, `TASKS.md`)
- The licensing webhook at `https://memophant.co/api/paddle-webhook` and the
  recovery endpoint at `https://memophant.co/api/recover-license`
- The auto-update mechanism (Sparkle, Ed25519 signatures, the appcast feed)

Out of scope:

- Issues that require physical access to an unlocked Mac the user has already
  logged into
- Social engineering of the developer or support staff
- Third-party services Memophant uses (Paddle, Resend, Neon, Vercel, GitHub)
  — report those to the respective vendor

## Coordinated disclosure

We follow standard 90-day coordinated disclosure. If the issue is widely
exploitable in the wild already, we'll fix and disclose faster.
