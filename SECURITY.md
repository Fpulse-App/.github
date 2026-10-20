# Security Policy

F-Pulse App takes the security of our service and our users' data seriously.
Thank you for helping keep F-Pulse App and its users safe.

## Supported Versions

| Product | Supported version |
| ------- | ----------------- |
| fpulse.app (hosted dashboard, REST API, feedback widget) | Always the current version |
| Mac desktop app | 1.0.5 and later :white_check_mark: · older versions :x: |
| WordPress plugin | 1.0.x :white_check_mark: |
| iOS / macOS SDK ([ztuskes/feedbackPulse](https://github.com/ztuskes/feedbackPulse)) | Latest release :white_check_mark: |
| Code examples ([fpulse-examples](https://github.com/Fpulse-App/fpulse-examples)) | `main` branch :white_check_mark: |

Security fixes for the hosted service are deployed for everyone at once. For the
desktop app, WordPress plugin and SDK, please update to the latest version.

## Reporting a Vulnerability

**Please do not open a public GitHub issue for security problems.**

Report it privately in one of these ways:

- Email **support@fpulse.app** with the subject "Security"
- Or use GitHub's **"Report a vulnerability"** button in the Security tab of the repository

Please include:
- What the problem is and where (URL, endpoint, app or plugin version)
- Steps to reproduce it, or a proof of concept
- The impact you think it has

### What to expect

- **Within 3 business days:** we confirm we received your report.
- **Within 7 days:** our first assessment, and whether we accept the issue.
- **While we work on it:** an update at least every 7 days.
- **Accepted:** we fix it as fast as we can (critical issues first), tell you when
  it is fixed, and credit you in the release notes if you want.
- **Declined:** we explain why, for example when it is out of scope or not exploitable.

Please give us a reasonable time to fix the issue before you share it publicly.

## Scope

In scope: fpulse.app and api.fpulse.app, the feedback widget, the REST API,
the Mac desktop app, the WordPress plugin, the iOS/macOS SDK and the code in this organization.

Out of scope:
- Denial of service, load testing or spam (including through the contact form)
- Social engineering or phishing of our team or users
- The public demo account (`demosite@fpulse.app`). It is shared on purpose and read-only.
- Reports from automated scanners without a working proof of impact
- Missing security headers or best practices with no real way to exploit them

## Safe Harbor

We will not take legal action against research done in good faith that follows
this policy, avoids privacy violations and service disruption, and only uses
your own accounts or the demo account.
