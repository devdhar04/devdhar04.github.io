# Privacy Policy for Smart Notes

**Effective Date:** May 18, 2026

**Last Updated:** May 29, 2026

Better Engineering ("we," "our," or "us") operates the Smart Notes mobile application (the "App"). This Privacy Policy explains how we handle information when you use our App.

---

## 1. Overview

Smart Notes is a note-taking application that stores all data locally on your device. We are committed to protecting your privacy and being transparent about our practices.

**Key Points:**

- All your notes, checklists, and settings stay on your device
- We do NOT sell, share, or rent your information to third parties
- The **Photo-to-Text (OCR)** feature sends images you select to a third-party OCR service for text extraction — see Section 3 for full details
- The **AI Summary** feature runs entirely on-device — no data is transmitted
- We use Google AdMob for displaying advertisements
- We use **Firebase Analytics** to understand how the app is used (anonymous, no personal data)
- We use **Firebase Crashlytics** to detect and fix crashes (anonymous crash reports only)

---

## 2. Information We Collect

**Personal Data:** We do NOT collect any personal data. Your notes, text, images, and all content you create remain stored locally on your device only.

**Usage Data:** We collect anonymous usage data via Firebase Analytics to understand how the app is used. This includes app sessions, feature interactions, and device information (model, OS version). This data is anonymous and cannot be used to identify you personally.

**Crash Data:** We collect anonymous crash reports via Firebase Crashlytics. This includes stack traces, device state at time of crash, and app version. This data is used solely to identify and fix bugs.

**Location Data:** We do NOT collect or access your precise location. Firebase Analytics may infer your approximate country/region from your IP address for aggregate reporting only.

**Feature Usage Statistics:** We collect anonymous counts of feature usage (e.g. how many times OCR or AI Summary is used, which category names are created). This data is stored locally on your device and does not include any note content.

