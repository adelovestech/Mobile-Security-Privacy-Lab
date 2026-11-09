# Lab 01 — App permissions on iOS and Android

**Status:** Procedure published; device observations pending  
**Audience:** Phone owners, junior security analysts, privacy/GRC learners  
**Estimated time:** 30–45 minutes per platform

## Consumer takeaway

An app's permission to access your camera, microphone, contacts, or location deserves periodic review. **A granted permission is not proof that an app misused data.** Evaluate whether the access supports a feature you actually use, and select the least access consistent with your needs.

## Question and scope

How can a user **view and change** permissions for a test app on iOS and Android? This lab tests visible settings and their changes, **not** covert data collection, app source code, network traffic, or platform exploit resistance.

## Prerequisites

- Your own iPhone and Android phone, both on supported OS versions.
- A harmless test application that requests a permission, or an existing app whose functions you understand.
- No employer-managed apps, accounts, or devices.
- A private scratch note for raw observations; publish only sanitized summaries.

## Procedure A — iPhone

1. Record the iPhone model and iOS version (omit serial number and Apple Account information).
2. Open **Settings → Privacy & Security**.
3. Choose a permission category such as **Camera**, **Microphone**, or **Location Services**.
4. Note which test apps appear and their displayed permission states; **do not capture a full personal app inventory**.
5. For a chosen test app, change the permission to a more restrictive available setting.
6. Open the test app and note whether a relevant feature still works or asks again for access.
7. If needed, restore the initial permission and record the rollback.

Apple also documents **App Privacy Report** for viewing certain data/sensor access and network activity. It is a different view from the permission-grant screen and may require enabling it before data accumulates.

## Procedure B — Android / Samsung

1. Record the Android version, Samsung software version if applicable, and device model; omit identifiers.
2. Open **Settings → Security and privacy → Privacy → Permission manager** if available. Exact labels can differ on Samsung builds; use Settings search for **Permission manager** if needed.
3. Select **Camera**, **Microphone**, or **Location** and review the test app's displayed state.
4. Set the test app to a more restrictive available permission option.
5. Open the app, use a relevant feature, and record whether it works or prompts for permission.
6. Review **Privacy Dashboard** where available to distinguish recent permission usage from current grants.
7. Restore the initial permission if necessary and note the rollback.

Google's documentation describes Permission manager and Privacy Dashboard; Samsung's UI may not match Google's illustrations exactly.

## Evidence table — fill after testing

| Test field | iOS observation | Android observation |
|---|---|---|
| Device/OS version | _Pending_ | _Pending_ |
| Test app (generic descriptor) | _Pending_ | _Pending_ |
| Permission tested | _Pending_ | _Pending_ |
| Initial state | _Pending_ | _Pending_ |
| Changed state | _Pending_ | _Pending_ |
| App behavior after change | _Pending_ | _Pending_ |
| Recent access visibility | _Pending_ | _Pending_ |
| Evidence image path | _Pending/redacted only_ | _Pending/redacted only_ |

## Analysis prompts

1. Did both phones offer a way to change the test permission? What was different?
2. Was the app behavior consistent with the displayed permission state?
3. Did either interface show **recent usage** separately from permission status?
4. What guidance would you give a nontechnical family member?
5. What is not proven by this lab (for example: actual data exfiltration or comparative platform exploitability)?

## Risk/control interpretation

- **Risk scenario:** Excessive app access increases the potential exposure of sensitive device data if an app misbehaves or is compromised.
- **User control:** Review and limit app permissions; uninstall apps that no longer serve a purpose.
- **Evidence:** Time-stamped, redacted settings observations plus reproducible procedure.
- **Limitation:** Device-level permission reviews are not a substitute for enterprise MDM, application assurance, or threat detection.

Use [the risk/control template](../templates/risk-control-record.md) to formalize this assessment. NIST SP 800-124 Rev. 2 provides enterprise mobile security context; OWASP MASVS applies specifically to app-security verification, so do not claim this small settings exercise verifies MASVS compliance.

## Official references

- [Apple — Control what you share on iPhone](https://support.apple.com/en-euro/guide/iphone/iph6e7d349d1/ios)
- [Apple — Control access to information in apps](https://support.apple.com/en-mide/guide/iphone/iph251e92810/ios)
- [Google — Change Android app permissions](https://support.google.com/android/answer/9431959)
- [Google — Privacy Dashboard](https://support.google.com/android/answer/13530434)

**Last source review:** 2026-11-09. Validate steps on your own OS builds before marking the lab complete.

