# Privacy Policy for Hide Puretech (Le Cache Misère)

**Last updated: May 2, 2026**

## 1. Introduction
This Privacy Policy describes how the "Hide Puretech" (also known as "Le Cache Misère" or "LCM") browser extension ("the Extension") handles information. We are committed to ensuring your privacy and being transparent about how we operate.

## 2. Data Collection and Usage
**The Extension does not collect, store, or transmit any of your personal data.**

### 2.1. Page Content and URLs
To provide its core functionality (filtering vehicle advertisements with specific engines), the Extension accesses:
- **Vehicle Data**: The Extension reads the text content (titles and descriptions) of supported car classifieds websites only when you are browsing them. This is done locally in your browser to identify keywords related to engine models (e.g., "Puretech", "THP").
- **URLs**: The Extension checks the URL of the tab you are visiting to determine if it matches a supported website.

**Handling**: This data is processed **exclusively in-memory** and is never stored, logged, or sent to any server.

### 2.2. User Preferences
The Extension allows you to save your settings (e.g., which motors to hide, active websites).
- **Storage**: These preferences are stored locally using your browser's \`chrome.storage.sync\` or \`chrome.storage.local\` API.
- **Syncing**: If you have browser synchronization enabled, these settings may be synced by your browser provider across your devices. We do not have access to this synchronized data.

## 3. Data Sharing
**We do not share any data with third parties.**
- No data is sent to external servers.
- No data is shared with advertisers or analytics providers.
- No data is sold or traded.

## 4. Permissions Justification
The Extension requests the following permissions for these specific reasons:
- \`storage\`: To save and retrieve your filtering preferences.
- \`tabs\`: To monitor current tab URLs and update the extension badge (showing the count of hidden ads).
- \`Content Scripts\`: To identify and hide specific advertisements on supported domains.

## 5. User Rights and Control
Since no data is collected or stored on our servers, you have full control over your data:
- **Opt-out**: You can stop all data processing by disabling or uninstalling the Extension.
- **Data Erasure**: You can clear all saved preferences by clearing your browser's extension data or uninstalling the Extension.

## 6. Supported Domains
The Extension only operates on the following domains:
- \`lacentrale.fr\`
- \`aramisauto.com\`
- \`leboncoin.fr\`
- \`autosphere.fr\`
- \`autoscout24.fr\`

## 7. Security
We follow industry best practices for browser extension development. Because the Extension operates entirely offline and does not communicate with external servers, your browsing data remains private and secure within your own browser environment.

## 8. Changes to This Policy
We may update this Privacy Policy from time to time. Any changes will be posted on this page and reflected in the "Last updated" date.

## 9. Contact
For any questions regarding this Privacy Policy, please contact us via our GitHub repository: [https://github.com/Mikaleb/LeCacheMisere](https://github.com/Mikaleb/LeCacheMisere)
