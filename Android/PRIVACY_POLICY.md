# Vision Player Pro Privacy Policy — Meta Horizon OS

**Effective Date:** July 25, 2026  
**Last Updated:** September 26, 2026  

---

## 1. Overview & Scope
This Privacy Policy describes how **Vision Player Pro** ("the app", "we", "us") handles information on Meta Quest headsets running Meta Horizon OS (Quest 2, Quest Pro, Quest 3, and Quest 3S). It addresses Meta's Virtual Reality Checks for privacy (**VRC.Privacy.1 through VRC.Privacy.4**).

---

## 2. Data We Do Not Collect (VRC.Privacy.2)
Vision Player Pro is designed to keep your media browsing completely private. We do **not** collect, store, sell, or transmit any of the following:

- Personal identifiers (name, email, phone number, Meta User ID)
- Hardware serial numbers or advertising identifiers
- Precise or coarse location data
- App usage analytics, telemetry, or crash reports sent to external servers
- Video filenames, media content, or folder paths from your personal library
- Biometric data (hand tracking joint positions or camera imagery)

---

## 3. Information Stored Locally on Your Device
To provide playback features, Vision Player Pro stores app state locally on your Meta Quest headset:

- Playback resume positions
- Playback history and favorites
- Per-video format configurations (projection, 3D mode, audio track selections)
- Network server bookmarks
- **Encrypted SMB credentials** (stored using Android `EncryptedSharedPreferences` with hardware keystore protection)

All of this data remains on your headset and is never transmitted to external servers. The only information that leaves your headset is described in section 5.

---

## 4. Network Activity
Network communication occurs strictly when initiated by you:

- **Local Network SMB Streaming:** Connects directly over port 445 (SMB) to stream media from your PC, Mac, or NAS on your local Wi-Fi. Traffic is restricted to your local network.
- **DLNA Media Servers:** Sends a discovery request to your local network (SSDP multicast) to find DLNA/UPnP media servers, then streams directly from the one you choose. Traffic stays inside your local network.
- **Automatic Share Discovery:** Listens for file shares that computers and NAS devices announce on your local network (mDNS), so they appear without typing an address.
- **Direct HTTP/HLS Streaming:** Connects directly to user-entered video stream URLs.

---

## 5. Meta Platform Services
Vision Player Pro uses two services built into Meta Horizon OS. Both are provided by Meta, under your Meta account and [Meta's Privacy Policy](https://www.meta.com/legal/privacy-policy/):

- **Entitlement check:** when the app starts, it asks Horizon OS whether your Meta account owns the app.
- **Achievements:** the first time you play a video on a given day, the app adds one to a "days watched" achievement on your Meta account. Reaching a milestone unlocks an achievement that appears on your Meta profile, and it is also what ends the Meta Horizon Store free trial. Only the count of days is recorded. What you watched, when, and for how long is never sent.

We do not retrieve or store this information ourselves.

---

## 6. System Permissions (VRC.Privacy.4)
Vision Player Pro requests only essential permissions:

- **Internet & Network Access (`INTERNET`, `ACCESS_NETWORK_STATE`):** Required for local SMB and DLNA network streaming and user-specified web streams.
- **Local Network Discovery (`ACCESS_WIFI_STATE`, `CHANGE_WIFI_MULTICAST_STATE`):** Required to discover DLNA media servers on your local network. Used only while a search is running; does not give the app access to your location or Wi-Fi network details.
- **Videos on Your Headset (`READ_MEDIA_VIDEO`; `READ_EXTERNAL_STORAGE` on older system versions):** Lets the library's Files tab list and play the videos stored on your headset. Video files only — no photos, audio, or documents.
- **Keep Awake (`WAKE_LOCK`):** Added by the Android media playback library (Media3) so the headset does not sleep in the middle of a video.
- **Hand Tracking (`HAND_TRACKING`):** Enables hands-free interaction with Horizon OS UI panels and transport controls. Hand tracking is processed by Horizon OS; Vision Player Pro does not capture or store camera images or biometric data.
- **Audio Settings (`MODIFY_AUDIO_SETTINGS`):** Allows volume adjustment via the in-app transport controls.

---

## 7. Third-Party Services & Ads
Vision Player Pro contains **no third-party advertising SDKs, no tracking frameworks, and no analytics code**.

---

## 8. User Control & Data Deletion (VRC.Privacy.3)
Because all app data is stored locally on your device:

- You can clear all app preferences and credentials at any time in **Settings > Storage > Vision Player Pro > Clear Data** on your Meta Quest.
- Uninstalling Vision Player Pro permanently deletes all local data from your headset.
- No external server data deletion requests are needed. Achievement progress (section 5) belongs to your Meta account and is managed by Meta.

---

## 9. Contact Information
If you have questions regarding this Privacy Policy:

- **Email:** davinci.dalhi@gmail.com
- **GitHub Repository:** [github.com/Meshy-SC/VisionPlayer](https://github.com/Meshy-SC/VisionPlayer)
