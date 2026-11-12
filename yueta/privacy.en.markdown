---
layout: page
title: Privacy Policy
permalink: /yueta/privacy/en/
---

# Privacy Policy

Last updated: November 12, 2026

This Privacy Policy applies to the "Yueta" (悦她) iOS application (Bundle ID: `com.yuanjingtech.yueta`, the "App"), provided by Yuanjing Tech ("we", "us").

## 1. In One Sentence

**Yueta keeps your data on your phone.** The App has no accounts, makes no network requests, and does not collect, upload, or share any of your personal data. Everything you record stays in the App's sandbox on your own device and is visible only to you.

## 2. Information We Process

The following information is entered by you and stored only on your device:

| Category | Details | Purpose |
|---|---|---|
| Cycle data | Last period start date, cycle length, phase lengths | Calculate the current cycle phase and upcoming dates |
| Check-ins | Completed daily tips and completed exercise items | Show today's progress, calendar marks, and statistics |
| Sleep records | Sleep hours you enter manually | Generate monthly sleep insights |
| Mood notes | Text you write in "Today's mood" | Shown back to you only, for your own review |
| Preferences | Reminder toggles and times, daily goal, color theme | Present the interface and reminders according to your preferences |

**None of this information is sent to any server.** The App contains no networking code and integrates no third-party SDKs (no analytics, no advertising, no crash reporting, no push provider). It does not use iCloud or CloudKit sync.

> We do **not** collect: your name, phone number, email, government ID, location, contacts, photos, clipboard, device identifiers (IDFA/IDFV), or Health app data. We do not build user profiles and do not track you across apps.

## 3. Where Data Is Stored

1. **On-device app sandbox.** The data above is JSON-serialized and stored in iOS `UserDefaults` inside the App's private sandbox. Other apps cannot read it.
2. **Not additionally encrypted, but protected by the OS.** The data is serialized rather than encrypted; its security relies on iOS sandbox isolation and device passcode encryption. We therefore recommend enabling a device passcode and Face ID / Touch ID.
3. **System backups.** If you enable iCloud Backup or back up your iPhone/iPad to a computer, App data may be included in that backup. That backup is managed by Apple (or by you) and never passes through our servers. You can disable backup under iOS "Settings → Apple ID → iCloud → Manage Account Storage → Backups", or exclude the App with desktop backup tools.
4. **No migration between devices.** Because there is no cloud sync, after switching to a new device you need to set your cycle start date again; past check-ins are not carried over.

## 4. System Permissions

The App requests exactly one permission:

- **Notifications** — used for the daily reminder, phase-start reminders, and the early-sleep reminder. All of these are **generated and scheduled locally on your device** (local notifications, scheduled at most 60 days ahead) and never pass through a push server. You can turn them off anytime in the App ("Settings → Reminders") or in iOS "Settings → Notifications → Yueta". Declining does not affect other features; you simply will not receive reminders.

The App does **not** request camera, microphone, photo library, location, contacts, calendar, Health data, or any other permission.

## 5. Sharing

The "Guide" tab offers a share button that opens the iOS system share sheet, so you can forward the general four-phase guidance to friends and family. That text is fixed educational content and **contains none of your personal records** (no dates, check-ins, sleep, or mood notes). You choose the destination in the system sheet; the App neither performs nor records the transfer.

## 6. Sharing, Transfer, and Disclosure

- **We do not sell** any of your information.
- **We do not share** your information with third parties — we neither collect nor hold it.
- **We do not transfer** data in connection with any merger or acquisition; the data never leaves your device.
- **We do not disclose** data publicly; we hold no copy to disclose.

## 7. Your Rights

Because the data lives only on your device, you can exercise every right directly and completely, without contacting us:

| Right | How |
|---|---|
| Access / export | View it in the App; take screenshots or use the system share sheet |
| Rectify | Change cycle settings under "Settings"; edit today's check-ins, sleep, and notes under "Today" |
| Delete a single record | Uncheck the item; clear the mood note and save |
| Delete all check-ins | "Settings → Data → Clear all check-in records" |
| Delete all data | Uninstall the App; iOS removes everything in its sandbox, including settings |
| Withdraw notification consent | Turn off reminders in the App, or in iOS "Settings → Notifications → Yueta" |

Deletion is irreversible, and we hold no backup to restore it — that is both the cost and the guarantee of "your data stays with you".

## 8. Sensitive Personal Information

Menstrual cycle, sleep, and mood records are sensitive personal information. Our principle is: **collect nothing, upload nothing, retain nothing on any server** — all processing happens locally on your device. Please also safeguard your device and passcode so others cannot view this content on your phone.

## 9. Children's Privacy

The App is not directed to children under 14 and is not offered to them. Because the App collects no information and has no accounts or servers, there is no scenario in which a child's personal information is collected or disclosed. If you are under 14, please use the App only under the guidance of a guardian, or do not use it.

## 10. Data Security

Our approach is to reduce risk at the source: no networking, no accounts, no third-party SDKs, no unnecessary permissions, and data that never leaves the device. This eliminates server breaches, interception in transit, and resale by third parties. Device-side risks such as loss, jailbreaking, or shared use are mitigated by your system passcode and biometrics.

## 11. Medical Disclaimer

The cycle-phase descriptions and the exercise and rest suggestions in the App are general health education, **for reference only**. They do not constitute medical advice and must not be used for diagnosis, treatment, or contraception. Individual variation is significant; trust your own body. If you experience persistent discomfort, irregular cycles, or need medication, please consult a qualified physician.

## 12. Changes to This Policy

If a future version adds networking, cloud sync, accounts, subscriptions, or third-party SDKs, we will update this Policy before that feature ships, clearly stating the new data types, purposes, and recipients, and will highlight the change in the App. Continued use means you accept the updated Policy; if you do not, you may stop using and uninstall the App.

Previous versions and revision dates of this Policy are retained on this page.

## 13. Contact Us

For any question, comment, or complaint about this Privacy Policy:

- Email: lotosbin@gmail.com
- Developer: Yuanjing Tech

We will respond within 15 business days of receiving your request.

© 2026 Yuanjing Tech
