# LocaleShot Privacy

LocaleShot is a local macOS app for recording and replaying iOS Simulator screenshot flows.

## Data Collection

LocaleShot does not collect analytics, telemetry, crash reports, device identifiers, account information, or personal data.

## Local Files

LocaleShot stores project data and generated screenshots locally on your Mac:

- Project settings, selected app bundle IDs, selected languages, and recorded flow steps
- Generated screenshots and manual checkpoint screenshots
- Local diagnostics files if you explicitly export them
- Recent local LocaleShot crash report excerpts inside exported diagnostics, if macOS created crash reports

By default, app data is stored in Application Support for packaged builds and in `.localizedscreenshots/` when running from the Swift package.

## Network Access

LocaleShot does not require network access for screenshot generation. It invokes local developer tools such as Xcode, `xcrun`, Simulator, and XCUITest.

## Third-Party Services

LocaleShot does not upload apps, screenshots, project data, or diagnostics to any third-party service.

## Contact

Open a GitHub issue if you find behavior that conflicts with this policy.
