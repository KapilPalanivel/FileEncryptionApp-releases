# File Encryption App — downloads

Windows desktop app for encrypting files and folders with AES-256-GCM (Argon2id-derived keys), with vaults, recovery keys, integrity verification and watch folders.

## Download

**[Latest release →](https://github.com/KapilPalanivel/FileEncryptionApp-releases/releases/latest)**

1. Download `FileEncryptionApp-windows.zip`.
2. Extract it anywhere and run `FileEncryptionApp.exe` (it includes its own Java runtime).

From v2.1.1 on, the app updates itself: it checks once a day (or Settings → Updates → Check now) and downloads only what changed.

## Integrity

Every release includes `update.properties` (SHA-256 of each file) and `update.properties.sig`, an Ed25519 signature made with an offline key. The app refuses updates whose signature doesn't verify.

This repository only hosts release downloads.
