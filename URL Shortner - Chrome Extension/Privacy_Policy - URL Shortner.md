# Privacy Policy — URL Shortener Extension

**Last Updated:** July 14, 2026  
**Extension Name:** URL Shortener — Instant Link Shortener  
**Extension ID:** gbmfofbmkjfmaidipmkcjaanalobgbji

---

## Overview

URL Shortener ("the Extension") is a Chrome browser extension that helps users shorten URLs they copy from web pages. This privacy policy explains what data is accessed, how it is used, and your rights regarding your information.

## Data We Access

### Clipboard Content (Only When You Copy)
- The Extension reads your clipboard **only** after a copy event to check if the copied text is a URL.
- If the text is a URL and you click "Shorten", the URL is sent to a third-party URL shortening service.
- If you click "No thanks" or ignore the prompt, nothing happens — the clipboard content is not stored or transmitted.

### Shortened URL History
- A history of shortened URLs (original URL + shortened URL) is stored **locally on your device** using Chrome's `chrome.storage.local` API.
- This data **never leaves your browser** and is not transmitted to any server we operate.
- You can clear this history at any time from the extension popup.

## Data We Do NOT Collect

- ❌ No personally identifiable information (name, email, etc.)
- ❌ No browsing history or web activity tracking
- ❌ No analytics, telemetry, or usage statistics
- ❌ No cookies, fingerprinting, or tracking pixels
- ❌ No financial, health, or authentication data
- ❌ No data sold or shared with third parties

## Third-Party Services

When you **choose** to shorten a URL, the URL is sent to one of the following third-party services via their public APIs:

| Service | Website | Privacy Policy |
|---------|---------|---------------|
| is.gd | [is.gd](https://is.gd) | [is.gd/privacy.php](https://is.gd/privacy.php) |
| CleanURI | [cleanuri.com](https://cleanuri.com) | [cleanuri.com](https://cleanuri.com) |
| TinyURL | [tinyurl.com](https://tinyurl.com) | [tinyurl.com/app/privacy](https://tinyurl.com/app/privacy) |

These services receive **only** the URL you choose to shorten. No other data is transmitted. We have no control over how these third-party services process data — please refer to their individual privacy policies.

## Permissions Used

| Permission | Purpose |
|------------|---------|
| `clipboardRead` | To read clipboard content after a copy event and detect if a URL was copied |
| `clipboardWrite` | To replace the clipboard content with the shortened URL |
| `activeTab` | To access the current tab's URL when using the "Shorten Current Page" feature |
| `storage` | To save user preferences (enabled/disabled) and URL history locally on the device |
| Host permissions (`is.gd`, `cleanuri.com`, `tinyurl.com`) | To make API requests to URL shortening services |

## Data Retention

- All data is stored locally on your device using Chrome's built-in storage.
- No data is stored on external servers operated by us.
- Data is automatically removed when you uninstall the extension.
- You can manually clear your history at any time via the extension popup.

## Children's Privacy

This Extension does not knowingly collect any information from children under the age of 13. The Extension does not require any personal information to function.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected in the "Last Updated" date at the top of this document. Continued use of the Extension after changes constitutes acceptance of the updated policy.

## Contact

If you have questions about this Privacy Policy, please contact us through:
- The Chrome Web Store support section for this extension
- Opening an issue on our GitHub repository

---

*This privacy policy applies to the URL Shortener Chrome Extension (ID: gbmfofbmkjfmaidipmkcjaanalobgbji).*
