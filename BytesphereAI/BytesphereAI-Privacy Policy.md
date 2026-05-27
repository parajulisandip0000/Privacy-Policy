# Privacy Policy for Bytesphere AI

**Last Updated: May 27, 2026**

Bytesphere Solutions ("we," "our," or "us") operates the **Bytesphere AI** mobile application (the "App"). We are committed to protecting your privacy and ensuring your data remains secure. 

This Privacy Policy explains how we collect, use, store, and share your information when you use Bytesphere AI. By using the App, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information Collection and Use

Bytesphere AI is designed as a privacy-first, offline-capable assistant. We collect and process data in the following ways depending on how you use the App:

### A. Offline Usage (Default Mode)
* **Local Chats and Embeddings:** When you chat with Bytesphere AI offline, your conversations, text embeddings, and chat histories are processed locally and stored securely on your device using an offline ObjectBox database. We do not access or collect this local data.
* **Local Files and Documents:** Documents or images you import locally to build your personal knowledge base are parsed and indexed locally on your device.

### B. Cloud Account and Sync (Optional Mode)
If you choose to sign in to your account via Google Sign-In, the App unlocks cloud-sync features:
* **Account Credentials:** Authentication is managed securely through Firebase Authentication. We retrieve basic profile information (such as your display name, email address, and profile photo URL) to set up and customize your account profile.
* **Cloud Synchronization:** To sync chats across multiple devices, your chat sessions and message history are securely synchronized with our cloud database powered by Supabase.
* **Cloud Attachments:** Images or documents you upload as attachments while logged in are uploaded to our secure Supabase Storage bucket. This returns markdown URLs so you can view attachments across your authenticated devices.

### C. Web Search Feature (Optional Toggle)
* When you toggle the "Web Search" feature, the App queries DuckDuckGo Lite to fetch public web results relevant to your query. No personal profile data or history is shared with DuckDuckGo.

---

## 2. Permissions Required by the App

To provide its core features, Bytesphere AI may request the following permissions on your device:
* **Internet Access:** Required for optional Google Sign-in, Supabase database sync, CDN model downloads, and Web Search functionality.
* **Storage / Photo Library Access:** Required to pick documents (PDFs, text files) and images to attach to chats or import into the local knowledge base.
* **Camera Access:** Required to take pictures directly and attach them to chat sessions.

---

## 3. Data Storage and Security

* **Local Data:** All local data remains sandboxed within the App's private local directories on your device.
* **Cloud Data:** Synced data is transmitted securely via HTTPS and stored in Supabase databases and storage buckets behind authentication rules, preventing unauthorized access.
* **Data Deletion:** If you delete a chat session in the App, it is permanently deleted from both your local database and the Supabase cloud database. If you wish to delete your account or all synchronized cloud data completely, you can log out or request deletion by contacting support.

---

## 4. Sharing Your Information

We do **not** sell, trade, rent, or share your personal information with third parties. Your data is only used to run the App and synchronize your data between your devices.

---

## 5. Children's Privacy

Bytesphere AI does not address anyone under the age of 13. We do not knowingly collect personally identifiable information from children under 13. If you are a parent or guardian and you are aware that your child has provided us with personal information, please contact us.

---

## 6. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date. You are advised to review this Privacy Policy periodically for any changes.

---

## 7. Contact Us

If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us at:
* **Email:** [info@bytesphere.com.np]
* **Website:** [https://bytesphere.com.np](https://bytesphere.com.np)
