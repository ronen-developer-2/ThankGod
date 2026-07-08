# Privacy Policy for "Thank God" Chrome Extension

**Last Updated: July 8, 2026**

Your privacy is our sacred priority. This Privacy Policy explains how the "Thank God" Chrome extension handles your data with absolute transparency.

### 1. Data Collection and Usage
The "Thank God" extension is built with a **privacy-first, local-only** philosophy.

- **No Personal Data Collection**: We do not collect, store, or transmit any personal information—including names, email addresses, or account details—to any external servers.
- **Local Storage**: All data you generate is stored exclusively on your device using the `chrome.storage.local` and `chrome.storage.sync` APIs. This includes:
    - **Gratitude Journal**: Your personal reflections and journal entries remain 100% private on your device.
    - **Saved Favorites**: Blessings and quotes you choose to save for future reflection.
    - **Recent History**: The list of recent blessings you have encountered.
    - **Progress & Achievements**: Your daily streaks and unlocked spiritual milestones.
- **Data Syncing**: Your extension preferences (e.g., visual theme, notification schedules, speech settings, and content categories) are stored using the `chrome.storage.sync` API. If Chrome sync is enabled, these settings are synchronized across your own devices logged into Chrome via your Google Account. We (the developers) do not collect or have access to this data.
- **No Tracking**: We do not use cookies, analytics, tracking scripts, or advertisements. Your journey is private and uninterrupted.

### 2. Permissions and Page Interaction
The extension requests specific permissions to provide a seamless spiritual experience:

- **`storage`**: Essential for saving your journal, favorites, settings, and stats locally.
- **`scripting`**: Required to safely inject the gentle Floating Sanctuary bubble interface into the pages you browse at your scheduled times.
- **`alarms`**: Used to schedule the display of the Floating Sanctuary bubble and trigger daily reminder notifications at your chosen times.
- **`notifications`**: Required to deliver daily blessings, motivations, or affirmations directly to your desktop/system notification area.
- **Content Scripts & Host Permissions (`<all_urls>`)**: Used exclusively to display the **Floating Sanctuary** bubble on web pages you browse at your scheduled times.
    - **Intelligent Exclusion**: To respect your focused workspace, the extension automatically excludes Google domains (such as Google Search, Docs, Sheets, and Drive) and internal browser pages from bubble injection.
    - **Privacy Guarantee**: While the extension has permission to display the sanctuary on web pages, it **does not read, record, or transmit** any content from the websites you visit, nor does it track your browsing history.

### 3. Third-Party Services
The extension does not share any data with third-party services. All blessing libraries, audio logic, and core features are bundled locally within the extension package.

### 4. Security
Your data remains entirely under your control. Since no data is transmitted to our servers, your information is as secure as your own Google account and local machine.

### 5. Changes to This Policy
We may update this Privacy Policy to reflect changes in functionality or best practices. Any updates will be noted by the "Last Updated" date at the top of this document.

### 6. Contact
If you have any questions about this Privacy Policy, please reach out through the Chrome Web Store developer support channel.

---
*By using the "Thank God" extension, you agree to the terms outlined in this Privacy Policy.*
