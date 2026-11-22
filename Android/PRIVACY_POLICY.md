# Vision Player Pro Privacy Policy — Meta Quest

- **App:** Vision Player Pro: VR Video Player, on the Meta Horizon Store
- **Publisher:** Meshy (Ahmed Dalhi)
- **Effective date:** July 25, 2026
- **Last updated:** November 22, 2026

---

## Summary

Vision Player Pro is free to download. It offers **Vision Player Pro+**, a one-time in-app purchase, and it uses Meta Horizon platform features for in-app purchases and achievements. To do this, **Vision Player Pro collects and processes the following user data**:

- your **Meta user ID** for this app (Meta's "User ID" feature)
- your **Meta profile**, meaning your username and profile picture, on which Meta shows your achievements (Meta's "User Profile" feature)
- your **achievement progress**: the number of days on which you watched videos in earlier, paid versions of the app, and whether you owned the app before it became free
- your **in-app purchase data**: whether your Meta account has bought Vision Player Pro+ (Meta's "In-App Purchases" feature)

Vision Player Pro uses this data to unlock Vision Player Pro+ for people who bought it, or who bought the app before it became free, and to record your achievements on your Meta account. It also checks with Meta that your account has the app. Your videos, history, settings, server passwords and the free version's daily watching time are stored on your headset.

Any user can ask us to delete their data at any time, free of charge. Section 7 explains how.

---

## 1. Who We Are

Vision Player Pro: VR Video Player ("Vision Player Pro", "the app") is published on the Meta Horizon Store by **Meshy**. The person responsible for your data (the data controller) is **Ahmed Dalhi**, based in France.

Contact: **davinci.dalhi@gmail.com**

This policy covers Vision Player Pro on Meta Quest headsets running Meta Horizon OS (Quest 2, Quest Pro, Quest 3 and Quest 3S).

---

## 2. Data We Collect and How We Use It

### 2.1 Your Meta user ID (Meta "User ID" feature)

- **What it is:** the number Meta uses to identify your Meta account inside Vision Player Pro. It is not your username. Meta gives each app a different number for the same person, so this one cannot identify you in other apps.
- **How it is processed:** Meta Horizon OS provides it to the app through the Meta Horizon Platform SDK when the app starts. Vision Player Pro processes it with every achievement update it sends to Meta (section 2.3), and Meta records your achievement progress under this ID, which is how Meta knows the progress belongs to you.
- **What it is used for:**
  - your achievements (section 2.3) and your purchases (section 2.4)
  - showing it to you as your **account number** in **Settings > Privacy**, so you can include it in a deletion request (section 7)

  It is not used for advertising, profiling or anything else. The app keeps it in memory while it runs; Meta stores it as part of your Meta account.

### 2.2 Your Meta profile: username and profile picture (Meta "User Profile" feature)

- **What it is:** your Meta Horizon username and profile picture.
- **How it is processed:** Meta processes your profile for Vision Player Pro's achievements: the achievements you earn in the app appear on your Meta Horizon profile, next to your username and picture. Meta requires every app that uses achievements to request access to this profile information.
- **What it is used for:** only for showing your achievements on your Meta Horizon profile. The app's own screens do not show your username or picture.

### 2.3 Your achievement progress

- **What it is:**
  - a **"days watched" count**: the number of different days on which you played at least one video in an earlier, paid version of the app (versions up to 26.1.17), and the **"Regular Viewer"** achievement those versions unlocked after 7 days of watching. The current version no longer adds to this count.
  - the **"Original Owner"** achievement, a hidden achievement that marks a Meta account that owned Vision Player Pro before it became free.
- **How it is collected:** earlier, paid versions added 1 to the count the first time you started a video on a given day. The current version reads the count and "Original Owner" when it starts. If your account has watched on a paid version, or the app on your headset was installed from a paid version, the app unlocks "Original Owner".
- **How it is used:**
  - to unlock Vision Player Pro+, free of charge, for everyone who bought Vision Player Pro before it became free. Your achievements are how the app recognises you as an earlier buyer, on any headset and after a reinstall.
  - to show your achievements on your Meta Horizon profile.
- **What it contains:** only the count and the two unlocks described above, with no video names, viewing times or durations.

### 2.4 Your in-app purchase data (Meta "In-App Purchases" feature)

- **What it is:** the record Meta keeps of the add-ons your Meta account has bought in Vision Player Pro. There is one: **Vision Player Pro+**, a one-time purchase. The record says which add-on it is and when it was bought.
- **How it is processed:** when the app starts, and when you choose **Restore Purchases** in **Settings > Vision Player Pro+**, the app asks Meta Horizon OS which add-ons your account owns and reads the store price of Vision Player Pro+ to show it. When you choose **Unlock Vision Player Pro+**, Meta Horizon OS shows Meta's own purchase screen; Meta handles the payment and tells the app whether the purchase went through. Your payment details (card or PayPal) are handled and kept by Meta.
- **What it is used for:** only to unlock Vision Player Pro+ on your headset and to show its price. It is not used for advertising, profiling or anything else.

### 2.5 Ownership check (entitlement)

When the app starts, it asks Meta Horizon OS whether your Meta account has Vision Player Pro from the Meta Horizon Store. It gets back a yes or no answer and uses it only to stop unlicensed copies of the app from running.

### 2.6 Emails you send us

If you email us for support or to request deletion, we receive your email address, your message, and anything you include, such as your account number. We use it only to answer you, or to find and delete your data. Your email passes through our email provider. We keep it only while we handle your request. For deletion requests, we delete your email once we have confirmed the deletion to you.

---

## 3. Data Stored on Your Headset

To remember your library and preferences, the app stores the following in its private storage on your headset:

- Playback resume positions
- Playback history and favorites
- Per-video format settings (projection, 3D mode, audio track selection)
- Network server bookmarks
- **Network server passwords**, encrypted with Android `EncryptedSharedPreferences`, which uses hardware-backed Android Keystore protection
- The date of the last day earlier versions counted toward your achievement progress (section 2.3)
- **Free version only:** how long you have watched videos today and the date, so the free version can offer its 10 minutes a day. Only time a video is actually playing is counted. Nothing about what you watched is stored.
- Whether Vision Player Pro+ is unlocked, so the app can start without waiting for Meta, and whether the app on your headset was first installed from an earlier, paid version (section 2.3)
- Thumbnails of your videos, and a fingerprint of each video file the app has shown, with the file's location. The fingerprint is calculated from the file's size and its first and last 64 KB. It lets the app recognise a video you have moved or renamed, so the video keeps its thumbnail, resume position, favorite and history. If a video disappears from its folder, these are kept for up to 180 days in case it comes back, for example when you reconnect a drive.

---

## 4. Crash Reports

If the app crashes, Meta Horizon OS may report it to Meta, and Meta's developer dashboard then shows us the technical details: the headset model, the Meta Horizon OS and app versions, and where in the code the crash happened. We use them only to fix the problem.

---

## 5. Where Your Data Is Stored and Who Can Access It

- **Your Meta user ID, profile, achievement progress and purchase records** are stored by **Meta** on Meta's servers, as part of your Meta account, under [Meta's Privacy Policy](https://www.meta.com/legal/privacy-policy/).
- **Your library data** (section 3) is stored on your headset.
- Vision Player Pro has no servers of its own. The developer can see the account number you include in an email to us, and can access your achievement progress through the tools Meta provides to developers; we use that access only to delete your progress at your request. Meta's developer dashboard also shows us the crash details described in section 4, and sales reports for Vision Player Pro+, which Meta provides as totals.
- No data processors, service providers or partners other than Meta have access to this data.

---

## 6. How Long We Keep Data

| Data | How long it is kept |
|---|---|
| Meta user ID, username, profile picture | Processed while the app runs and for each achievement update; kept by Meta as part of your Meta account. |
| Achievement progress | On your Meta account until you ask us to delete it (section 7) or you delete your Meta account. |
| Purchase records | Kept by Meta as part of your Meta account's purchase history, under Meta's Privacy Policy. |
| Data on your headset (section 3) | Until you clear the app's data or uninstall the app. |
| Emails you send us | While we handle your request (section 2.6). |

---

## 7. Requesting Data Deletion

**All users, in every country, can ask us to delete their data at any time. It is free, and you do not have to give a reason.**

### Data on your headset

You can delete this yourself, immediately:

- In your headset's **Settings**, open **Storage**, select **Vision Player Pro**, and choose **Clear Data**, or
- Uninstall Vision Player Pro. This permanently deletes all of the app's data from your headset.

### Achievement progress and account data

1. Open Vision Player Pro, go to **Settings > Privacy**, and note your **account number**.
2. Email **davinci.dalhi@gmail.com** with the subject **"Data deletion request"** and include your account number. This number is how we find your data in Meta's developer tools.
3. Within **30 days**, we delete all of your Vision Player Pro achievement progress (locked and unlocked) using Meta's developer tools. We then email you to confirm.

If the app is no longer installed, you can reinstall it from your Meta Horizon library to find the number. If you cannot do that, email us anyway and we will work with you to find and delete your data.

After deletion, your Vision Player Pro achievements disappear from your Meta profile. If you bought the app before it became free, the "Original Owner" achievement is how the app recognises you on a new headset or after a reinstall, so deleting it can remove Vision Player Pro+ in those cases; a Vision Player Pro+ purchase you made in the app is not affected, because Meta keeps it as part of your purchase history.

Your purchase records belong to your Meta account's purchase history, which Meta keeps; you can see and manage them with Meta's own tools.

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

- We use your Meta user ID, achievement progress and purchase data to provide what you bought and the features you chose to use: Vision Player Pro+, achievements, and Vision Player Pro+ for earlier buyers. This is necessary to perform our contract with you.
- The ownership check protects the app from unlicensed copies. This is our legitimate interest.
- We use your emails because you asked us something. This is also our legitimate interest.

---

## 9. Network Activity

The app connects to the network only for the following:

- **Local network SMB streaming:** connects directly over port 445 to a PC, Mac or NAS that you add, and streams from it over your local Wi-Fi. This traffic stays inside your local network.
- **DLNA media servers:** sends a discovery request to your local network (SSDP multicast) to find DLNA/UPnP media servers, then streams directly from the one you choose. This traffic stays inside your local network.
- **Automatic share discovery:** listens for file shares that computers and NAS devices announce on your local network (mDNS), so they appear without typing an address.
- **HTTP/HLS streaming:** connects directly to video stream addresses that you enter.
- **Meta platform services:** communicates with Meta, through Meta Horizon OS, for the ownership check, in-app purchases and achievements (section 2).

---

## 10. System Permissions

- **Internet and network access (`INTERNET`, `ACCESS_NETWORK_STATE`):** used for local SMB and DLNA streaming, streams you enter, and Meta platform services.
- **Local network discovery (`ACCESS_WIFI_STATE`, `CHANGE_WIFI_MULTICAST_STATE`):** used to discover DLNA media servers on your local network, only while a search is running. These permissions do not give the app your location or Wi-Fi network details.
- **Videos on your headset (`READ_MEDIA_VIDEO`; `READ_EXTERNAL_STORAGE` on older system versions):** lets the Files tab list and play videos stored on your headset. The app accesses video files only, not photos, audio or documents.
- **Keep awake (`WAKE_LOCK`):** added by the Android media playback library (Media3), so the headset does not sleep in the middle of a video.
- **Hand tracking (`HAND_TRACKING`):** lets you use the app's panels and controls with your hands. Meta Horizon OS processes hand tracking and turns your hands into a pointer for the app, used only while you use the app.
- **Audio settings (`MODIFY_AUDIO_SETTINGS`):** used to change the volume from the player controls.

---

## 11. Third Parties, Advertising and Sharing

Vision Player Pro contains **no advertising, analytics or tracking code**. Your data is never sold, rented or shared for advertising. The only other party involved is Meta, which runs Meta Horizon OS, the Meta Horizon Store, the purchase screen and payments, and the platform features described in section 2.

---

## 12. Children

Vision Player Pro is a general-audience video player. It processes the same limited data (section 2) for every user, whatever their age, and asks no one for personal details. A parent or guardian can request deletion of a child's data as described in section 7.

---

## 13. Security

The data on your headset is kept in the app's private storage, which other apps cannot read. Network server passwords on your headset are encrypted with hardware-backed Android Keystore protection. Your user ID, profile, achievement progress and purchase records are processed through Meta's own platform SDK and stored by Meta.

---

## 14. Changes to This Policy

If we change this policy, we will publish the new version here and update the "Last updated" date above. If a change affects what data the app collects, we will also say so in the app's release notes.

---

## 15. Contact

- **Data controller:** Ahmed Dalhi (Meshy), France
- **Email:** davinci.dalhi@gmail.com
- **GitHub:** [github.com/Meshy-SC/VisionPlayer](https://github.com/Meshy-SC/VisionPlayer)
