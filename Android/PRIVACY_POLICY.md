# Vision Player Privacy Policy — Meta Horizon OS

**Effective Date:** July 25, 2026  
**Last Updated:** July 25, 2026  

---

## 1. Overview & Scope
This Privacy Policy describes how **VisionPlayer** ("the app", "we", "us") handles information on Meta Quest headsets running Meta Horizon OS (Quest 2, Quest Pro, Quest 3, and Quest 3S). It addresses Meta's Virtual Reality Checks for privacy (**VRC.Privacy.1 through VRC.Privacy.4**).

---

## 2. Data We Do Not Collect (VRC.Privacy.2)
VisionPlayer is designed to keep your media browsing completely private. We do **not** collect, store, sell, or transmit any of the following:

- Personal identifiers (name, email, phone number, Meta User ID)
- Hardware serial numbers or advertising identifiers
- Precise or coarse location data
- App usage analytics, telemetry, or crash reports sent to external servers
- Video filenames, media content, or folder paths from your personal library
- Biometric data (hand tracking joint positions or camera imagery)

---

## 3. Information Stored Locally on Your Device
To provide playback features, VisionPlayer stores app state locally on your Meta Quest headset:

- Playback resume positions
- Playback history and favorites
- Per-video format configurations (projection, 3D mode, audio track selections)
- Network server bookmarks
- **Encrypted SMB credentials** (stored using Android `EncryptedSharedPreferences` with hardware keystore protection)

All data remains on your headset and is never transmitted to external servers.

---

## 4. Network Activity
Network communication occurs strictly when initiated by you:

- **Local Network SMB Streaming:** Connects directly over port 445 (SMB) to stream media from your PC, Mac, or NAS on your local Wi-Fi. Traffic is restricted to your local network.
- **Direct HTTP/HLS Streaming:** Connects directly to user-entered video stream URLs.

---

## 5. System Permissions (VRC.Privacy.4)
VisionPlayer requests only essential permissions:

- **Internet & Network Access (`INTERNET`, `ACCESS_NETWORK_STATE`):** Required for local SMB network streaming and user-specified web streams.
- **Hand Tracking (`HAND_TRACKING`):** Enables hands-free interaction with Horizon OS UI panels and transport controls. Hand tracking is processed by Horizon OS; VisionPlayer does not capture or store camera images or biometric data.
- **Audio Settings (`MODIFY_AUDIO_SETTINGS`):** Allows volume adjustment via the in-app transport controls.

---

## 6. Third-Party Services & Ads
VisionPlayer contains **no third-party advertising SDKs, no tracking frameworks, and no analytics code**.

---

## 7. User Control & Data Deletion (VRC.Privacy.3)
Because all app data is stored locally on your device:

- You can clear all app preferences and credentials at any time in **Settings > Storage > VisionPlayer > Clear Data** on your Meta Quest.
- Uninstalling VisionPlayer permanently deletes all local data from your headset.
- No external server data deletion requests are needed.

---

## 8. Contact Information
If you have questions regarding this Privacy Policy:

- **Email:** davinci.dalhi@gmail.com
- **GitHub Repository:** [github.com/Meshy-SC/VisionPlayer](https://github.com/Meshy-SC/VisionPlayer)
