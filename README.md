# Mobile Security & Privacy Lab

**Hands-on Apple device security, data privacy, and GRC portfolio.**

> Active learning portfolio · Primary platforms: iOS, iPadOS, macOS · Updated 2026-11-09

This independent project documents practical security and privacy assessments using personally controlled Apple devices. The goal is to teach everyday users while demonstrating a repeatable security-assessment method: **scope → test → observe → evaluate risk → recommend control → document limitations**.

Long-term tracks include Apple enterprise security, BYOD, identity and access management, privacy governance, and cloud security. Android remains optional, not a requirement.

## Start here

1. Run [Lab 01: iOS App Permissions](labs/01-ios-app-permissions.md) on a personal device.
2. Record real findings using [the observation template](templates/lab-observation.md).
3. Complete [a risk/control record](templates/risk-control-record.md).
4. Publish **redacted** screenshots and evidence only after checking for private information.

## Portfolio tracks

| Track | Example work | Evidence |
|---|---|---|
| iOS security | Permissions, updates, authentication, recovery | Device observations and screenshots |
| iPadOS security | Tablet privacy settings and hardening | Reproducible device notes |
| Apple enterprise security | Managed devices, BYOD, enrollment | Architecture and control analysis |
| Privacy & GRC | Data risks, control mapping, testing | Risk register and evidence records |
| Cloud security | AWS/Azure identity and data protection | Authorized lab notes |
| Optional Android | Cross-platform comparisons | Separate, clearly scoped tests |

## Repository contents

- `labs/01-ios-app-permissions.md` — first active hands-on iPhone lab.
- `labs/01-app-permission-audit.md` — optional earlier cross-platform procedure.
- `roadmap/6-week-plan.md` — six-week Apple security/GRC learning path.
- `guides/phone-privacy-quickstart.md` — consumer guidance.
- `templates/` — reproducible observation and risk/control formats.
- `references/sources.md` — official documentation.

## Method and ethical boundaries

Only test systems, accounts, apps and devices you own or are explicitly authorized to assess. Keep work devices, employer applications, and confidential information out of the repository. Never publish account names, device identifiers, serial numbers, phone numbers, GPS coordinates, credentials, MFA codes, notification contents, or unredacted app inventories.

Distinguish **documented vendor behavior**, **direct observation**, and **your inference**. Empty templates are not completed assessments. User-facing settings checks do not prove an app is secure or demonstrate compliance with a standard.

## Standards context

- [Apple Platform Security](https://support.apple.com/guide/security/welcome/web) covers Apple security architecture.
- [NIST SP 800-124 Rev. 2](https://csrc.nist.gov/pubs/sp/800/124/r2/final) covers enterprise mobile-device management and risk.
- [OWASP MASVS](https://mas.owasp.org/MASVS/) is about mobile **application** security verification, not certification of an individual's device settings.

This is an independent educational project, not affiliated with device vendors, standards bodies, or any employer.
