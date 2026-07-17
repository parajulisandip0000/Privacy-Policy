# Privacy Policy for Website Tech Detector++

**Last Updated:** July 2026

Website Tech Detector++ ("the Extension") is committed to protecting your privacy. This Privacy Policy explains how your data is handled when you use the Extension.

## 1. Data Collection and Usage
**We do not collect, store, or transmit your personal data.** 

The Extension operates completely locally within your browser. All technology detection, DOM parsing, and HTTP header inspection happen securely on your machine. We do not use analytics, we do not track your browsing history, and we do not have servers that collect your data.

## 2. API Integrations & Third-Party Services
The Extension offers optional Business Intelligence features (such as Estimated Traffic and Contact Emails). These features are entirely opt-in and require you to provide your own API keys (e.g., SimilarWeb, Hunter.io). 

If you choose to use these features:
- Your API keys are saved securely and locally in your browser using Chrome's local storage. They are never sent to our servers.
- When you activate a scan, the Extension makes direct requests from your browser to the respective third-party APIs (e.g., api.similarweb.com) using the domain of the website you are currently visiting. 
- Please refer to the privacy policies of those specific third-party services regarding how they handle those API requests.

## 3. Required Permissions
The Extension requires the following permissions to function:
- **`activeTab` & `scripting`**: Required to temporarily run a secure, sandboxed script on the website you are actively viewing in order to detect frontend technologies (React, Vue, Tailwind, etc.).
- **`webRequest` & `<all_urls>`**: Required to passively inspect HTTP response headers for the websites you visit to identify server-side infrastructure (CDNs, Web Servers, HTTP/3).
- **`storage`**: Required to locally save your settings and custom API keys.

## 4. Changes to This Policy
If we make meaningful changes to how this Extension handles your data, we will update this Privacy Policy. However, our core philosophy is that your browsing data belongs to you.

## 5. Contact
If you have any questions about this Privacy Policy, please open an issue in our GitHub repository.
