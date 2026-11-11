# SafeBeauty — releases

Installer downloads for the **SafeBeauty for Salons** desktop app, by
[Linumic](https://linumic.com). SafeBeauty is a beauty-salon booking marketplace
for Afghanistan.

This repository holds **release files only**. The application source is private.

## Download

Get the files from the [Releases page](../../releases/latest), or from the
salon download page: <https://safebeauty.web.app/provider-app>.

| Platform | File |
|---|---|
| macOS, Apple Silicon | `SafeBeauty-Salon-mac-arm64.dmg` |
| macOS, Intel | `SafeBeauty-Salon-mac-x64.dmg` |
| Windows | `SafeBeauty-Salon-win-x64.exe` |

The app opens the salon console (<https://salon.linumic.com>) in its own window.
A salon owner signs in with the phone number and password of her SafeBeauty
account; there is no separate account for the desktop app.

### Installing

The apps are **not code-signed**, so the first time you open one your computer
asks you to confirm.

- **macOS:** open the `.dmg`, drag the app to Applications, then right-click it
  and choose **Open**, and confirm once.
- **Windows:** run the `.exe`. If SmartScreen warns, choose **More info**, then
  **Run anyway**.

### Checking a download

`SHA256SUMS.txt` on the release lists the SHA-256 of each file. On macOS:
`shasum -a 256 <file>`; on Windows: `certutil -hashfile <file> SHA256`.

## Questions

safebeauty@linumic.com
