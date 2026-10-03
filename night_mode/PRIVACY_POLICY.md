# Privacy Policy for Night Mode Pro

**Last Updated:** October 2026

## Overview
Night Mode Pro ("the Extension") is dedicated to protecting user privacy. This Privacy Policy outlines our data handling practices and confirms our adherence to the Google Chrome Web Store Developer Program Policies, specifically the User Data FAQ and Limited Use requirements.

---

## 1. Information Collection and Usage

**Night Mode Pro does NOT collect, store, transmit, or share any personal information or sensitive user data.**

- **No Analytics / Telemetry:** We do not include third-party trackers, Google Analytics, or diagnostic telemetry.
- **No Remote Servers:** All operations and styles are executed entirely locally within the user's browser. No outgoing network requests are initiated by the extension.
- **No Browsing History Stored:** We do not track, log, or transmit URLs visited, search queries, or content viewed by the user.

---

## 2. Chrome Extension Permissions Justification

In compliance with the Chrome Web Store Minimum Permissions Policy, Night Mode Pro only requests permissions strictly required to perform its single purpose:

### `storage`
- **Purpose:** Used strictly via `chrome.storage.sync` to save your customized preferences (dark mode toggle, brightness, contrast, color temperature/warmth, preferred theme mode, and per-site exclusion list).
- **Scope:** Preferences are synced solely through Google's encrypted Chrome Sync service to your signed-in browser profile across devices.

### `activeTab`
- **Purpose:** Enables the extension popup to identify the active tab's domain name when clicked, allowing users to toggle per-site exclusion with a single click.

### `tabs`
- **Purpose:** Used in the background service worker to update toolbar badge text (`ON` / `OFF`) based on whether the active website is enabled or on the user's exclusion list.
- **Data Handling:** Tab URLs are processed strictly in local memory to match hostname against user-defined exclusion lists; URLs are never logged, stored, or transmitted.

### Host Permissions (`<all_urls>`)
- **Purpose:** Required to inject stylesheets and dynamic CSS filter variables (such as Smart Invert and Pure Black OLED styling) across web pages to deliver night mode functionality.

---

## 3. Data Protection and Security
Because Night Mode Pro does not transmit or store personal data on any server, there is no risk of your data being breached, sold, or shared with third parties.

---

## 4. Single Purpose Policy Compliance
Night Mode Pro has a single purpose: to provide users with an eye-friendly, customizable dark mode browsing experience.

---

## 5. Contact
If you have any questions or feedback regarding this Privacy Policy, please open an issue on our GitHub repository:
[https://github.com/homeworldshadow/policies](https://github.com/homeworldshadow/policies)
