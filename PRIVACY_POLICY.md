# Privacy Policy

**Last Updated**: January, 2026

This Privacy Policy describes how **NotebookLM Clip** (the “Extension”) handles information when you use it in Google Chrome, Microsoft Edge, or other Chromium-based browsers.

## Summary

- The Extension exports content from NotebookLM and saves it to files on your device.
- The Extension **does not** operate a backend server and **does not** transmit your data to any server controlled by the Extension publisher.
- The Extension stores only your local preferences (download folder name and toggle settings) in the browser’s extension storage.

## Information the Extension accesses

### NotebookLM content (when you run an export)

When you click **Fetch & Download**, the Extension requests notebook data from NotebookLM and processes it to generate output files (for example Markdown and JSON). This content may include text you wrote, source metadata, chat history, and built-in content such as slides, audio, video, quizzes, or flashcards, depending on what exists in the notebook and which toggles you enable.

### Active tab URL

The Extension reads the URL of your currently active tab when you start an export. This is used to confirm you are on a NotebookLM notebook page and to extract the notebook identifier.

### Download behavior

The Extension uses the browser’s downloads system to save exported files to your device. Your files are written under the download folder name you configure in the Extension popup (within your browser’s Downloads location).

### Settings stored locally

The Extension stores your preferences locally in the browser’s extension storage (`chrome.storage.local`), including:

- Download folder name
- Which export toggles are enabled (assets, images, sources, chats, JSON, etc.)

## Information the Extension does not collect

The Extension does not:

- Collect or sell personal information
- Use analytics, tracking pixels, or advertising identifiers
- Record your browsing history beyond reading the active tab URL at the moment you initiate an export
- Log or transmit the contents of your exported files to the publisher

## Where data is processed

All formatting and file generation happens locally in your browser.

Network requests made by the Extension go only to Google-operated services required for NotebookLM export and optional asset downloads, such as:

- `https://notebooklm.google.com/*`
- `https://*.googleusercontent.com/*`
- `https://*.gstatic.com/*`

These requests use your existing browser session (for example, cookies) so the Extension can access your NotebookLM data while you are signed in.

## Data sharing

The Extension does not share your data with the publisher or third parties. However, when the Extension requests NotebookLM data or downloads assets, your browser communicates with Google services as described above. Google’s handling of that data is governed by Google’s own policies.

## Data retention and deletion

- Extension settings: retained in local extension storage until you clear extension data or uninstall the Extension.
- Exported files: retained on your device until you delete them.

Uninstalling the Extension removes its stored settings.

## Security

The Extension does not embed account credentials or secret keys. It relies on your existing signed-in browser session for NotebookLM access. You should avoid installing untrusted extensions and keep your browser up to date.

## Children’s privacy

The Extension is not directed to children under 13 and does not knowingly collect personal information from children.

## Changes to this policy

If the Extension’s data practices change, this policy will be updated. The “Last Updated” date at the top indicates the latest revision.

## Contact

If you have questions about this policy, contact:

- Extension Web Store Reviews
- Extension Support Page
- Repository / issues: [Github](https://github.com/bnpdataw/notebooklm_clip)

