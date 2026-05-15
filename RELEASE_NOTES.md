# LocaleShot 0.1.0

Initial public beta for indie iOS developers.

## Highlights

- Record one screenshot flow in the iOS Simulator.
- Replay the flow across selected App Store locales.
- Capture raw simulator screenshots without device frames or marketing templates.
- Use a visual macOS app with project management, language selection, generation progress, and screenshot review.
- Follow the Start Here panel for permission setup, Simulator attach, app selection, recording, and generation.
- Keep data local. No accounts, uploads, analytics, or telemetry.

## Requirements

- macOS 13 or newer
- Xcode with iOS Simulator installed
- A booted iOS Simulator with the target app installed
- Accessibility permission for recording clicks in the real Simulator window

## Known Limits

- This beta is optimized for iOS Simulator workflows, not physical devices.
- Replay uses recorded coordinates, so large UI changes between languages can still require re-recording.
- Developer ID signing and notarization require local Apple developer credentials.
