# Privacy Policy for Progress Tracker

**Effective Date:** June 2026

## Overview
Progress Tracker is committed to protecting your privacy. This app is designed with privacy-first principles—your data belongs to you, not us.

## Data Collection & Usage

### Data We Collect

1. **Progress Entries & Tracker Data**
   - Your custom trackers (names, units, goals)
   - Your logged data points and metrics
   - Photos you attach to entries
   - All stored securely on your device

2. **iCloud Sync (CloudKit)**
   - Data is automatically synced to your private iCloud account for backup and cross-device access
   - Synced data is encrypted end-to-end using your iCloud encryption
   - You control this via iOS Settings → [Your Name] → iCloud → ProgressTracker

3. **Chat Messages (Optional)**
   - If you use the chat feature, messages are stored in our Supabase backend
   - Messages are linked to your iCloud account identifier
   - You can delete your chat history at any time in the app

4. **Usage Analytics**
   - Launch count and install date (stored locally)
   - XP and game progress (stored locally)
   - Pro purchase status (managed via Apple StoreKit)

### Data We Do NOT Collect
- Your name, email, or contact information (unless you explicitly provide it for support)
- Location data
- Device identifiers or advertising data
- Browsing or app usage history
- Biometric data (Face ID is processed locally on your device only)

## Data Storage & Security

- **Local Storage:** Your trackers and entries are stored on your device using Apple's SwiftData framework with encrypted at-rest storage.
- **iCloud Sync:** Data is encrypted and transmitted via CloudKit directly to your iCloud account. We never see the contents.
- **Chat Data:** Messages stored in Supabase are encrypted in transit (HTTPS) and at rest in our database. Only you and our backend can decrypt them using your account.

## Your Rights

You have the right to:
- **Access** your data—export or review all your progress entries in the app
- **Delete** your data—remove individual entries, trackers, or wipe your entire account

## Third-Party Services

Progress Tracker uses:
- **Apple CloudKit** — For iCloud sync
- **Supabase** — For optional chat messaging
- **Apple StoreKit** — For in-app purchases

## Contact Us

If you have questions about this privacy policy or your data:
- Email: mhasan@technic.com
- Support: https://mhasan.technic.com/support

## Changes to This Policy

We may update this privacy policy occasionally. We'll notify you of any changes by updating the "Effective Date" above.
