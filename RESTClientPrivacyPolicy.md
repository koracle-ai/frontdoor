# Privacy Policy — Koracle REST Client

**Last Updated:** April 1, 2026

## Overview

Koracle REST Client is a browser extension that allows users to send REST API requests directly from their browser. This privacy policy explains how the extension handles user data.

## Data Collection

**Koracle REST Client does NOT collect, transmit, or share any personal data with external servers or third parties.**

### What the extension stores locally

The following data is stored **locally on your device only** using the browser's built-in `chrome.storage.local` API:

- **Request History** — The HTTP method, URL, and status code of recent API requests (up to 100 entries).
- **Saved Collections** — Requests you explicitly save, including the method, URL, headers, and body content.

This data **never leaves your browser**. It is not sent to any server, analytics service, or third party.

### What the extension accesses

- **Cookies and Sessions** — The extension uses the `cookies` permission and `credentials: include` in fetch requests to send your browser's existing session cookies with API requests. This is the core functionality of the extension — allowing authenticated API requests using your active sessions. **No cookie data is read, stored, logged, or transmitted by the extension.**
- **Network Requests** — The extension makes HTTP requests **only** to URLs you explicitly enter. It never makes requests to any other server.
- **Active Tab** — The `activeTab` permission is used solely to determine the context of the current page. No page content is read or modified.

## Data Sharing

We do **not** share any data with third parties. The extension operates entirely offline (except for the HTTP requests you explicitly initiate) and has no analytics, telemetry, or tracking of any kind.

## Data Storage & Security

- All data is stored locally in the browser's extension storage.
- Data can be cleared at any time via the Settings panel inside the extension.
- Uninstalling the extension removes all stored data.

## Permissions Explained

| Permission                     | Purpose                                                                                  |
| ------------------------------ | ---------------------------------------------------------------------------------------- |
| `storage`                      | Save request history and collections locally on your device                              |
| `cookies`                      | Include browser session cookies with API requests you initiate                           |
| `activeTab`                    | Determine the current page context                                                       |
| `<all_urls>` (host permission) | Send API requests to any URL you enter — required because the extension is a REST client |

## Changes to This Policy

If we make changes to this privacy policy, we will update the "Last Updated" date above. Significant changes will be communicated through the extension's store listing or update notes.

## Contact

If you have questions about this privacy policy, please contact us at:

- **GitHub:** [https://github.com/koracle-ai](https://github.com/koracle-ai)
- **Email:** hello@koracle.ai
