# PhonePal

PhonePal is a personal notes and checklists app for Android and Windows. It is built with Flutter and syncs across devices through Firebase, so a note created on your phone can show up on your PC a few seconds later.

This repository currently hosts release builds for PhonePal.

Latest release: [PhonePal 0.1.0](https://github.com/Excellonline/phone-pal/releases/tag/v0.1.0)

## Downloads

| Platform | Release file | Use this when |
| --- | --- | --- |
| Android APK | `releases/android/PhonePal-Android-0.1.0.apk` | You want to sideload PhonePal directly onto an Android phone. |
| Android AAB | `releases/android/PhonePal-Android-0.1.0.aab` | You need the Play Store / app bundle build. |
| Windows ZIP | [PhonePal-Windows-0.1.0.zip](https://github.com/Excellonline/phone-pal/releases/tag/v0.1.0) | You want the easiest Windows download. |
| Windows folder | `releases/windows/PhonePal-Windows-0.1.0/phonepal.exe` | You are browsing the committed release files directly. Keep the whole folder together. |

## Features

- Notes and checklists that sync between Android and Windows
- Firebase email/password sign-in
- Offline editing with queued sync when the device reconnects
- Search, folders/tags, reminders, and sort options
- Drag-to-reorder checklist items
- Light and dark theme support
- Desktop shortcuts for fast note, checklist, and search actions

## Install

### Android

1. Download `releases/android/PhonePal-Android-0.1.0.apk`.
2. Open the APK on your Android device.
3. If Android asks, allow installs from the browser or file manager you used.
4. Launch PhonePal and sign in with your PhonePal account.

### Windows

1. Download `PhonePal-Windows-0.1.0.zip` from the latest GitHub release.
2. Extract the ZIP.
3. Open `PhonePal-Windows-0.1.0/`.
4. Run `phonepal.exe`.

Do not move `phonepal.exe` out of its folder. The DLLs, Flutter runtime, and `data/` directory are part of the Windows app bundle.

## Release Integrity

SHA-256 checksums for the main release artifacts are tracked in `releases/CHECKSUMS.txt`.

## Project Notes

PhonePal was built as a cross-device personal productivity app. The app uses Firebase Authentication and Cloud Firestore for account-based sync, with local persistence so edits can continue while offline.

This repository is focused on published release artifacts. The Flutter source project is maintained separately.

## Support

If something does not install or sync correctly, open an issue with:

- Your platform: Android or Windows
- The release file you used
- A short description of what happened
- Any visible error message

## License

No open-source license has been published for this repository. All rights are reserved by the repository owner.
