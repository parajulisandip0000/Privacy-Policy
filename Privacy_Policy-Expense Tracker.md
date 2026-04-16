# Privacy Policy

**Effective date:** April 9, 2026

This Privacy Policy explains how **Expense Tracker** ("the App", "we", "our", or "us") collects, uses, stores, and shares information when you use the App.

If you do not agree with this policy, do not use the App.

## Summary

Expense Tracker is a money-management app that can:

- Read financial SMS messages on your device when you grant SMS permission
- Convert eligible bank and payment SMS into transaction records
- Let you add, edit, review, export, and sync your expense data
- Provide reminders, reports, due tracking, and account sync features

## Information We Collect

Depending on the features you use, the App may collect and process:

- **SMS data**: sender, message body, received time, import time, parse status, confidence score, and links between SMS messages and transactions
- **Transaction data**: imported and manually entered transactions, categories, notes, references, review decisions, balances, and analytics inputs
- **Due tracking data**: due items, repayment records, notes, expected return dates, and related payment history
- **Account information**: email address, display name, unique account identifier, and authentication state when you use Firebase Authentication or Google Sign-In
- **Preference data**: currency, onboarding state, report filters, sync settings, reminder settings, and similar app preferences
- **Device and technical data**: a locally generated device identifier and limited technical data needed for app storage, encryption, and sync

## How We Use Information

We use information handled by the App to:

- Detect and organize financial transaction SMS messages
- Create and maintain expense records, reports, summaries, and review queues
- Avoid duplicate imports and preserve transaction history
- Sync supported app data across the same signed-in user's devices
- Support reminders, exports, authentication, and app preferences
- Maintain app reliability, security, and data integrity

## SMS Access and Use

The App requests `READ_SMS` and `RECEIVE_SMS` so it can provide SMS-based money-management features.

- `READ_SMS` is used to scan SMS messages already stored on the device and identify eligible financial transaction messages
- `RECEIVE_SMS` is used to detect when a new SMS arrives so the App can trigger a new import
- The App is intended to use SMS access only for money-management features such as detecting debits, credits, refunds, fees, transfers, and balance alerts
- The App does **not** request call log permissions
- The App does **not** send SMS messages on your behalf
- The App is **not** the default SMS handler, default Phone handler, or default Assistant handler
- SMS data is not used for advertising, marketing, or unrelated profiling

## Storage, Encryption, and Sync

Expense Tracker is designed to be local-first.

- App data is stored in a local database on your device
- The local database uses SQLCipher, and the database passphrase is protected with Android Keystore-backed encryption
- If you enable sign-in and sync, the App uploads supported records to Firebase services associated with your account
- If sync is enabled, SMS message bodies are uploaded in encrypted form together with related metadata such as sender, timestamps, parse status, confidence, linked transaction ID, and device ID
- Transactions, due items, categories, and selected preferences may also be synced to your account
- Exported files are created only when you explicitly use the export feature

No storage or transmission method is completely secure, but we take reasonable measures to protect the data handled by the App.

## How We Share Information

We do **not sell** your personal information.

We may share or transmit information only in these cases:

- **With Firebase and Google services**: when needed to provide authentication, Google sign-in, and cloud sync features that you choose to use
- **Across your signed-in devices**: when you enable sync, the App may transfer your supported records through Firebase services so they are available on another device using the same account
- **When you export data**: exported files are created locally for you to save or share
- **For legal reasons**: if required by law, regulation, court order, or valid legal process

We do not share SMS data with third parties for advertising or data brokerage.

## Permissions Used

The current Android version of the App may request:

- `READ_SMS`
- `RECEIVE_SMS`
- `RECEIVE_BOOT_COMPLETED`
- `INTERNET`
- `POST_NOTIFICATIONS`

`POST_NOTIFICATIONS` is used for optional reminder notifications. `RECEIVE_BOOT_COMPLETED` is used to restore reminder scheduling and background work after device restart, app update, or time-setting changes.

## Your Choices

You can:

- Grant or deny SMS permission
- Enable or disable reminder notifications
- Sign in or sign out
- Enable or disable sync
- Add, edit, review, export, or delete local records inside the App
- Uninstall the App or clear app storage to remove local app data from your device

If you deny SMS permission, the App can still be used for manual entry and other non-SMS features, but automatic SMS-based import will not work.

Signing out stops account-based sync, but it does not by itself guarantee deletion of data that was already synced to backend services.

## Data Retention

We retain data for as long as needed to provide the App's features and support your use of the App.

- Local data remains on your device until you delete it in the App, clear app storage, or uninstall the App
- Synced cloud data may remain in associated backend storage until it is deleted or overwritten through supported account or service processes
- Exported files remain under your control after you create them

## Children's Privacy

The App is not intended for children under 13, and we do not knowingly collect personal information from children under 13.

## Third-Party Services

The App may use third-party services including:

- Firebase Authentication
- Firebase Firestore
- Google Sign-In

Those services operate under their own privacy policies and terms.

## Changes to This Policy

We may update this Privacy Policy from time to time. If we make a material change, we will update the effective date above and may provide additional notice where appropriate.

## Contact

If you have questions about this Privacy Policy, contact:

**Email:** info@bytesphere.com.np

**Developer:** Bytesphere Solutions Pvt. Ltd
