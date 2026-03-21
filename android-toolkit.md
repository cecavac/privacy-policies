# Privacy Policy — Android Toolkit

**Effective Date:** 2026-03-21

---

## Introduction

This Privacy Policy describes how Dragan Cecavac ("Service Provider", "we", "us", or "our") collects, uses, and discloses information in connection with your use of the Android Toolkit mobile application ("Application").

Android Toolkit is a professional tool intended exclusively for software development, quality assurance testing, device administration, and IT management purposes. By using the Application, you agree to the practices described in this Privacy Policy.

---

## Intended Use and Acceptable Use Policy

Android Toolkit is designed for legitimate professional and technical use cases, including but not limited to:

- Android application development and debugging
- Quality assurance testing across multiple Android devices
- IT administration of Android device fleets
- Kiosk, point-of-sale, and digital signage device configuration and maintenance
- Home automation device management
- Field diagnostics and technical support

> **⚠️ Important:** Accessing, connecting to, or interacting with any Android device using this Application without the explicit authorization of the device owner or the organization responsible for that device is strictly prohibited. The Service Provider assumes no liability for unauthorized use. Users who misuse the Application to access devices without permission may be in violation of applicable computer fraud, unauthorized access, or privacy laws.

---

## Information We Collect

### Information You Provide

The Application does not require you to create an account or submit personal information directly to the Service Provider. We do not collect, store, or transmit personally identifiable data to our servers.

### Automatically Collected Information

The Application uses the following third-party services that may automatically collect certain non-personally identifiable information:

**Firebase Analytics**
- Anonymized usage statistics and app interaction data
- Device model, operating system version, and approximate geographic region (country-level)
- Session duration and feature usage patterns
- This data is used solely to improve Application functionality and user experience

**Firebase Crashlytics**
- Crash reports and diagnostic data when the Application encounters an error
- Device state at the time of a crash (OS version, device model, available memory)
- Stack traces and error logs — these do not contain personal data or data from connected devices
- This data is used exclusively to identify and fix software bugs

**Trial Management Identifier**
- The Application generates a unique identifier tied to your device for the sole purpose of managing the 7-day free trial period
- This identifier persists across app reinstalls to prevent trial resets, and is stored securely in Firebase database
- It is app-specific — the same device will have a different identifier for other applications
- It cannot be used to identify you personally, track you across apps, or link your usage to any real-world identity

None of the above services collect data from the remote Android devices you connect to via ADB. All ADB sessions, shell commands, logcat output, file transfers, screen mirroring, and macro recordings are processed locally on your device and are never transmitted to the Service Provider or any third party.

---

## Purchases and Billing

Android Toolkit offers a 7-day free trial, after which continued use requires a one-time purchase through the Google Play Store. All billing and payment processing is handled entirely by Google Play Billing. The Service Provider does not collect, store, or process any payment card or financial information.

For information on how Google handles payment data, please refer to [Google Play's Privacy Policy](https://policies.google.com/privacy).

---

## ADB Connectivity and Device Data

The Application embeds an ADB (Android Debug Bridge) binary to enable wireless connectivity to other Android devices on the same network or VPN. In the course of using ADB features, the Application may access or display:

- Shell command output from connected devices
- Logcat logs from connected devices
- File system contents of connected devices (via file explorer)
- Bug reports, ANR traces, and tombstone files
- CPU, memory, and battery statistics
- Screen content (via device mirroring over H.264)
- Input event sequences recorded as macros

All of the above data is processed locally on your device. It is never uploaded to the Service Provider's servers. You are solely responsible for how you handle, store, or share any data obtained from connected devices.

---

## Third-Party Services

The Application integrates the following third-party services. Their respective privacy policies govern how they handle data:

- [Google Play Services](https://policies.google.com/privacy)
- [Firebase Analytics, Database & Crashlytics](https://firebase.google.com/support/privacy)
- [Google Play Billing](https://play.google.com/about/play-terms/)

**Android Robot Mascot**

The Android robot icon used in this Application is reproduced and modified from work created and shared by Google, and is used according to the terms described in the [Creative Commons 3.0 Attribution License](https://creativecommons.org/licenses/by/3.0/).

---

## Data Retention

The Service Provider does not maintain a database of user data. Crash reports and analytics data collected by Firebase are subject to Firebase's own data retention policies. You may opt out of analytics data collection through your device's settings or by adjusting permissions within the Application settings where available.

---

## Children's Privacy

Android Toolkit is a professional developer and IT tool not directed at children. The Application is not intended for use by individuals under the age of 13, and we do not knowingly collect any information from children.

---

## Security

Android Toolkit does not introduce any remote access capabilities beyond those already built into the Android operating system. Connectivity relies entirely on Android's native ADB (Android Debug Bridge) feature, which must be explicitly enabled by the user on each target device via the device's Developer Options. This is the same mechanism used when connecting to a device from a laptop or desktop computer via ADB — Android Toolkit simply allows this workflow from a mobile device instead.

Target devices manage authorization themselves: the target device must enable WiFi pairing and share the pairing code with the other device, consistent with standard ADB behavior. No connection can be established without this explicit approval step on the target device.

You are responsible for securing access to your device and ensuring that ADB connections are only established over trusted networks or VPNs. The Service Provider is not responsible for data accessed through unauthorized use of the Application.

The Service Provider strongly advises against using rooted or jailbroken devices, as such modifications may compromise the security of the Application and connected devices.

---

## Changes to This Privacy Policy

The Service Provider may update this Privacy Policy periodically. Changes will be posted to this page with an updated effective date. Continued use of the Application after any changes constitutes your acceptance of the revised policy. We encourage you to review this policy regularly.

---

## Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or the Application's data practices, please contact:

**Dragan Cecavac**
Email: [celecavac.help@gmail.com](mailto:celecavac.help@gmail.com)

---

*This Privacy Policy was last updated on 2026-03-21.*