# Privacy Policy — Nuggets

**Last updated: April 23, 2026**

## Who We Are

Nuggets is developed by **ymtoh.com**. You can reach us at **nuggets.support@ymtoh.com**.

---

## What Data Nuggets Collects

### Data you create
- Notes ("nuggets") you type into the app, including their content, tags, source labels, and timestamps.

This data is stored **entirely on your device** using Apple's SwiftData framework. It never leaves your device unless you explicitly enable Google Drive backup (see below).

### Data from Google Sign-In (optional)
If you choose to enable backup, you will sign in with your Google account. Nuggets reads your **Google account email address** solely to display it in the Settings screen so you know which account is connected. We do not store your Google credentials — authentication is handled entirely by Google's official Sign-In SDK.

---

## How Data Leaves Your Device

### Google Drive backup (optional, user-initiated)
If you enable backup, your nuggets, tags, and app preferences are uploaded as JSON files to the **app-specific hidden folder** in your Google Drive (`drive.appdata` scope). This folder:

- Is not visible to you in the Google Drive UI
- Cannot be read by other apps
- Is permanently deleted if you uninstall Nuggets or revoke access

Backups are encrypted in transit via HTTPS. You can disable backup or sign out at any time from Settings. Signing out removes the local auth token immediately.

### No other data leaves your device
Nuggets has no analytics SDK, no crash reporter, no ad network, and no backend server. Your notes are never read by us.

---

## Data We Do Not Collect

- Location data
- Contacts or address book
- Photos or camera (beyond what you explicitly paste into a note)
- Device identifiers or advertising IDs
- Usage analytics or behavioral tracking

---

## Third-Party Services

| Service | Purpose | Privacy Policy |
|---|---|---|
| Google Sign-In | Authentication for backup | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google Drive API | Storing your backup files in your own Drive | [Google Privacy Policy](https://policies.google.com/privacy) |

No data is shared with any other third party.

---

## Your Rights

You can:
- **Delete all your data** by deleting the app (removes all local SwiftData storage)
- **Delete your backup** by signing out of Google in Settings and revoking Nuggets' access at [myaccount.google.com/permissions](https://myaccount.google.com/permissions)
- **Export your data** via the backup JSON files in your Google Drive appdata folder

---

## Children's Privacy

Nuggets is not directed at children under 13 and does not knowingly collect data from them.

---

## Changes to This Policy

If we make material changes, we will update the "Last updated" date above. Continued use of the app after changes constitutes acceptance.

---

## Contact

Questions? Email us at **nuggets.support@ymtoh.com**.