**Photo-to-Text Images:** When you use the Photo-to-Text feature, the image you select from your gallery is transmitted to OCR.space (a third-party service) for text recognition. This image is sent over HTTPS and is used solely to extract text. We do not store or log images on our own servers. Please review [OCR.space's Privacy Policy](https://ocr.space/privacy) for details on how they handle submitted images.

---

## 3. Permissions Explained

The App requests the following permissions:

**Photo Library / Storage Permission (`READ_MEDIA_IMAGES` / `READ_EXTERNAL_STORAGE`)**
- **Purpose:** Allows you to select existing images from your gallery — either to attach to a note or to extract text via Photo-to-Text (OCR)
- **Usage:** Only accessed when you explicitly choose to pick an image
- **Storage:** Images attached to notes are stored locally on your device
- **Note:** When using Photo-to-Text, the selected image is sent to OCR.space for text recognition (see Section 2)

**Internet Permission**
- **Purpose:** Required for two features: (1) sending images to OCR.space for text recognition, and (2) displaying advertisements via Google AdMob
- **Usage:** Your notes and content are NEVER transmitted over the internet; only OCR images and anonymous ad-related data are sent

**Notifications Permission (`POST_NOTIFICATIONS`)**
- **Purpose:** Required to display reminder notifications when a note reminder you set becomes due
- **Usage:** Only triggers when you have an active reminder scheduled

**Exact Alarm Permission (`SCHEDULE_EXACT_ALARM`)**
- **Purpose:** Required to fire reminder notifications at the precise time you specified
- **Usage:** Only active when you have reminders set

**Boot Completed Permission (`RECEIVE_BOOT_COMPLETED`)**
- **Purpose:** Allows the app to restore your scheduled reminders after your device restarts, so you don't miss them
- **Usage:** Only reads previously saved reminder data from local storage after a reboot

**Vibrate Permission**
- **Purpose:** Provides haptic feedback for a better user experience
- **Usage:** Creates vibration feedback when you interact with the app

---

## 4. Third-Party Services

The App uses the following third-party services:

**OCR.space (Photo-to-Text)**
- **Purpose:** Extracts text from images you select when using the Photo-to-Text feature
- **Data Sent:** The image you select from your gallery, encoded as base64 over HTTPS
- **Privacy Policy:** [https://ocr.space/privacy](https://ocr.space/privacy)
- **Note:** We do not control OCR.space's data practices. Images are sent only when you explicitly trigger the Photo-to-Text feature.

**Google AdMob (Advertising)**
- **Purpose:** Displays advertisements in the app
- **Data Collected by AdMob:** AdMob may collect device identifiers, IP address, and advertising data for ad personalization
- **Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
- **Opt-Out:** You can opt out of personalized ads in your device settings

**Firebase Analytics (Google LLC)**
- **Purpose:** Collects anonymous usage data to help us understand how the app is used and improve the user experience
- **Data Collected:** App events, session duration, device model, OS version, and approximate country/region
- **Note:** No personal data or note content is ever shared with Firebase
- **Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
- **Opt-Out:** You can opt out via your device's advertising settings or by disabling analytics in your Google account settings

**Firebase Crashlytics (Google LLC)**
- **Purpose:** Collects anonymous crash reports to help us identify and fix bugs
- **Data Collected:** Crash logs, stack traces, device state at time of crash, app version, and OS version
- **Note:** Crash reports do not contain your notes or any personal data
- **Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

We do NOT control and are NOT responsible for third-party privacy practices. We encourage you to review their privacy policies.

---

## 5. How We Use Information

Since we do not collect your personal data:

- Your notes, text, and images are stored locally on your device
- We have NO access to your notes or content
- We do NOT sync your data to cloud servers
- We do NOT use your data for marketing purposes
- Images are only transmitted to OCR.space when you explicitly use the Photo-to-Text feature
- Reminder notifications are triggered locally on your device using data you provided
- Anonymous usage data and crash reports are collected via Firebase to improve the app
- Anonymous feature usage statistics are stored locally on your device only

---

## 6. AI Summary Feature

The AI Summary feature analyzes your note content entirely on-device using a local text processing algorithm. **No note content is transmitted to any server or external service** when using this feature. Your text never leaves your device.

---

## 7. Data Storage and Security

**Local Storage:**
- All notes, images, reminders, and app data are stored in your device's local storage
- Data is NOT encrypted by default (standard Android app storage)
- You are responsible for device security (lock screen, encryption)

**Backups:**
- If you use device backup features (Google Backup, etc.), your notes may be included in those backups
- We do NOT create or manage any backups

**Security:**
- We implement standard security practices in our app development
- Since data is local, your device security is critical
- We recommend: using a device lock screen, keeping your device OS updated, and not rooting your device

---

## 8. Data Retention

- Your data remains on your device until you delete it or uninstall the app
- Uninstalling the app will delete all locally stored notes and images
- We do NOT retain any data after app uninstallation
- Reminder notifications are cleared when you remove them in the app or uninstall

---

## 9. Children's Privacy

Our App does not knowingly collect information from children under 13 years of age. Since we do not collect any personal data, the app is safe for all ages. If you believe a child has provided information to us, please contact us, though note that we do not collect or store such information.

---

## 10. Your Rights and Choices

Since all data is stored locally on your device:

- **Access:** You have full access to all your data within the app
- **Delete:** You can delete any note, image, or reminder at any time
- **Export:** You can share individual notes using your device's share functionality
- **Control:** You have complete control over your data

**Regarding AdMob Data:**
- You can opt out of personalized ads in your device settings
- Android: *Settings → Google → Ads → Opt out of Ads Personalization*

**Regarding Firebase Analytics:**
- You can opt out via *Settings → Google → Ads → Opt out of Ads Personalization*
- Or disable analytics collection in your Google account settings

**Regarding Notifications:**
- You can disable reminder notifications at any time via *Settings → Apps → Smart Notes → Notifications*

---

## 11. International Users

The App is available worldwide. Since we do not collect or transmit your personal data:

- Your notes never leave your device
- Images are only sent to OCR.space (USA) when you use Photo-to-Text
- Anonymous usage and crash data is processed by Google Firebase (USA) servers
- Local privacy laws regarding data storage apply based on your location

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be effective when posted. We will notify you of significant changes by:

- Updating the "Last Updated" date at the top of this policy
- Showing an in-app notification (for major changes)

We encourage you to review this Privacy Policy periodically.

---

## 13. Your Consent

By using the App, you consent to this Privacy Policy and our Terms and Conditions.

---

## 14. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our privacy practices, please contact us:

**Better Engineering**

Email: [daily.gyaan.4u@gmail.com](mailto:daily.gyaan.4u@gmail.com)

We will respond to your inquiry within 48 hours.

---

## 15. Legal Compliance

This Privacy Policy complies with:

- Google Play Store policies
- General Data Protection Regulation (GDPR) principles
- California Consumer Privacy Act (CCPA) principles
- Children's Online Privacy Protection Act (COPPA)

---

## Summary

✅ We do NOT collect your personal data

✅ All notes stay on your device

✅ **Photo-to-Text** sends selected images to OCR.space for text extraction only

✅ **AI Summary** is 100% offline — nothing leaves your device

✅ **Firebase Analytics** collects anonymous usage data (no personal data, no note content)

✅ **Firebase Crashlytics** collects anonymous crash reports to fix bugs

✅ AdMob collects anonymous advertising data

✅ Reminders fire locally — no server involved

✅ No camera permission required — gallery only

✅ You have complete control over your data

---

*This Privacy Policy was last updated on May 29, 2026.*
