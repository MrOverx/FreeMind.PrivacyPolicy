# Privacy Policy for FreeMind Community

**Effective Date:** September 19, 2026  
**Last Updated:** September 19, 2026  
**Application Name:** FreeMind   
**Contact Email:** [mroverxk@gmail.com](mailto:mroverxk@gmail.com)  

---

## Privacy at a Glance (Quick Summary)

| Core Principle | Our Commitment |
|---|---|
| **Do we sell or rent your personal data?** | **Never.** We do not sell, rent, monetize, or trade any user data with any third party. |
| **Is an account or registration required?** | **No.** You can build habits and track recovery completely privately without creating an account. |
| **Where is your recovery and habit data stored?** | **100% Locally on your device** inside private application sandbox storage. |
| **Are your relapse counts or streak details uploaded?** | **No.** Sobriety streaks, dopamine threshold graphs, and relapse logs never leave your device. |
| **What does FreeMind use the internet for?** | Exclusively to fetch public community posts, announcements, media, and polls in the Community tab. |
| **Do we access your Camera, Microphone, or Contacts?** | **No.** FreeMind does not request or access camera, microphone, contacts, location, or photo gallery. |
| **Are there third-party ad networks or user tracking SDKs?** | **No.** FreeMind is completely free of advertising SDKs, ad brokers, and behavioral analytics trackers. |

---

## 1. Introduction

Welcome to **FreeMind** ("we," "our," or "us"). We are deeply committed to protecting your privacy and treating your sensitive personal recovery data with utmost care and transparency.

FreeMind is designed as an **offline-first, privacy-respecting tool** to help individuals overcome addictions, cultivate positive habits, and find inspiration through our community. This Privacy Policy explains our exact data practices, device permissions, and security measures.

By installing or using FreeMind, you acknowledge the terms described in this Privacy Policy.

---

## 2. Personal Recovery & Habit Data (100% Local On-Device)

FreeMind operates on a strict local-storage architecture for all habit-building and recovery tracking features:

- **Missions & Sobriety:** The addictions or habits you choose to overcome (e.g., Pornography/Masturbation, Social Media, Smoking, Gaming, Alcohol, Sugar/Junk Food, or Custom missions).
- **Streak & Relapse Records:** Days clean, streak milestones, relapse counts, relapse logs/timestamps, and dopamine regulation graph parameters (Base Reset and Peak Warning thresholds).
- **Good Habits:** Positive daily habits you track (e.g., Meditation, Workout, Reading, Cold Showers, Deep Work, Journaling), reminder schedules, and completion histories.
- **Application Preferences:** Theme preference (Dark / Light mode) and notification settings.

### Storage & Transmission:
- All habit and recovery records are stored exclusively in your device's local application storage (`SharedPreferences` / private sandbox).
- **This data is NEVER transmitted to external servers, cloud backups, analytics platforms, or third parties.**
- If you do not manually export or share your device screen, no one—including the developers of FreeMind—has access to your personal recovery data.

---

## 3. Community Feed & Network Operations

FreeMind includes a dedicated **Community** section designed to provide encouragement, inspiration, and shared experiences:

### What Network Requests Are Made:
- **Public Community Content:** The app connects to the official FreeMind Community API gateway (`http://13.202.30.66:8080`) to retrieve community posts, announcements, public metrics (like counts, reply counts, view counts), and community polls.
- **Media Delivery:** Community banners, logos, image attachments, and video media are delivered through Amazon Web Services (AWS S3) content delivery networks.
- **Client Authentication:** The app uses a built-in client API key to authenticate requests with the community service endpoint.

### Strict Data Isolation:
- **Zero Personal Data Leakage:** When fetching community posts, your personal habit streaks, addiction missions, relapse logs, or local settings are **never** attached, transmitted, or synchronized with the community server.
- The community service only receives standard HTTP request headers required for network routing (such as user-agent and community identifiers).

---

## 4. Device Permissions & Purpose

FreeMind requests only the minimal set of operating system permissions strictly necessary to operate its core features:

