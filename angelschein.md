# Privacy Policy

**App name: Angelschein**
**Effective date: 2026-08-05**

---

## 1. Overview

This Privacy Policy describes how the Angelschein app ("Application") handles your data — what is stored, why, how long it is kept, and how you can delete it. Angelschein is a study app that helps users in Germany prepare for their state fishing-license ("Angelschein") exam by practicing multiple-choice questions and tracking their progress.

**Disclaimer**: The Application does not represent, and is not affiliated with, endorsed by, or an official representative of any government entity or state fishing/angling authority. Question content is prepared independently by the developer with reference to publicly available exam materials for informational and study purposes only; it is not a substitute for, and carries no guarantee of matching, the official exam.

By using the Application, you agree to the practices described here.

---

## 2. Data Collected and Stored

### 2a. Locally Stored App Data (Settings & Practice History)

The Application stores the following data **exclusively on your device**:

- Your selected German state and which question categories you have enabled
- Your test settings (e.g. all-questions mode vs. a set number of questions per category, silent mode, vibration on/off)
- A local history of your answers to practice questions (which category, whether the answer was correct, and when it was answered), used to calculate your today/last-week/last-month/total scores

**This data is never transmitted to the developer or any third party.** There is no account registration and no cloud sync — this data lives only in the Application's local storage on your device and is used solely to run the app and show you your own progress. Note that if your device has Android's system backup enabled, this local data may be included in your device's standard Android backup to your own Google Account, the same as any other app's local data; the developer has no access to that backup.

### 2b. Automatically Collected Analytics Data

The Application uses Firebase Analytics and Firebase Crashlytics (third-party services by Google), which automatically collect limited, anonymized diagnostic data to help improve app stability and usability. This may include:

- Crash reports and error diagnostics (device state, OS version, stack traces)
- Device model, operating system version, and approximate location (country-level only)
- App interaction and feature-usage statistics, and session duration

This data is anonymized and is not used to identify you personally. The Application does **not** collect or transmit an advertising identifier (Android Advertising ID) — this is explicitly disabled.

### 2c. Question Reports You Submit

The Application includes an optional "report a question" feature that lets you flag a question you believe is incorrect or unclear. If you choose to use it, the following is sent to a Firebase Realtime Database operated by the developer:

- The internal ID of the question being reported
- The Application's version number
- The free-text message you write

This is only sent if you actively open the report dialog and tap submit — it is never sent automatically. Please avoid including personal information in your report message. Since this feature does not require an account, the developer cannot verify who submitted a given report; if you'd like a report you submitted removed, contact the developer (see Section 14) with enough detail (e.g. the question and approximate time of submission) to identify it.

### 2d. Data the Developer Does NOT Collect

- Your name, email address, or any account/login information — the Application has no account system
- Precise GPS or location data
- Payment or financial information — the Application is free with no in-app purchases
- Photos, contacts, or any other device content

---

## 3. Purpose of Data Use

| Data Type | Purpose |
|-----------|---------|
| Local settings & practice history | Stored on-device to run the app and show your own progress and scores |
| Anonymized analytics (Firebase Analytics / Crashlytics) | App stability monitoring, crash diagnostics, and usability improvements |
| Question reports (Firebase Realtime Database) | Letting the developer identify and correct wrong or unclear exam questions |

---

## 4. Data Retention

**Locally stored settings and practice history** are retained on your device for as long as the Application is installed. The developer does not hold any copy of this data.

**Anonymized analytics data** collected by Firebase Analytics and Crashlytics is retained in accordance with Google's data retention policies. See [Firebase Privacy and Security](https://firebase.google.com/support/privacy) for details.

**Question reports** are retained in the developer's Firebase Realtime Database until deleted. They are kept only to review and act on reported issues, and are periodically cleaned up once addressed.

---

## 5. Data Deletion

### Deleting your local settings and practice history

Because this data is stored only on your device, you are in full control of it:

1. Use the Application's settings to change or reset individual preferences.
2. **Uninstall the Application** — this permanently removes all locally stored app data from your device.

> ⚠️ Uninstalling the app deletes your local practice history permanently. There is no cloud backup or recovery through the Application itself.

