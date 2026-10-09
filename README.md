# Division Records System downloads

## Fresh-deployment release candidate

- [Windows 0.3.1 package](https://github.com/gragaza-creator/DRS-downloads/releases/download/windows-v0.3.1/DRS-Windows-v0.3.1.zip) — extract the entire ZIP and open DRS.Desktop.exe. Restores Change folder under Admin / Google Drive. Includes the guided installation checklist and unchanged standard Android 0.3.0 template.
- [Standard Android 0.3.0](https://github.com/gragaza-creator/DRS-downloads/releases/download/android-v0.3.0/DRS-Android-v0.3.0.apk) — code 12, office scanner with shared-section phone access and compressed tracking batches.
- [Android update QR](https://github.com/gragaza-creator/DRS-downloads/releases/download/android-v0.3.0/DRS-Android-QR.png).
- [Separate DRS Super 1.1.0](https://github.com/gragaza-creator/DRS-downloads/releases/download/super-v1.1.0/DRS-Super-v1.1.0.apk) — code 8, section switching.
- [Separate Super setup package](https://github.com/gragaza-creator/DRS-downloads/releases/download/super-v1.1.0/DRS-Super-Setup-v1.1.0.zip).
- [Windows checksum](https://github.com/gragaza-creator/DRS-downloads/releases/download/windows-v0.3.1/SHA256SUMS.txt).

165 automated tests and native Windows checks passed. The candidate still requires actual phone and Google-account acceptance. No test phone was available. Read the included INSTALL-CHECKLIST.txt, PACKAGER-CHECKLIST.txt, RELEASE-NOTES.md and UI-VALIDATION.md.

The first Windows Create access opens the installation checklist: App setup, Google sign-in, Drive folder, Sync check, Phone setup. The package administrator prepares Google app settings once; normal staff use the guided flow. Public packages contain no Google account configuration, workspace databases or enrollment credentials.

Android requires Android 8.0 or later, ARM64/ARM32 and Google Play services. Install generic updates over an existing enrolled app to retain its access and queue. **A fresh phone must use a configured section QR from Records.** One section QR can enroll multiple authorized phones. Keep configured office/operator downloads private.

The new deployment starts with a fresh database. Compressed immutable tracking batches preserve individual action signatures without phones overwriting one shared transaction file. One current snapshot and one reusable app download per section limit duplication within the 15 GB account budget.

## Previous published versions

[Windows 0.2.12](https://github.com/gragaza-creator/DRS-downloads/releases/tag/windows-v0.2.12), [Android 0.2.10](https://github.com/gragaza-creator/DRS-downloads/releases/tag/android-v0.2.10), [Super 1.0.5](https://github.com/gragaza-creator/DRS-downloads/releases/tag/super-v1.0.5). Their notes describe their own validation limits; publication is not proof of phone/account field testing.