| Permission | Technical Name | Purpose & Implementation |
|---|---|---|
| **Notifications** | `POST_NOTIFICATIONS` | Used exclusively to deliver your daily habit check-in reminders and clean streak milestone alerts. Managed 100% locally by your device. |
| **Exact Alarms** | `SCHEDULE_EXACT_ALARM`, `USE_EXACT_ALARM` | Required on modern Android versions so that your custom-scheduled habit reminders trigger precisely at the specific hour and minute you selected, even during device idle or power-saving states. |
| **Reboot Persistence** | `RECEIVE_BOOT_COMPLETED` | Allows the app to automatically restore and reschedule your active habit reminder alarms after your phone restarts or powers back on. |
| **Wake Lock** | `WAKE_LOCK` | Briefly wakes the device's notification system to display your scheduled reminder without missing check-in times. |
| **Internet Access** | `INTERNET` | Required exclusively to fetch public community feed posts, polls, and media attachments from the official community server. |

### Permissions We Do NOT Request:
FreeMind **never** requests or requires access to:
- Camera or Microphone
- Contacts or Address Book
- Precise or Approximate Location (GPS)
- Device Storage / Photo Gallery (Read/Write External Storage)
- Phone State or SMS

---

## 5. Third-Party Services & Tracking

- **No Third-Party Advertising:** FreeMind does not incorporate Google AdMob, Unity Ads, Facebook Audience Network, or any other commercial ad networks.
- **No Behavioral Analytics / Fingerprinting:** We do not embed Firebase Analytics, AppsFlyer, Mixpanel, or third-party behavioral profiling trackers.
- **Open-Source Foundations:** The app is built using the open-source Flutter framework and trusted standard plugins for local notifications, preferences, and HTTP networking.

---

## 6. Data Retention, Management, and Deletion

Because all personal habits and recovery data reside exclusively on your mobile hardware:

- **Instant Data Reset:** You can erase all stored missions, habits, streaks, and preferences at any time through your device operating system:
  - **Android:** Navigate to `Settings` > `Apps` > `FreeMind` > `Storage & cache` > `Clear storage` / `Clear data`.
- **Complete Deletion upon Uninstall:** Uninstalling FreeMind immediately and permanently deletes all local application sandbox storage, habit databases, and logs from your device.
- **No Residual Server Data:** Because your recovery data was never uploaded to our servers, there are no remote records, accounts, or personal databases to delete.

---

## 7. Children's Privacy

FreeMind is designed for a general audience seeking personal habit improvement and mental wellness. We do not knowingly collect, request, or solicit personal information from children under the age of 13 (or the applicable legal age in your territory). If you believe that a minor has interacted with our services inappropriately, please contact us immediately at [mroverxk@gmail.com](mailto:mroverxk@gmail.com), and we will take immediate remedial action.

---

## 8. Security Safeguards

We prioritize the safety and privacy of your data:
- **Sandbox Protection:** Local habit and streak data is secured by Android and iOS sandboxing, preventing other installed apps from accessing FreeMind's internal data storage.
- **No Cloud Account Vulnerabilities:** Without remote user databases or password accounts, your personal recovery journey is immune to server-side credential stuffing or centralized data breaches.
- **User Recommendations:** We encourage users to maintain standard device security protections, including device screen passcodes, PINs, or biometric authentication.

---

## 9. Policy Updates & Notifications

We may revise this Privacy Policy from time to time to reflect enhancements to our application features or applicable legal standards. Any revisions will be reflected by updating the **"Last Updated"** date at the top of this document. The most current version of this policy will always remain accessible within the app and via our official store/repository links.

---

## 10. Contact Us

If you have questions, feedback, or suggestions regarding this Privacy Policy or FreeMind's privacy practices, we welcome you to reach out to us:

- **Organization:** FreeMind Community
- **Support Email:** [mroverxk@gmail.com](mailto:mroverxk@gmail.com)
- **Application:** FreeMind (`com.freemindcommunity.overxverse`)
- **Official Repository / Community:** [FreeMind Community](https://github.com/mroverx)
