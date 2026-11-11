# OSIEL Labs — GitHub organization setup checklist

This document distinguishes configuration committed in `.github` from organization-level settings requiring an owner in GitHub's web UI.

## Organization profile

- The public `OSIEL-Labs/.github` repository hosts `profile/README.md`.
- Verify that https://github.com/OSIEL-Labs renders the profile.
- Confirm that repository visibility and public-facing claims match intended disclosure.

## Organization settings (owner action)

- **Display name:** OSIEL Labs.
- **Description (suggested):** Engineering modular, extensible and dependable enterprise software. Building the foundations of OSIEL.
- **Website:** Set only when an official verified site is available.
- **Email:** Set only when a public, monitored organization contact exists.
- **Location:** Optional; choose whether organizational location should be public.
- **Avatar:** Upload an approved OSIEL Labs visual identity.
- **Pinned repositories:** Pin suitable public repositories once available.
- **Member permissions:** Use least privilege and require two-factor authentication where appropriate.
- **Repository defaults:** Configure branch protection or rulesets, review policy and security scanning.
- **Security reporting:** Enable private vulnerability reporting where available and establish a monitored private reporting contact.
- **Discussions:** Enable only where active moderation and maintenance are planned.

## Before publishing code

- Decide each repository's license explicitly; do not attach an open-source license by default.
- Add a repository-specific README and declared maturity.
- Check for proprietary research, credentials, internal documentation and customer data.
- Assign maintainers and define tests, release expectations and support status.
- Set topics, homepage and description for each repository when supported.

## Maintenance

Review the organization profile and shared community defaults as projects become public. Project-specific policies take precedence.
