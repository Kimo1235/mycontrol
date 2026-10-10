Welcome to **Gallery Hide : Vault & Locker** ("we", "our", or "us"). We are committed to protecting and respecting your privacy. This Privacy Policy explains how our mobile application collects, uses, protects, and discloses information when you install and use **Gallery Hide : Vault & Locker** on your Android device.

By downloading, installing, or using the Application, you agree to the collection and use of information in accordance with this Privacy Policy. If you do not agree with any part of this policy, please do not use the Application.

---

## 2. Core Privacy Principle: Local On-Device Processing

> **Important:** **Gallery Hide : Vault & Locker does NOT upload, store, or transmit your personal photos, videos, or locked vault files to any remote server or cloud storage.**

All core functionalities—including viewing media, editing photos, generating collages, scanning duplicate photos, and locking media inside the private vault—operate **locally and offline on your device**. Your private media remains entirely under your personal control.

---

## 3. Information We Collect and Process

### A. Media Files and Storage Data (Processed Strictly On-Device)
* **Photos, Videos, and Albums:** We access your local storage to index, display, manage, and edit your photos and videos, and to allow you to move selected files into the protected vault.
* **EXIF and Location Metadata (`ACCESS_MEDIA_LOCATION`):** We read media metadata (such as capture date, camera details, and embedded GPS coordinates) solely to organize media, show details, and display album groupings on your device. This metadata is never transmitted to us or third parties.
* **Vault Files and Encryption:** Photos and videos hidden in the vault are protected locally. Neither we nor any external server have access to your vault files, your chosen PIN, password, or security answers.

### B. Camera and Intruder Capture Data
* **Camera Functionality:** When you choose to take a photo or capture an image for editing within the app, the camera is accessed with your explicit permission.
* **Secret Snap / Intruder Selfie:** If enabled in the vault settings, the app uses your device's front camera to capture a photo when someone repeatedly enters an incorrect PIN or password. These capture records are stored **locally on your device** in the Secret Snap gallery so that only you can review unauthorized access attempts. These photos are **never** shared, uploaded, or transmitted externally.

### C. Biometric Data (`USE_BIOMETRIC`)
* If you enable biometric authentication (such as fingerprint or face unlock) to unlock your vault, the authentication is handled exclusively by your device's operating system via official Android Biometric APIs (`BiometricPrompt`).
* **We do not collect, process, or store raw biometric data.** The app only receives a cryptographic confirmation from the Android OS indicating whether authentication succeeded or failed.

### D. Security Questions and Password Recovery
* If you set up a recovery question and answer to recover your vault PIN/password, this data is saved **locally in your device's private app preferences (`SharedPreferences`)**. It is never transmitted over the internet or uploaded to any server.

### E. Automatically Collected Data & Third-Party SDKs
While we do not collect personal photos or account credentials, our third-party service providers (such as advertising networks and analytics platforms) may automatically collect certain diagnostic and non-personally identifiable technical information:

* **Device Identifiers:** Google Advertising ID (AAID), Android ID, unique device identifiers.
* **Technical Information:** Device manufacturer, hardware model, operating system version, network connection type (Wi-Fi, cellular), carrier, and language settings.
* **App Usage & Analytics:** App open events, feature usage metrics, session durations, and general interaction events.
* **Crash & Performance Data:** Stack traces, crash dumps, system state at the time of an error, and diagnostic logs to help troubleshoot and resolve crashes.

---

## 4. Permissions Used by the Application

To deliver its core features, the Application requests the following Android runtime permissions:

| Permission | Purpose & Justification |
| :--- | :--- |
| `READ_MEDIA_IMAGES`, `READ_MEDIA_VIDEO` (Android 13+) | Allows the app to read, load, and organize photos and videos stored on your device. |
| `READ_EXTERNAL_STORAGE`, `WRITE_EXTERNAL_STORAGE` (Android 12 and below) | Allows reading media files and saving edited photos, collages, or hidden vault items to local storage. |
| `ACCESS_MEDIA_LOCATION` | Required on Android 10+ to read embedded photo location metadata (EXIF) to organize media and display file details. |
| `CAMERA` | Required to capture photos directly within the app and for the Intruder Selfie ("Secret Snap") feature when incorrect unlock attempts occur. |
| `USE_BIOMETRIC` | Enables quick and secure vault unlocking using your device's fingerprint or biometric sensor. |
| `INTERNET`, `ACCESS_NETWORK_STATE` | Required to retrieve advertisements, fetch remote app configuration, and report crash diagnostic logs. |
| `com.google.android.gms.permission.AD_ID` | Allows advertising SDKs to use the Google Advertising ID for ad frequency capping and analytics. |
| `RECEIVE_BOOT_COMPLETED`, `WAKE_LOCK`, `VIBRATE` | Used for scheduled background duplicate photo scanning reminders and haptic feedback during interactions. |

You can revoke any granted permission at any time through your device settings: **Settings > Apps > Gallery Hide : Vault & Locker > Permissions**. Note that revoking permissions may disable related functionality (such as photo viewing or intruder capture).

---

## 5. Third-Party Services and Partners

