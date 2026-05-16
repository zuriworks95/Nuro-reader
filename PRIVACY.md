# Privacy Policy — Bionic Reader

_Last updated: May 2026_

**Bionic Reader collects no personal data.**

The extension runs entirely in your browser. There are no analytics, no
remote servers, no tracking cookies, no third-party scripts. Nothing
about your browsing is transmitted anywhere.

## What is stored

The extension uses Chrome's `chrome.storage.sync` API to remember **only**
your own settings — which features you've enabled per website, and your
preferred fixation intensity. These settings sync between your own Chrome
profiles via your Google account (the same way your bookmarks do). They
are never sent to Zuriwork or any third party.

You can clear all settings at any time by visiting `chrome://extensions`,
opening Bionic Reader's "Details" page, and removing the extension — or by
clicking **Reset this site** in the popup to clear a single site.

## Permissions explained

- **`storage`** — to save your toggles and intensity locally.
- **`activeTab`** — so the popup can apply changes to the tab you're
  currently looking at.
- **`<all_urls>`** host permission — required so the extension's reading
  aids can apply on any website you visit. The content script only reads
  and modifies the DOM of the page you're on; it never exfiltrates page
  contents.

## No data collection. No tracking.

If this changes in the future, this document will be updated and the
version bumped before any data-collecting code ships.

## Contact

Open an issue or reach out: contact@zuriwork.com
