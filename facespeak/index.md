# FaceSpeak — Privacy Policy

**Last updated: October 26, 2026**

FaceSpeak ("the app") is an Augmentative and Alternative Communication (AAC) app that translates facial gestures into spoken phrases. This policy explains what data the app accesses, what it does with it, and what it never does.

## Camera & Face Data

FaceSpeak requires camera access (`android.permission.CAMERA`) to detect facial gestures.

- Camera frames are analyzed **entirely on-device** using Google ML Kit Face Detection, which runs locally on your phone.
- No camera frame, image, video, or derived face data (expressions, landmarks, gesture history) is ever uploaded, transmitted over the network, or stored outside your device.
- Nothing from the camera is written to disk. Frames exist only in memory for the fraction of a second needed to detect a gesture, then are discarded.

## Data Stored On Your Device

The following is stored locally on your device only, and is never transmitted anywhere:

- Your custom gesture-to-phrase mappings and settings (sensitivity, cooldown, TTS speed/pitch).
- Your recent phrases history (last 10 spoken phrases).

This data is removed if you uninstall the app or clear its storage.

## Crash Reporting

FaceSpeak uses **Firebase Crashlytics** to receive automatic crash and error reports if the app fails unexpectedly. A crash report may include: device model, OS version, app version, and a stack trace of the failure. Crash reports do **not** include camera frames, face data, or your gesture mappings/phrases.

The app has no analytics, no accounts and no remote database: Crashlytics is the only network service it uses.

## Permissions

| Permission | Why FaceSpeak needs it |
|---|---|
| Camera | Real-time facial gesture detection (on-device only) |
| Vibrate | Haptic feedback when a gesture is detected |

## Third Parties

FaceSpeak does not sell, rent, or share your data with third parties. The only third-party service integrated is Firebase Crashlytics (Google), used solely for crash diagnostics as described above, governed by [Google's Privacy Policy](https://policies.google.com/privacy).

## Children's Privacy

FaceSpeak does not knowingly collect any personal information from anyone, including children, since no personal data leaves the device except anonymous crash diagnostics.

## Changes to This Policy

If FaceSpeak's data practices change, this document will be updated and the "Last updated" date above will reflect the change.

## Contact

Questions about this policy can be sent to: pedro13087@gmail.com
