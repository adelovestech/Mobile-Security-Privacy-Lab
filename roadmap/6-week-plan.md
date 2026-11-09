# Six-week publishing roadmap

Suggested cadence: **one public update per week**, 2–3 focused sessions of 30–45 minutes. Each week ends with one clear artifact—not a promise of an exhaustive security assessment.

| Week | Deliverable | Evidence to capture | Definition of done |
|---|---|---|---|
| 1 | Permission audit: iOS vs Android | Settings paths; redacted captures; versions | Complete Lab 01 and at least one observation per platform |
| 2 | Privacy visibility guide | App Privacy Report / Privacy Dashboard observations | Distinguish access history from permission grants |
| 3 | Phone hardening checklist | Screenshots of test-device controls | Consumer steps, caveats, and rollback steps |
| 4 | Mobile phishing threat model | Fictional examples and attack-path diagram | No live phishing or credential collection |
| 5 | Update and app-source hygiene | Patch status and app-source settings on test devices | Compare evidence, not unsupported security rankings |
| 6 | Risk/control crosswalk | Risk register, control owners, evidence, gaps | Explain enterprise relevance and scope limitations |

## Publication workflow

1. Create a GitHub issue named `Week N: topic` with 3–5 acceptance checks.
2. Revisit linked official sources; note date reviewed.
3. Conduct the lab on personally controlled devices and save **redacted** evidence.
4. Make a feature branch, update the Markdown and evidence, and open a pull request.
5. Self-review for reproducibility, privacy leaks, and unverified claims; then merge.

## Suggested later topics

MFA and passkeys; backup and recovery; lost-device response; app store data disclosures; enterprise BYOD trade-offs. Keep separate coverage for device settings and application security testing.

