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

SHA-256: `22897FE70CAF020219F8D61369FB93E228D4C39ECD031A153DC9C6F6A81162C2`

### Homepage reliability fixes

- Test OTP `1234` is handled locally without waiting for the backend.
- Cart artwork is bundled in the APK and does not depend on missing media URLs.
- Cart prices remain visible on narrow phone screens.
- The wallet preview displays cached/default balance immediately while refreshing.
