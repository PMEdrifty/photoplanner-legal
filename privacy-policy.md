# PhotoPlanner Privacy Policy

**Effective Date:** September 23, 2026  
**Last Updated:** September 23, 2026

---

## 1. Who We Are

PhotoPlanner ("the App," "we," "our," "us") is an independent photography planning application for iOS. The data controller responsible for your information is:

Michael Pearson  
Email: michaelphotoplanner@gmail.com

---

## 2. Scope

This Privacy Policy explains what information the App collects, how it is used, how long it is kept, and what rights you have. It applies to all users of PhotoPlanner regardless of location.

---

## 3. Information We Collect and Why

### 3.1 Live Device Location
**What:** Your device's current GPS coordinates (latitude/longitude).  
**Why:** To fetch local weather conditions via Apple WeatherKit and calculate sun rise, set, and golden hour times for your area.  
**How stored:** Held in memory only while the App is in use. Never written to disk and never transmitted to our servers (we have none). When weather is requested, your coordinates are sent directly from your device to Apple's WeatherKit servers under Apple's own privacy policy.

### 3.2 Shoot Location Coordinates
**What:** The latitude and longitude of each photography shoot you plan.  
**Why:** To recalculate live weather, sun position, and conditions score when you view a shoot's detail screen.  
**How stored:** Stored locally on your device in SwiftData. Never uploaded, synced, or transmitted anywhere.

### 3.3 Saved Locations
**What:** Name, latitude, longitude, notes, and a weather summary for any location you bookmark on the Map tab.  
**How stored:** Stored locally on your device in SwiftData. Never transmitted.

### 3.4 Shoot Records
**What:** For each shoot you plan, the App stores:
- Shoot type (e.g. Wildlife, Landscape, Astrophotography)
- Subject description
- Location name and coordinates
- Date, start time, and end time
- Weather summary at time of planning
- Conditions score (0–100, calculated from weather and sun data)
- Post-shoot review notes ("How it went," "What I'd do differently")
- Internal notification identifier (a random UUID used only to manage local reminders)
- Date the shoot record was created

**How stored:** Stored locally on your device in SwiftData. Never transmitted.

### 3.5 Profile and Gear Information
**What:** Display name, bio, camera body, and lens details you enter voluntarily.  
**How stored:** Stored locally in your device's UserDefaults and SwiftData. Never transmitted.

### 3.6 Profile and Banner Photos
**What:** Images you voluntarily choose as your profile picture or banner.  
**How stored:** Saved locally on your device, encrypted using iOS Data Protection (.completeFileProtection) — inaccessible when the device is locked. Excluded from iCloud and iTunes backup. Never uploaded.

### 3.7 Notification Preferences
**What:** Whether you have enabled shoot reminders.  
**How stored:** Stored locally in your device's UserDefaults. Never transmitted.

### 3.8 Widget Data
**What:** A small summary of your next upcoming shoot (type, location name, date, conditions score), written to a shared App Group container so the widget extension can display it.  
**How stored:** Stored locally on your device. Never transmitted.

---

## 4. Notification Content on Lock Screen

When a shoot reminder fires, the notification body includes your shoot type, subject, and location name. This content may be visible on your device's lock screen to anyone who can physically see your device.

---

## 5. Information We Do Not Collect

We do not collect, process, or store:
- Your email address, Apple ID, or any account credentials
- Device identifiers, advertising IDs (IDFA), or any cross-app tracking identifiers
- Analytics, usage statistics, session recordings, or crash reports
- Payment or financial information
- Contacts, calendar entries, or data from any other app

---

## 6. Third-Party Services

### 6.1 Apple WeatherKit
When weather is requested, your device's coordinates are sent to Apple's WeatherKit service. This is governed entirely by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). We do not receive, store, or process this data.

Weather data is provided by Apple Weather, as required by Apple's WeatherKit developer agreement.

### 6.2 No Other Third Parties
The App contains no analytics SDKs, advertising networks, crash reporters, social login providers, or any other third-party frameworks.

---

## 7. Legal Basis for Processing (GDPR — EU/EEA Users)

| Data | Legal Basis |
|---|---|
| Live GPS location (for weather/sun) | Legitimate interests (Art. 6(1)(f)) |
| Shoot location coordinates (stored) | Contract performance (Art. 6(1)(b)) |
| Saved locations | Contract performance (Art. 6(1)(b)) |
| Shoot records | Contract performance (Art. 6(1)(b)) |
| Profile and gear info | Contract performance (Art. 6(1)(b)) |
| Profile photos | Consent (Art. 6(1)(a)) |
| Notification preferences | Consent (Art. 6(1)(a)) |

You may withdraw consent at any time by removing your profile image or disabling notifications in Settings.

---

## 8. International Data Transfers

Your live GPS coordinates are sent to Apple's WeatherKit service, which may process data on servers outside your country of residence. Apple applies Standard Contractual Clauses and their own data transfer mechanisms. See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). All other data remains on your device.

---

## 9. Your Rights

### 9.1 EU/EEA Users — GDPR Rights

You have the right to access, rectify, erase, restrict, port, and object to processing of your data, and to withdraw consent at any time. Because all data is stored locally on your device, you can exercise most rights directly in the App. For formal requests, contact michaelphotoplanner@gmail.com. We will respond within 30 days. You also have the right to lodge a complaint with your local supervisory authority.

### 9.2 California Users — CCPA Rights

You have the right to know what personal information we collect, delete it, and opt out of its sale (we do not sell personal information). To submit a request, email michaelphotoplanner@gmail.com. We will respond within 45 days.

---

## 10. Data Retention

All data is stored on your device for as long as you use the App. Uninstalling the App removes all locally stored data. We hold no copies of your data on any server.

---

## 11. Data Security

- Profile images are encrypted with iOS `.completeFileProtection`
- Profile images are excluded from iCloud and iTunes backup
- All data is protected by your device's hardware encryption
- We have no backend infrastructure that could be breached

---

## 12. Children's Privacy

The App is not directed at children under 13 (or under 16 in applicable EU jurisdictions). We do not knowingly collect personal information from children. Contact mep746@gmail.com if you believe a child has used the App.

---

## 13. Governing Law

This Privacy Policy is governed by the laws of **Canada/Ontario**. Disputes will be subject to the exclusive jurisdiction of the courts of **Canada/Ontario**.

---

## 14. Changes to This Policy

Changes will be reflected by updating the "Last Updated" date above. Significant changes will also be noted in the App's App Store release notes.

---

## 15. Contact

Michael Pearson  
michaelphotoplanner@gmail.com
