# Vision Player Pro Privacy Policy — Meta Quest

- **App:** Vision Player Pro: VR Video Player, on the Meta Horizon Store
- **Publisher:** Meshy (Ahmed Dalhi)
- **Effective date:** July 25, 2026
- **Last updated:** October 1, 2026

---

## Summary

Vision Player Pro has no accounts, no servers, no advertising and no analytics. Your videos, history, settings and passwords stay on your headset. We cannot see them.

The app uses a few Meta Horizon platform features, and those give it access to some data from your Meta account:

- your **Meta user ID** for this app (Meta's "User ID" feature)
- your **Meta profile**, meaning your username and profile picture (Meta's "User Profile" feature)
- your **achievement progress**: the number of days you have watched videos

The app uses this data for two things: to record your achievements on your Meta account, and to end the Meta Horizon Store free trial after 7 days of watching. It also checks with Meta that you own the app. Any user can ask us to delete this data at any time. Section 7 explains how.

---

## 1. Who We Are

Vision Player Pro: VR Video Player ("Vision Player Pro", "the app") is published on the Meta Horizon Store by **Meshy**. The person responsible for your data (the data controller) is **Ahmed Dalhi**, based in France.

Contact: **davinci.dalhi@gmail.com**

This policy covers Vision Player Pro on Meta Quest headsets running Meta Horizon OS (Quest 2, Quest Pro, Quest 3 and Quest 3S).

---

## 2. Data We Collect and How We Use It

### 2.1 Your Meta user ID (Meta "User ID" feature)

- **What it is:** the number Meta uses to identify your Meta account inside Vision Player Pro. It is not your username. Meta gives each app a different number for the same person, so this one cannot identify you in other apps.
- **How the app gets it:** Meta Horizon OS provides it through the Meta Horizon Platform SDK when the app starts.
- **How it is used:**
  - Meta saves your achievement progress (section 2.3) under this ID. That is how Meta knows the progress belongs to you.
  - The app shows it to you as your **account number** in **Settings > Privacy**, so you can include it in a deletion request (section 7).
- The app does not save this ID. It only goes to Meta, as part of achievement updates.

### 2.2 Your Meta profile: username and profile picture (Meta "User Profile" feature)

- **What it is:** your Meta Horizon username and profile picture.
- **How it is used:** achievements you earn in Vision Player Pro appear on your Meta Horizon profile, next to your username and picture. Meta requires every app that uses achievements to request access to this profile information.
- Vision Player Pro itself does not read, display, save or send your username or profile picture.

### 2.3 Your achievement progress

- **What it is:**
  - a **"days watched" count**: the number of different days on which you played at least one video in the app
  - whether you have unlocked the **"Regular Viewer"** achievement, which unlocks after 7 days of watching
- **How it is collected:** the first time you start a video on a given day, the app adds 1 to the count. On the 7th day it unlocks "Regular Viewer". The app saves only the date of the last day it counted, on your headset, so it does not count the same day twice.
- **How it is used:**
  - to show your achievements on your Meta Horizon profile
  - to end the Meta Horizon Store free trial. If you are trying the app before buying it, the trial ends when "Regular Viewer" unlocks, and Meta then offers you the purchase.
- **Never recorded or sent:** which videos you watched, their names, when you watched them, or for how long.

### 2.4 Ownership check (entitlement)

When the app starts, it asks Meta Horizon OS whether your Meta account owns Vision Player Pro. It gets back a yes or no answer and uses it only to stop unlicensed copies of the app from running. The answer is not saved or sent anywhere.

### 2.5 Emails you send us

If you email us for support or to request deletion, we receive your email address, your message, and anything you include, such as your account number. We use it only to answer you, or to find and delete your data. Your email passes through our email provider. We keep it only while we handle your request. For deletion requests, we delete your email once we have confirmed the deletion to you.

---

## 3. Data That Stays on Your Headset

To remember your library and preferences, the app saves the following on your headset. **It never leaves your headset, and we cannot see it.**

- Playback resume positions
- Playback history and favorites
- Per-video format settings (projection, 3D mode, audio track selection)
- Network server bookmarks
- **Network server passwords**, encrypted with Android `EncryptedSharedPreferences`, which uses hardware-backed Android Keystore protection
- The date of the last day counted toward your achievement progress (section 2.3)
- Thumbnails of your videos, and a fingerprint of each video file the app has shown, with the file's location. The fingerprint is calculated from the file's size and its first and last 64 KB. It lets the app recognise a video you have moved or renamed, so the video keeps its thumbnail, resume position, favorite and history. If a video disappears from its folder, these are kept for up to 180 days in case it comes back, for example when you reconnect a drive.

---

## 4. Data We Do Not Collect

We collect nothing beyond what sections 2 and 3 describe. In particular, Vision Player Pro does **not** collect:

- Your name, email address or phone number (unless you email us, as in section 2.5)
- Hardware serial numbers or advertising identifiers
- Location, whether precise or approximate
- Usage analytics, telemetry or crash reports
- Video names, video content, folder paths or viewing habits
- Biometric data, such as hand-tracking positions or camera images

---

## 5. Where Your Data Is Stored and Who Can Access It

- **Your Meta user ID, profile and achievement progress** are stored by **Meta** on Meta's servers, as part of your Meta account, under [Meta's Privacy Policy](https://www.meta.com/legal/privacy-policy/).
- Vision Player Pro has **no servers, no database and no user accounts** of its own. We (the developer) do not receive your user ID, profile or achievement progress, except for an account number you choose to email us. We access your achievement progress only to delete it at your request, using the tools Meta provides to developers.
- We do not use any data processors, service providers or partners that can access this data.

---

## 6. How Long We Keep Data

| Data | How long it is kept |
|---|---|
| Meta user ID, username, profile picture | Not saved by the app. |
| Achievement progress | On your Meta account until you ask us to delete it (section 7) or you delete your Meta account. |
| Data on your headset (section 3) | Until you clear the app's data or uninstall the app. |
| Emails you send us | While we handle your request (section 2.5). |

---

## 7. Requesting Data Deletion

**All users, in every country, can ask us to delete their data at any time. It is free, and you do not have to give a reason.**

### Data on your headset

You can delete this yourself, immediately:

- In your headset's **Settings**, open **Storage**, select **Vision Player Pro**, and choose **Clear Data**, or
- Uninstall Vision Player Pro. This permanently deletes all of the app's data from your headset.

### Achievement progress and account data

1. Open Vision Player Pro, go to **Settings > Privacy**, and note your **account number**.
2. Email **davinci.dalhi@gmail.com** with the subject **"Data deletion request"** and include your account number. The app never learns your name or email address, so this number is the only way we can find your data.
3. Within **30 days**, we delete all of your Vision Player Pro achievement progress (locked and unlocked) using Meta's developer tools. We then email you to confirm.

If the app is no longer installed, you can reinstall it from your Meta Horizon library to find the number. If you cannot do that, email us anyway and we will work with you to find and delete your data.

After deletion, your Vision Player Pro achievements disappear from your Meta profile. If you keep using the app, the days-watched count starts again from zero.

We will not refuse a deletion request. No law requires us to keep any of this data.

You can also manage or delete the data that Meta holds about your Meta account using Meta's own tools, described in [Meta's Privacy Policy](https://www.meta.com/legal/privacy-policy/).

---

## 8. Your Other Rights

Wherever you live, you can ask us to:

- tell you what data we hold about you and give you a copy
- correct it
- delete it (section 7)
- stop or restrict using it

Email **davinci.dalhi@gmail.com**. We answer within 30 days, free of charge.

You can also complain to a data protection authority. In France, that is the CNIL ([cnil.fr](https://www.cnil.fr)). Elsewhere, contact your local authority.

**Legal basis (for users in the EEA and the UK):**

- We use your Meta user ID and achievement progress to provide app features you chose to use: achievements and the store free trial. This is necessary to perform our contract with you.
- The ownership check protects the app from unlicensed copies. This is our legitimate interest.
- We use your emails because you asked us something. This is also our legitimate interest.

---

## 9. Network Activity

The app connects to the network only for the following:

- **Local network SMB streaming:** connects directly over port 445 to a PC, Mac or NAS that you add, and streams from it over your local Wi-Fi. This traffic stays inside your local network.
- **DLNA media servers:** sends a discovery request to your local network (SSDP multicast) to find DLNA/UPnP media servers, then streams directly from the one you choose. This traffic stays inside your local network.
- **Automatic share discovery:** listens for file shares that computers and NAS devices announce on your local network (mDNS), so they appear without typing an address.
- **HTTP/HLS streaming:** connects directly to video stream addresses that you enter.
- **Meta platform services:** communicates with Meta, through Meta Horizon OS, for the ownership check and achievements (section 2).

---

## 10. System Permissions

- **Internet and network access (`INTERNET`, `ACCESS_NETWORK_STATE`):** used for local SMB and DLNA streaming, streams you enter, and Meta platform services.
- **Local network discovery (`ACCESS_WIFI_STATE`, `CHANGE_WIFI_MULTICAST_STATE`):** used to discover DLNA media servers on your local network, only while a search is running. These permissions do not give the app your location or Wi-Fi network details.
- **Videos on your headset (`READ_MEDIA_VIDEO`; `READ_EXTERNAL_STORAGE` on older system versions):** lets the Files tab list and play videos stored on your headset. The app accesses video files only, not photos, audio or documents.
- **Keep awake (`WAKE_LOCK`):** added by the Android media playback library (Media3), so the headset does not sleep in the middle of a video.
- **Hand tracking (`HAND_TRACKING`):** lets you use the app's panels and controls with your hands. Meta Horizon OS processes hand tracking. Vision Player Pro does not capture or store camera images or hand data.
- **Audio settings (`MODIFY_AUDIO_SETTINGS`):** used to change the volume from the player controls.

---

## 11. Third Parties, Advertising and Sharing

Vision Player Pro contains **no advertising, no analytics and no tracking code**. We do not sell, rent, share or transfer your data to anyone. The only other party involved is Meta, which runs Meta Horizon OS, the Meta Horizon Store and the platform features described in section 2.

---

## 12. Children

Vision Player Pro is a general-audience video player. It never asks for personal details. It handles the same limited data (section 2) for every user, whatever their age. A parent or guardian can request deletion of a child's data as described in section 7.

---

## 13. Security

We keep no copy of your data on any server. Network server passwords on your headset are encrypted with hardware-backed Android Keystore protection. The app displays your account number but does not save it.

---

## 14. Changes to This Policy

If we change this policy, we will publish the new version here and update the "Last updated" date above. If a change affects what data the app collects, we will also say so in the app's release notes.

---

## 15. Contact

- **Data controller:** Ahmed Dalhi (Meshy), France
- **Email:** davinci.dalhi@gmail.com
- **GitHub:** [github.com/Meshy-SC/VisionPlayer](https://github.com/Meshy-SC/VisionPlayer)