The Application integrates trusted third-party SDKs for advertising, analytics, and crash reporting. These providers process information under their own privacy policies:

1. **Google AdMob / Google Mobile Ads**
   * Purpose: Delivering banner, interstitial, and native advertisements.
   * Privacy Policy: [https://policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)
   * Partner Technologies: [https://policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites)

2. **Meta Audience Network (Facebook)**
   * Purpose: Serving relevant ads through advertising mediation.
   * Privacy Policy: [https://www.facebook.com/about/privacy/](https://www.facebook.com/about/privacy/)

3. **Google Firebase Analytics**
   * Purpose: Measuring app performance and user engagement trends.
   * Privacy Policy: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

4. **Google Firebase Crashlytics**
   * Purpose: Collecting crash logs and technical diagnosis to fix application crashes.
   * Privacy Policy: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

5. **Google Firebase Remote Config**
   * Purpose: Dynamically configuring feature flags and UI behaviors.
   * Privacy Policy: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

6. **Google Play Services**
   * Purpose: Providing foundational platform features and security services.
   * Privacy Policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

## 6. How We Use the Information

We and our service providers use collected data for the following purposes:
* **To provide and maintain the service:** Displaying media, organizing albums, editing photos, and securing private files in the vault.
* **To ensure application security:** Preventing unauthorized access through vault PINs, biometrics, and intruder selfie logs.
* **To analyze and optimize:** Identifying app crashes, bugs, and performance bottlenecks via Firebase Crashlytics.
* **To monetize the application:** Displaying relevant or non-personalized advertisements via Google AdMob and Meta Audience Network.
* **To comply with legal obligations:** Meeting applicable legal and regulatory requirements.

---

## 7. Data Retention and Deletion

* **Local User Media & Vault Content:** Your media files and vault contents remain on your device. You can delete photos, videos, or vault items at any time directly in the app. Uninstalling the application or clearing application data permanently removes all locally stored app preferences, security questions, and cached thumbnails.
* **Third-Party Analytic & Advertising Data:** Diagnostic and advertising data retained by third-party services is managed in accordance with their respective retention schedules (generally between 14 days and 14 months for Google Analytics).
* **Data Deletion Inquiries:** Because we do not operate user accounts or maintain a remote database with your personal media, we do not store your personal files on our servers. To request deletion of any third-party identifier data associated with your device, please contact us at [your-support-email@example.com].

---

## 8. User Rights and Choices (GDPR & CCPA/CPRA)

Depending on your geographic location, you may have specific privacy rights:

### European Union & UK Residents (GDPR / UK GDPR)
* **Right to Access & Portability:** You have the right to request information about personal data processed about you.
* **Right to Rectification & Erasure:** You have the right to have inaccurate personal data corrected or erased.
* **Right to Withdraw Consent:** Where data processing is based on consent, you may withdraw your consent at any time (e.g., via device permissions or ad consent dialogs).
* **Right to Lodge a Complaint:** You may lodge a complaint with your local data protection supervisory authority.

### California Residents (CCPA / CPRA)
* **Right to Know:** You may request disclosure of the categories and specific pieces of personal information collected by advertising partners.
* **Right to Delete:** You have the right to request deletion of personal information collected, subject to legal exceptions.
* **Right to Opt-Out of Sale/Sharing:** We do not "sell" your personal photos or information in exchange for money. However, the use of third-party advertising SDKs may be considered "sharing" or "targeted advertising" under California law. You may opt out of personalized ads as described below.
* **Non-Discrimination:** We will not discriminate against you for exercising any of your privacy rights.

### How to Opt Out of Interest-Based Advertising
You can reset or opt out of personalized advertisements directly from your Android device settings:
* Open **Settings > Google > Ads** (or **Settings > Privacy > Ads** on newer Android versions).
* Tap **Reset advertising ID** or tap **Delete advertising ID** to stop personalized advertising tracking across apps.

---

## 9. Children's Privacy (COPPA & GDPR-K Compliance)

Our Application is **not directed to children under the age of 13** (or under 16 in the European Economic Area). We do not knowingly solicit or collect personal information from children under these ages. If you are a parent or guardian and become aware that your child has provided personal information to third-party services through the Application, please contact us immediately so we can take appropriate corrective action.

---

## 10. Security of Your Information

The security of your data is paramount to us. We implement industry-standard protective measures:
* All media hiding and locking occurs inside sandboxed local app storage.
* Biometric authentication is managed securely by Android's hardware-backed keystore and BiometricPrompt.
* Communications between third-party SDKs and their servers (e.g., ad requests and crash reports) are transmitted using encrypted HTTPS/TLS protocols.

Please note that no method of electronic storage or internet transmission is 100% secure. You are responsible for safeguarding your device passcode, vault PIN, and pattern lock.

---

## 11. International Data Transfers

Third-party service providers (such as Google and Meta) may store and process technical data and advertising identifiers on servers located outside your country of residence, including in the United States. These companies comply with applicable international data transfer frameworks, such as Standard Contractual Clauses (SCCs).

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, legal requirements, or Android platform updates. Any updates will become effective when the revised policy is published. We encourage you to review this Privacy Policy periodically.

The date of the most recent revision is indicated at the top of this document.
