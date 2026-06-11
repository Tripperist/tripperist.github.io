---
permalink: /privacy/
title: "Privacy Policy"
---
# Tripperist — Privacy Policy

*Effective date: June 11, 2026*

---

## 1. Introduction

Tripperist ("the App") is a personal, non-commercial hobby project. This policy explains what data we collect, why we collect it, and how you can control it.

---

## 2. Data We Collect

### 2a. Account data (authenticated users only)

When you sign in via Auth0, we receive and store:

- **Auth0 subject identifier** (`sub`) — a stable, opaque ID that links your Auth0 account to our database
- **Email address** — as provided by your identity provider (Google, etc.)
- **Display name and avatar URL** — if your identity provider shares them
- **Username** — the Tripperist handle you choose during onboarding
- **Last login timestamp**

### 2b. Trip and favorites data

Trips, trip stops, and favorited places you create are stored on our servers so they sync across your devices.

### 2c. Roaming preferences

Settings you configure in the App (theme, drive-mode thresholds, location refresh interval) are stored server-side so they roam with your account.

### 2d. Audit log

We maintain a server-side audit log that records account-creation and account-deletion events. This log retains the Auth0 subject, email, and username captured at event time. It exists solely for integrity and dispute-resolution purposes and is never shared or sold.

### 2e. Location data

The App reads your device location while the App is in use (foreground only) to power Drive Mode alerts and the nearby-places view. **We do not transmit or store your location on our servers.** Location processing happens entirely on your device.

### 2f. Map tiles

Map tiles are served by OpenStreetMap infrastructure. Your IP address may be visible to OpenStreetMap tile servers when tiles are fetched. See the [OpenStreetMap Privacy Policy](https://wiki.osmfoundation.org/wiki/Privacy_Policy) for details.

---

## 3. How We Use Your Data

| Data | Purpose |
|------|---------|
| Auth0 sub / email | Authenticate you and identify your account |
| Display name / avatar | Show in the Profile screen |
| Username | Your public Tripperist handle |
| Trips / favorites | Sync your data across devices |
| Preferences | Roam your settings across devices |
| Audit log | Account integrity and dispute resolution |

We do not use your data for advertising, profiling, or any purpose beyond operating the App.

---

## 4. Data Sharing

We do not sell, rent, or share your personal data with third parties, except:

- **Auth0** — handles authentication on our behalf. Subject to the [Auth0 Privacy Policy](https://auth0.com/privacy).
- **Fly.io** — hosts our API and database. Data at rest is stored on Fly.io infrastructure.
- **Legal requirement** — if required by law or valid legal process.

---

## 5. Data Retention

Your account data is retained for as long as your account exists. When you delete your account (see Section 6), all personal data is permanently deleted from the live database immediately. The audit log entry recording the deletion event is retained for up to **60 days** as a backstop against fraud or disputes, after which it is purged.

---

## 6. Your Rights — Deleting Your Account

You can permanently delete your account and all associated data (trips, favorites, preferences) directly from the App:

**Profile → Delete Account**

Deletion is immediate and irreversible. There is no grace period or recovery option.

If you are unable to delete your account from the App, contact us at **tripperista@gmail.com** and we will complete the deletion manually within 30 days.

---

## 7. Children

The App is not directed at children under 13. We do not knowingly collect data from children under 13. If you believe a child under 13 has created an account, contact us at **tripperista@gmail.com** and we will delete it promptly.

---

## 8. Security

Account data is transmitted over HTTPS. Database access is restricted to our API service. We apply reasonable technical measures to protect your data, but no system is perfectly secure.

---

## 9. Changes to This Policy

We may update this policy from time to time. Material changes will be reflected in the effective date above. Continued use of the App after changes are posted constitutes acceptance.

---

## 10. Contact

Questions or requests regarding your data:
**tripperista@gmail.com**

This policy is governed by the laws of the State of Nevada.
