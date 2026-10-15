# WalkieTalkie releases

Android APKs for **WalkieTalkie** — private push-to-talk over the internet or
phone-to-phone with no network. The source code is kept private; this
repository only hosts signed releases.

## Install

1. Open the [latest release](https://github.com/CodeWithRakibul/walkie-talkie-releases/releases/latest) on your phone.
2. Download the APK for your phone:
   - **`arm64-v8a`** — almost all phones from the last several years.
   - **`universal`** — works everywhere (larger download); use it if unsure.
3. Open the file and allow your browser to install apps when Android asks.

Requires Android 10 or newer and Google Play services.

## Updates

Once installed, the app checks for a new release every time it opens and offers
to download and install it. Android only accepts an update signed with the same
key as the installed app, so a tampered APK can't replace it. Each release lists
the SHA-256 of every APK.

`update.json` (attached to every release) is what the app reads:
`https://github.com/CodeWithRakibul/walkie-talkie-releases/releases/latest/download/update.json`
