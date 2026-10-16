# InjeQuest · Privacy Policy

**Last updated**: 2026-10-07

InjeQuest ("the App") is developed independently by Wallace Lai. This policy explains how the App collects, uses and shares your personal data. Please read it before using the App.

---

## 1. Data we collect

### 1.1 On-device data (stays on your device)
The following is stored in the App's local database or SharedPreferences. Unless you turn on cloud sync, it is **never uploaded to any server**:

- Injection records (date, dose, site)
- Weight records (date, value)
- Progress photos (original files)
- Reminder settings (time, on/off)
- Display preferences (language, colour palette)
- S Badge balance
- Privacy-lock status
- First-launch timestamp

### 1.2 Cloud sync data (only when you sign in with Google)
If you upgrade to Pro, turn on cloud sync and sign in with a Google account, the App uploads **the on-device data above** to Google Firebase (Firestore + Storage) so it can sync across your devices. Synced data is governed by Google Firebase's data processing terms.

- Storage: Firebase Firestore + Firebase Storage
- Owner: you (stored in a folder keyed to your Google UID)
- Purpose: letting you access your own data across devices

### 1.3 Basic Google account info (at sign-in)
When you sign in with Google, the App receives:

- Email address
- Display name
- Google UID (unique identifier)

This is used only to set up your personal cloud-sync folder, never for marketing or analytics.

### 1.4 Advertising data (free tier)
On the free tier, the App shows rewarded ads through Google AdMob in exchange for S Badges. Google AdMob and its ad partners may collect:

- Advertising identifier (Android Advertising ID / iOS IDFA)
- IP address
- Approximate location (country level)
- Ad interaction events (views, clicks)
- Device type and OS version

If you are in the EU, UK or Switzerland, the App asks for your consent to personalised ads through Google's consent management tool before it first loads an ad. You can change your choice at any time under Settings → About → "Ad privacy settings". If you do not consent, the App does not request ads from Google AdMob.

See Google's Privacy Policy for how ad data is handled: <https://policies.google.com/privacy>

### 1.5 In-app purchases
The one-time Pro purchase is processed by Google Play or the Apple App Store. The App only receives the purchase receipt and never sees your payment details.

### 1.6 Anonymous crash and error reports
To find and fix bugs, the App uses Google Firebase Crashlytics. When the App crashes or hits certain errors (such as a failed sync), it sends:

- The error message and stack trace
- Device model, OS version and App version
- Time of the event and App state at the time (foreground/background, free memory, etc.)

Crash reports **do not include** your injection or weight records, photos, email address, name or Google account details, and are used only for debugging. This data is stored **anonymously** and cannot be traced back to you as an individual, which also means **we cannot look up or delete any individual report on your behalf**.

You can turn this off at any time from **Settings → Privacy → "Send anonymous crash reports"**. Once off, the App stops sending any further reports and any locally queued reports are discarded.

---

## 2. How we use your data

- On-device data: only to run the App's core features
- Cloud data: only to sync across your own devices
- Google account info: only to identify and access your cloud folder
- Ad data: processed by Google AdMob to serve ads
- Crash and error reports: only to find and fix bugs

**The App never uses your data for analytics or marketing, and never sells it to third parties.**

---

## 3. Who we share data with

- **Google Firebase**: storage platform for cloud-sync data
- **Google AdMob**: only when showing ads on the free tier
- **Google Firebase Crashlytics**: crash and error reports
- **Google Play / Apple App Store**: processing in-app purchases

Apart from these service providers, the App shares your data with no one.

---

<a id="account-deletion"></a>

## 4. Account deletion

InjeQuest's core data lives on your device — uninstalling the app permanently deletes it. If you've enabled cloud sync, you can delete your cloud account and data in either of two ways:

**In-app**: Settings → Cloud sync → Delete cloud account & data → Confirm. This removes:

- Your injection, weight and settings records in Firestore
- All your photos in Firebase Storage
- Your cloud sync account

**Email**: If you can no longer open the app, email **wallace.lai.android@gmail.com** with the subject "Delete my InjeQuest cloud data" and include the Google account you signed in with. We'll process the request within 7 days and reply with confirmation.

**Data that cannot be individually deleted**: Anonymous crash reports (Firebase Crashlytics) contain no personally identifiable information and cannot technically be mapped back to a specific user. Under GDPR Article 11 we do not retain information sufficient to re-identify you. You can turn these off anytime via Settings → Privacy → Send anonymous crash reports.

**No account required for use**: Core features (injection log, weight log, reminders, export, goal) are all usable without signing in — no account needs to be created.

---

## 5. Your rights

At any time you can:

- **View all data**: export a JSON backup from Settings
- **Delete all data**: use "Clear all records" in Settings
- **Delete your cloud account and data**: while signed in, go to Settings → Cloud sync → "Delete cloud account & data" to permanently erase all your records, photos and your cloud account from Firebase. If you can no longer use the App (e.g. you've uninstalled it), email us at the address below with the Google account you signed in with, and we will complete the deletion within 30 days
- **Turn off anonymous crash reports**: toggle Settings → Privacy → "Send anonymous crash reports" off to stop any further uploads. Because crash reports are stored anonymously and cannot be tied to a specific user, **we are unable to look up or delete individual historical reports**; if you are not comfortable with this, please turn the feature off
- **Change ad consent** (EU, UK and Switzerland): Settings → About → "Ad privacy settings"
- **Withdraw consent**: uninstall the App

If you are in the EU, UK, Switzerland or California, you also have rights under GDPR / UK GDPR / CCPA, including access, rectification, erasure, portability and objection.

---

## 6. Retention

- On-device data: until you delete it or uninstall the App
- Cloud data: until you delete it
- Ad data: per Google's retention policies

---

## 7. Children's privacy

The App is **not directed at children under 13**. Minors should use it with a parent or legal guardian. If we learn we have collected data from a child under 13, we will delete it promptly.

---

## 8. Security

- On-device data is protected by the OS sandbox; you can additionally enable the biometric privacy lock
- Cloud sync is encrypted in transit over HTTPS
- Firebase security rules restrict each folder to its owner

We do our best to protect your data but cannot guarantee absolute security. In the event of a breach, we will notify affected users as required by local law.

---

## 9. Changes to this policy

This policy may be updated from time to time. The "Last updated" date at the top will change, and material changes will be announced in the App, possibly asking you to agree again.

---

## 10. Contact

Questions about this policy:

**Developer**: Wallace Lai
**Email**: wallace.lai.android@gmail.com

---

*The App is an independently developed logging tool and does not provide medical advice, diagnosis or treatment. See the Medical Disclaimer.*
