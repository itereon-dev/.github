# Security policy

This policy applies to every public repository of the itereon organisation. Our
software may handle wallet keys and place real orders. If you find a way to weaken
that (key exposure, order manipulation, bypassing risk limits, a tampered update, or
any other vulnerability), we want to know **privately, first**.

## Reporting

- Preferred: use **Report a vulnerability** on the affected repository's *Security*
  tab (GitHub private vulnerability reporting; only maintainers see it). For POLYDESK
  clicktrader: [report here](https://github.com/itereon-dev/polydesk-clicktrader-releases/security/advisories/new).
- Or email **admin@itereon.eu** with "SECURITY" in the subject.

Please include the product and version, your operating system, and steps to
reproduce. **Do not include private keys, API tokens, or wallet addresses.** Describe
the issue, do not demonstrate it with your own credentials.

Please do **not** open a public issue for security problems.

## What to expect

- Acknowledgement within 3 business days.
- We keep you informed while we investigate and fix, and credit you in the release
  notes if you wish.
- Fixes ship as a regular release. Installed POLYDESK apps receive them via the
  built-in, signature-verified updater.

## Scope

- Software published by itereon GmbH, including the POLYDESK clicktrader desktop
  application and the trading engine bundled inside it.
- Our update service and the integrity of published installers (every release carries
  `SHA256SUMS.txt`; updates are verified against a signing key embedded in the app).

Out of scope: third-party platforms, APIs and smart contracts (for example
Polymarket's own systems). Please report those to the respective operator.
