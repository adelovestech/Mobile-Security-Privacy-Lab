# Mobile Security & Privacy Lab

**Practical iOS and Android privacy education backed by reproducible security observations.**

> Status: public portfolio starter · First lab: ready to execute · Last reviewed: 2026-11-09

This project helps everyday phone users understand privacy settings while demonstrating a structured, evidence-based approach to mobile security review. It covers **consumer guidance**, **hands-on device labs**, and **risk/control analysis** relevant to cybersecurity, privacy, and GRC.

## Start here

1. Read [Lab 01: App permission audit](labs/01-app-permission-audit.md).
2. Run the steps on a **personal test device** with a non-sensitive test app.
3. Record results in a copy of [the observation template](templates/lab-observation.md).
4. Replace screenshot placeholders only with **redacted images you captured**.
5. Publish findings as observations, not claims that one platform is inherently secure or insecure.

## What you'll learn

| Track | Consumer question | Technical evidence |
|---|---|---|
| Permissions | Which apps can use my camera, microphone, or location? | Permission inventory and observed controls |
| Privacy visibility | Can I see recent data access? | Platform-specific dashboard/report observations |
| Device hardening | Which protections should I enable? | Reproducible configuration checklist |
| Mobile threats | What might phishing or risky apps do? | Threat-model notes and safe demonstrations |
| Governance | How should an organization manage device risk? | Risk, control, evidence, and residual-risk mapping |

## Repository map

```text
mobile-security-privacy-lab/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── SECURITY.md
├── .gitignore
├── roadmap/6-week-plan.md
├── labs/01-app-permission-audit.md
├── guides/phone-privacy-quickstart.md
├── templates/lab-observation.md
├── templates/risk-control-record.md
└── references/sources.md
```

## Method

Each lab separates **vendor-documented behavior**, **direct observation**, **risk interpretation**, and **recommendation**. Capture device model, OS version, test date, and configuration in a sanitized observation record. UI labels may vary across versions or manufacturers.

The NIST guidance in this repository discusses **enterprise mobile device management**; it is not a certification or endorsement of these consumer settings. OWASP MASVS is primarily a **mobile application security verification** standard, not a universal checklist for handset settings.

## Ethical boundaries

- Only inspect devices, apps, accounts, and networks you own or are authorized to test.
- No credential harvesting, malware deployment, unauthorized interception, or third-party account testing.
- Do not publish account names, device identifiers, phone numbers, GPS coordinates, notification contents, or access tokens.
- Keep professional work devices, employer data, and confidential policies completely out of this repository.
- Screenshots and lab results are **not yet supplied**. Do not represent the templates as completed testing.

## Six-week publishing path

See [the roadmap](roadmap/6-week-plan.md) for weekly deliverables and acceptance criteria.

## Source material

Official Apple and Google support documentation, [NIST SP 800-124 Rev. 2](https://csrc.nist.gov/pubs/sp/800/124/r2/final), and [OWASP MASVS](https://mas.owasp.org/MASVS/) are listed in [references](references/sources.md). Product interfaces change; recheck official documentation before each update.

## Portfolio note

This is an independent educational project, not affiliated with Apple, Google, Samsung, NIST, OWASP, or any employer. Statements about risks are educational interpretations unless a reproducible observation is attached.