The developer has no copy of this data and cannot delete or recover it on your behalf.

### Deleting a submitted question report

Contact the developer at **celecavac.help@gmail.com** with details identifying your report (see Section 2c), and it will be removed.

### Deleting anonymized analytics data

Crash and analytics data collected via Firebase is anonymized and not linked to your identity, so the developer has no way to locate or delete an individual record. This data ages out automatically under [Firebase's own data retention policies](https://firebase.google.com/support/privacy). If you wish to stop this data from being collected in the first place, you may opt out through your device's ad/analytics settings, or through [Google's privacy portals](https://myaccount.google.com/data-and-privacy).

---

## 6. Data Sharing

The developer does **not** sell, trade, or share your data with any third parties.

Anonymized, non-identifiable diagnostic data may be processed by Firebase Analytics and Crashlytics as described in Section 2b, and question reports you choose to submit are stored in the developer's Firebase Realtime Database as described in Section 2c. Neither can be used to identify you as an individual unless you choose to include identifying details in a report's free-text message. See Section 8 for how this may change if advertising or affiliate partnerships are introduced.

---

## 7. Third-Party Services

The Application integrates the following third-party services, each with their own terms and privacy policies:

- [Google Play Services – Privacy Policy](https://policies.google.com/privacy)
- [Firebase Analytics, Realtime Database & Crashlytics](https://firebase.google.com/support/privacy)

---

## 8. Advertising & Affiliate Partnerships

The Application does not currently display advertising or participate in any affiliate/referral programs. The developer reserves the right to introduce advertising (for example, through a network such as Google AdMob) or affiliate/referral partnerships in a future update without further amending this Privacy Policy, provided such features operate within the scope described below.

If introduced, an advertising or affiliate partner may automatically collect information such as:

- Device identifiers and general device/OS information
- IP address and approximate location (country/region level)
- Ad interaction data (e.g. impressions and clicks) used for ad delivery, frequency capping, and measurement

Such partners are governed by their own privacy policies, and any personalized/targeted advertising would remain subject to the consent and opt-out controls required by Google Play and applicable law (for example, via your device's Settings > Privacy > Ads, or Google's [Ads Settings](https://adssettings.google.com/)). The developer will not sell your data to advertising or affiliate partners; any data shared would be limited to what is necessary for those partners to serve or measure ads and referrals.

---

## 9. Permissions

The Application requests the following device permission:

- **Vibration (`VIBRATE`)** — used to give haptic feedback when you answer a practice question correctly or incorrectly. This can be turned off in the Application's settings.

The Application does not request location, camera, microphone, contacts, storage, or any other sensitive device permissions.

---

## 10. Children's Privacy

Angelschein is a general-audience study app for a fishing-license exam and is not directed at children. The Application does not knowingly collect personal information from children under 13. If you believe a child has provided personal information through the question-report feature described in Section 2c, please contact the developer so it can be removed.

---

## 11. Security

The Application's connections to Firebase (Analytics, Crashlytics, and the Realtime Database used for question reports) are made over HTTPS. No user credentials or account data exist to be compromised, since the Application has no account system.

You are responsible for the security of your own device. The developer advises against using rooted or jailbroken devices, as such modifications may compromise the security of the Application and its local data.

---

## 12. Internet Connectivity

The Application's core study features — practicing questions and reviewing your local progress — work fully offline, since question content is bundled with the app rather than downloaded. An internet connection is used only for analytics, crash reporting, and submitting question reports. If certain features are unavailable due to lack of Wi-Fi or mobile data, this does not affect your ability to study. Standard carrier data charges may apply if you use the Application over a mobile network.

---

## 13. Changes to This Privacy Policy

This Privacy Policy may be updated periodically. Changes will be posted on this page with a revised effective date. Continued use of the Application after changes are posted constitutes your acceptance of the updated policy.

---

## 14. Contact Us

For any questions, concerns, or data-related requests regarding this Privacy Policy, please contact:

**Dragan Cecavac**
Email: [celecavac.help@gmail.com](mailto:celecavac.help@gmail.com)

---

*This Privacy Policy applies solely to the Angelschein Application and does not extend to any linked third-party services.*
