# Monopoly: Android releases

Signed APKs of the Monopoly Android app, published automatically by CI from the (private) source
repository. This repository holds no source code.

- **Install:** open the latest release under **Releases**, download `monopoly-x.y.z.apk` on the phone
  and open it (Android asks once to allow installs from your browser or Files app).
- **Update:** once installed, the app finds new versions itself: **About → Check for updates**, or the
  banner on Home. Saved games stay.
- `update.json` describes the newest release (version, download link, SHA-256, notes). The app installs
  an update only if the file's checksum, package name, version and signing certificate all match.
