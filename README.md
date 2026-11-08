# Tout Chariot Android release

Public Android releases for Tout Chariot.

## Download

Download `Tout-Chariot-arm64-v8a-release.apk` for modern 64-bit Android phones.

## Verified flow

- Authentication and registration
- Home page and cart types
- Documentation, FAQ and address book
- Support tickets
- Account page and five-tab navigation

Build: `1.2 (2003)` using Flutter `3.22.1`

SHA-256: `965BB7BC370CD0272874A4C648C08CFC4FF758027CD0B9E39EC606005B14BBD1`

### Homepage reliability fixes

- Test OTP `1234` is verified by the deployed backend; the APK no longer bypasses server verification.
- Cart artwork is bundled in the APK and does not depend on missing media URLs.
- Cart prices remain visible on narrow phone screens.
- The wallet preview displays cached/default balance immediately while refreshing.

### Authentication verification

Tested from the installed APK on Android on 8 November 2026:

- Phone-first registration reached the deployed Render backend.
- OTP `1234` was accepted by the backend and marked the phone verified.
- Password creation succeeded after OTP verification.
- A subsequent password login succeeded and opened the authenticated profile flow.
