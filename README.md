# Spotless

Builds of Spotless, a native macOS 27 cleaner, disk explorer and system monitor.

1. Download `Spotless-<version>.zip` from the [latest release](https://github.com/MansiVisuals/Spotless-Releases/releases/latest).
2. Unzip it and move Spotless to the Applications folder.
3. These builds are signed with a self-signed certificate and aren't notarized, so remove the download quarantine once in Terminal:

   ```sh
   xattr -dr com.apple.quarantine /Applications/Spotless.app
   ```

From version 0.1.1 on, Spotless checks this page once a day and updates itself (Spotless ▸ Check for Updates…). It installs a new version only when it's signed with the same certificate as the copy you have.
