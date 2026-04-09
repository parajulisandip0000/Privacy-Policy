# Privacy Policy

**Effective date:** April 9, 2026

This Privacy Policy explains how **Expense Tracker** ("the App") collects, uses, stores, and shares information.

If you do not agree with this policy, do not use the App.

## Information We Collect

The App may collect the following information, depending on the features you use:

- **SMS messages**: If you grant SMS permission, the App reads financial SMS messages on your device to detect deposits, withdrawals, refunds, fees, balance alerts, and similar transaction activity.
- **Transaction data**: Manually entered transactions, imported transaction details, categories, notes, due items, and review decisions.
- **Account information**: If you sign in, the App may use your email address, display name, and unique account identifier from Firebase Authentication or Google Sign-In.
- **Device information**: The App generates and stores a device identifier for local app operations and sync.
- **App preferences**: Settings such as currency, sync preferences, onboarding status, and custom date ranges.

## How We Use Information

We use the information above to:

- Import and organize financial SMS messages
- Track income, expenses, and due items
- Sync your data across devices when you enable sign-in and sync
- Let you export your data manually
- Improve the reliability of the App and prevent duplicate imports

## SMS Handling

The App requests `READ_SMS` permission so it can scan your inbox locally and identify financial messages.

- SMS scanning happens on your device.
- The App is designed to read only messages that match financial patterns.
- Raw SMS messages are stored locally in the App database and may be encrypted at rest on the device.
- If cloud sync is enabled, the App may upload encrypted SMS content and related metadata to your Firebase account so your data can be restored on another signed-in device.

## How We Share Information

We do **not sell** your personal information.

We may share data in these cases:

- **With service providers**: The App uses Firebase Authentication and Firestore, and may use Google Sign-In. These services process data on our behalf to provide sign-in and sync features.
- **When you choose to sync**: Transaction data, due items, preferences, and encrypted SMS-related data may be stored in your Firebase account.
- **When you export data**: If you use the export feature, the App creates a local text file that you can save or share yourself.
- **For legal reasons**: If required by law, court order, or valid legal process.

## Data Storage and Security

The App is designed to be local-first.

- Local app data is stored on your device.
- The local database is encrypted on supported builds.
- Cloud sync, when enabled, stores data in your Firebase account.
- SMS message bodies are not uploaded in plain text when sync is enabled; encrypted content is used instead.

No online system is completely secure, but we take reasonable measures to protect the data handled by the App.

## Data Retention

We keep data as long as needed to provide the App’s features.

- Local data remains on your device until you delete it, clear app data, or uninstall the App.
- If sync is enabled, cloud data remains in your Firebase account until you delete it or otherwise remove it from the App.
- Exported files remain under your control after you save or share them.

## Your Choices

You can control your data in these ways:

- Grant or deny SMS permission
- Sign in or sign out
- Enable or disable auto sync
- Delete transactions, due items, and other records inside the App
- Export your data for backup or review
- Uninstall the App to remove local data from your device

## Permissions Used

The App currently uses these Android permissions:

- `READ_SMS`
- `RECEIVE_BOOT_COMPLETED`
- `INTERNET`

The App does not intentionally request camera, microphone, or location permissions in this version.

## Children's Privacy

The App is not intended for children under 13, and we do not knowingly collect personal information from children under 13.

## Third-Party Services

The App may use:

- Firebase Authentication
- Firebase Firestore
- Google Sign-In

These services have their own privacy policies and terms.

## Changes to This Policy

We may update this Privacy Policy from time to time. If we make material changes, we will update the effective date above or provide another notice where appropriate.

## Contact

If you have questions about this Privacy Policy, contact:

**Email:** info@bytesphere.com.np

**Developer:** Bytesphere Solutions Pvt. Ltd
