# Lab 01 — iOS App Permission & Privacy Assessment

**Status:** Procedure ready; observations pending  
**Duration:** Approximately 45 minutes  
**Scope:** Visible iOS settings and behavior of a harmless test app

## Research question

How can an iPhone owner inspect and restrict camera, microphone, location, and tracking access, and what changes in app behavior after a permission is removed?

## Consumer takeaway

Permissions should be limited to functions you actually use. **A granted permission is not proof that an app misused personal data.** Reducing access can affect app features, so record the trade-off.

## Prerequisites

- Personally owned, unmanaged iPhone with a current supported iOS version.
- A trusted test app using non-sensitive test data.
- No employer accounts, personal identifying screenshots, or real private messages.

## Procedure

1. Record device model, iOS version and test date; omit serial numbers and account identifiers.
2. Open **Settings → Privacy & Security**.
3. Open **Camera** and inspect one chosen test app; note its initial setting.
4. Change the permission to a more restrictive available state. Open the app and test its camera feature; record what happens.
5. Repeat for **Microphone** and **Location Services** using suitable test apps. Available choices vary.
6. Review **Tracking** separately; tracking requests are not equivalent to camera/microphone sensor access.
7. If available, review **App Privacy Report**. It may require enabling it before activity data appears, and does not replace permission settings.
8. Restore any settings needed for normal use and record the rollback.

## Observations — fill only after testing

| Control | Initial state | Changed state | App behavior | Redacted evidence |
|---|---|---|---|---|
| Camera | Pending | Pending | Pending | Pending |
| Microphone | Pending | Pending | Pending | Pending |
| Location | Pending | Pending | Pending | Pending |
| Tracking | Pending | Pending | Pending | Pending |

## Analysis prompts

1. Which choices were actually available on the tested OS version?
2. Did restriction alter the app's function or prompt behavior?
3. What could App Privacy Report show, if enabled?
4. Which potential privacy risks do unnecessary permissions create?
5. What does this test **not** establish—for example, actual data exfiltration, app code security, or overall iOS security?

## GRC exercise

| Field | Initial hypothesis; validate against your evidence |
|---|---|
| Risk | Excessive access may increase exposure of sensitive information |
| Objective | Limit app access to legitimate use |
| Control | Periodically review and restrict unnecessary permissions |
| Owner | User; administrator for enterprise-managed policy |
| Evidence | Redacted before/after settings and repeatable observations |
| Residual risk | Necessary access can still involve data processing |

Complete [the observation template](../templates/lab-observation.md) and [risk/control record](../templates/risk-control-record.md). This is educational testing, not a NIST or OWASP compliance attestation.

## Official references

- [Apple — Control what you share](https://support.apple.com/en-euro/guide/iphone/iph6e7d349d1/ios)
- [Apple — Control access to app information](https://support.apple.com/en-mide/guide/iphone/iph251e92810/ios)
- [Apple Platform Security](https://support.apple.com/guide/security/welcome/web)

Source review: 2026-11-09. Confirm menus against your current installed OS.
