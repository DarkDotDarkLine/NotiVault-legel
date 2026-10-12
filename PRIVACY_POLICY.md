# Comprehensive Privacy Policy for NotiVault

**Last Updated / Effective Date:** October 12, 2026  
**Application Name:** NotiVault (Notification Saver & Vault)  
**Package Name:** `com.opusvale.notivault`  
**Developer Organization:** OpusVale  
**Official Support Email:** `support@opusvale.com`

---

## 1. Introduction & Overview

Welcome to **NotiVault** ("we", "our", "us", or "the App"). NotiVault is an Android utility application engineered to log, search, organize, and archive incoming Android notifications locally on your device.

We take user data protection, transparency, and privacy with utmost seriousness. This Privacy Policy provides a detailed explanation of what information is processed by NotiVault, how that information is handled, where it is stored, and your rights as a user under global privacy laws, including the **General Data Protection Regulation (GDPR)**, the **California Consumer Privacy Act (CCPA/CPRA)**, and **Google Play Developer Program Policies**.

By downloading, installing, or using NotiVault, you acknowledge that you have read and understood this Privacy Policy.

---

## 2. Special Android Permission: Notification Listener Access

To perform its primary core function—saving and archiving notifications so you do not miss critical messages—NotiVault requires access to Android's Notification Listener Service (`android.permission.BIND_NOTIFICATION_LISTENER_SERVICE`).

### A. How Notification Data is Handled
- **Data Captured:** App name, app package identifier, notification title, notification message text, post timestamp, and notification icon metadata.
- **100% Local Storage:** All captured notification content is processed strictly on your physical Android device and stored inside an encrypted local SQLite database (Room Persistence Library).
- **Zero Cloud Uploads:** **NotiVault does NOT send, transmit, backup, upload, or sync your notification messages to any cloud server, developer server, or external database.** Your private messages and notification history NEVER leave your device.
- **No Third-Party Access:** We do not sell, rent, monetize, or grant any third party access to your saved notification logs.

---

## 3. Automatically Collected Information & Ad Integration

While notification content remains strictly local, the App integrates Google Mobile Ads (Google AdMob) to serve banner and app open advertisements.

### A. Google AdMob Advertising Network
NotiVault uses **Google AdMob (Google LLC)** to display advertisements. AdMob may collect and process certain non-personally identifiable technical identifiers:
- Device IP address and location (country/city level).
- Unique Advertising Identifiers (e.g., Google Advertising ID / GAID).
- Device model, hardware configuration, and Android operating system version.
- Ad interaction statistics (impressions, clicks, and load times).

To learn more about how Google processes advertising data, please review Google's Privacy Policy:  
👉 [https://policies.google.com/privacy](https://policies.google.com/privacy)  
👉 [https://policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)

---

## 4. System Permissions & Rationale

NotiVault requests only the minimum necessary Android system permissions:

1. `android.permission.BIND_NOTIFICATION_LISTENER_SERVICE`:
   - **Purpose:** Core app function. Captures incoming notifications to archive them in your local vault.
2. `android.permission.INTERNET`:
   - **Purpose:** Network access required for Google AdMob to load advertisement banners and remote configuration updates.
3. `android.permission.ACCESS_NETWORK_STATE`:
   - **Purpose:** Checks whether the device has an active internet connection before attempting to fetch ad content.
4. `android.permission.RECEIVE_BOOT_COMPLETED`:
   - **Purpose:** Automatically restarts the notification listener service when your device reboots so notification logging continues seamlessly.
5. `android.permission.POST_NOTIFICATIONS`:
   - **Purpose:** Displays ongoing status indicators and system service alerts if required on Android 13+.

---

## 5. User Data Control, Rights & Deletion

We empower you with complete, unconstrained control over your personal data:

### A. Deleting All Saved Notification Data
You can permanently wipe all notification logs stored in the local database at any time by navigating to:  
`App Settings > Clear All Saved Data`  
Once clicked and confirmed, all stored database tables are immediately purged and unrecoverable.

### B. Revoking Notification Access
You can revoke NotiVault's permission to read notifications at any time via Android System Settings:  
`Settings > Apps > Special App Access > Notification Access > NotiVault (Toggle OFF)`

### C. Complete Data Removal via Uninstallation
Uninstalling the NotiVault application from your Android device automatically deletes the local SQLite database and all cached application files from your device storage.

---

## 6. Children’s Privacy Policy (COPPA Compliance)

NotiVault is a general audience utility tool and is not intended for children under 13 years of age (or under 16 years in the European Union). We do not knowingly collect, store, or solicit personal data from children. If you believe a minor has provided us with personal data, please contact `support@opusvale.com` immediately so we can investigate and remove any associated records.

---

## 7. Data Security Measures

Although all notification logs remain locally on your device, we implement industry-standard software architecture and security practices:
- Local database access is isolated using Android's Application Sandbox framework. No other third-party app installed on your device can access NotiVault's database files without root privileges.
- All network communications for AdMob use Secure Sockets Layer (SSL/TLS) encryption.

---

## 8. International Data Transfers & Legal Rights

Depending on your jurisdiction, you have specific data protection rights under regulations such as GDPR or CCPA:
- **Right to Access:** You can view all saved notification logs directly inside the app's Main Dashboard.
- **Right to Erasure:** You can delete all logs using the in-app "Clear All Data" feature.
- **Opt-Out of Personalized Ads:** You can reset or opt out of personalized ads at any time in your Android phone settings (`Settings > Google > Ads > Opt out of Ads Personalization`).

---

## 9. Changes to This Privacy Policy

We reserve the right to modify or update this Privacy Policy at any time. Any changes will be reflected in this file with an updated "Last Updated" date. We advise you to review this policy periodically to stay informed about how we protect your privacy.

---

## 10. Contact Information

If you have any questions, concerns, legal inquiries, or feedback regarding this Privacy Policy or NotiVault, please reach out to us:

- **Developer / Publisher:** OpusVale
- **Application:** NotiVault (`com.opusvale.notivault`)
- **Support Email:** `support@opusvale.com`
- **Website:** `https://github.com/opusvale/notivault-android`
