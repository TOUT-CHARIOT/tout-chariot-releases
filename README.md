# Tout Chariot Android releases

## Latest: shareholder demonstration 1.3

[Download Tout Chariot Demo 1.3.0 (APK)](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/download/v1.3.0-qa/Tout-Chariot-1.3.0-hosted-demo.apk) · [Release notes and verification](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/tag/v1.3.0-qa)

Android 7.0 or newer; universal APK for arm64-v8a, armeabi-v7a and x86_64. Internet access is required; no local server is needed. The app connects to the hosted HTTPS backend.

**Installation:** the launcher name is **Tout Chariot Demo**. It installs alongside the earlier 1.2 app, avoiding an update-signature conflict. Do not uninstall the previous app.

**Sign in with the demonstration credentials supplied privately by the project owner.** OTP 1234 is restricted to authorized test accounts. Signup with other phone numbers is not enabled.

### Available flows

- National: Transport, Labor (Main-d’œuvre), Location. Location replaces Dépannage for new requests.
- International: International moving and International transport.
- Eleven cart categories, including Plateau and Semi-remorque.
- Admin-managed plans, versioned quotes, options, conditional minimums and rental availability.
- Provider arrival proposal, customer confirmation, job execution and history.
- Rider/provider chat, Firebase notifications and a five-tab provider workspace.

All five hosted service workflows were checked through completion, including persisted chat and payment guards. The Android demo-package test verified rental confirmation/completion and actual Firebase push delivery. The normal release APK was also installed and signed in through its phone/password UI.

### Demonstration limits

Carts and prices are demonstration configurations. PI-SPI remains in sandbox; real payer-approved settlement is not claimed. General public SMS signup and production store signing are not configured. This is a demonstration prerelease, not a commercial production release.

[SHA-256 checksums](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/download/v1.3.0-qa/SHA256SUMS.txt) · [Verification report](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/download/v1.3.0-qa/VERIFICATION.md)

## Previous version

[Android QA 1.2](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/tag/v1.2.0-qa) is retained for reference. The APK stored at the repository root is an older build; use the latest release link above for the hosted demonstration.

