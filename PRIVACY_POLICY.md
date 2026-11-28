# Privacy Policy — Έχεις Κότσια; (Do You Have the Guts?)

**Effective Date:** November 28, 2026  
**Developer:** Giannis Oikonomakis ([jemangr.app](https://jemangr.app/el/))

## 100% On-Device Sensors, Camera & Microphone

**Έχεις Κότσια; (Do You Have the Guts?)** (`app.jemangr.testkotsion`) processes all biometric signals and media strictly locally on your device.

* **Camera & Microphone (Optional):** Used optionally during active test runs to measure decibel peaks, detect facial motion jumps, capture your peak reaction snapshot, and composite your 9:16 split-screen reaction video locally in device memory. **No video, photo, or audio clip is ever uploaded to any server.**
* **Motion Sensors:** Accelerometer and gyroscope events are analyzed locally in real time to compute hand tremor and flinch G-force.
* **Local Preferences Only:** Language, safety notice state, mute state, camera toggle, and Pro/perk unlock status are stored strictly in `localStorage` on your device.
* **Advertising & Consent (Android):** The Android app supports optional rewarded videos and frequency-capped post-result interstitials via Google AdMob (`@capacitor-community/admob`) with Google User Messaging Platform (UMP) GDPR consent where required. An optional **Party Pass Pro** unlock is available via Google Play Billing.
* **Optional Update Check:** Performs a read-only HTTPS GET request to GitHub (`version.json` / latest release metadata) with zero personal identifiers.

## Contact
Portfolio & Support: [https://jemangr.app/el/](https://jemangr.app/el/)

Copyright © 2026 Giannis Oikonomakis (jemangr.app). All Rights Reserved.
