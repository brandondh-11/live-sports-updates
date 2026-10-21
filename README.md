# Live Sports updates

[Download the latest official installers](https://github.com/brandondh-11/live-sports-updates/releases/latest).

This repository contains the update manifest, installer releases, and SHA256 checksums. Project source and signing credentials remain private.

Version 1.2.12 introduces clean Live Sports application identities:

- Android: `io.livesports.app`
- Windows application ID: `io.livesports.app`
- Linux Flatpak: `io.livesports.LiveSports`

Android and Linux users upgrading from earlier releases must install the new app once. It is a separate application and does not automatically inherit the old application's saved settings. After checking the new installation, remove the old application to avoid duplicate launchers. Future releases update the new identity through Update now / Later. Windows Setup uses the existing LiveSports installation and settings location.

Android's replacement certificate identifies Live Sports and retains the private signing key. Downloads are verified against the published SHA256 checksums. Android requires system installation confirmation; Windows opens Setup; Linux opens the verified Flatpak in the system installer.
