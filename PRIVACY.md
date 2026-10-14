# Privacy Policy — Portable Log Viewer

**Last updated:** October 14, 2026
**Developer:** MacG Productions
**Contact:** macgproductions@macgworld.com

Portable Log Viewer ("the extension") is a Chrome extension for reading, searching, annotating and exporting log files. This policy explains what the extension does with your data.

## Summary

- The developer does **not** collect, receive, store, sell or share any of your data. The extension has no server, no account system, no analytics and no tracking.
- Your log files are read and processed **locally in your browser**. They are never uploaded anywhere automatically.
- The only time any log content leaves your computer is when **you** click the optional AI analysis button, and it goes **directly to the AI provider you chose**, using **your own API key**.

## Data the extension handles

### Log files
When you open or drag in a log file, the extension reads it in your browser to display it. The file is not uploaded, copied to a server, or sent to the developer. The extension does not modify the original log file.

### Data stored on your device
The extension saves the following in your browser's local storage (`localStorage`) and IndexedDB for the extension. This data stays on your device and is not transmitted to the developer:

- Display preferences: theme, log format selection, column order, column widths, hidden columns and custom column names.
- Your notes and note colors, saved per log file name.
- If you use the AI feature: your chosen provider, model name, and the API key you entered.
- A reference to the most recently opened log file (used so the viewer can keep tailing it when you pop it out into a window or tab).

This data remains until you clear it, either by clearing the extension's site data in Chrome or by uninstalling the extension. Local storage is not encrypted by the extension; anyone with access to your browser profile on your computer could read it, including a stored API key.

### Exports
CSV and Annotated Log exports are generated on your device and saved through your browser's normal download mechanism. They are only written where you choose to save them.

## Optional AI analysis

The AI analysis feature is off until you use it. It requires you to enter your own API key for one of these providers:

- Anthropic (Claude) — `api.anthropic.com`
- OpenAI (ChatGPT) — `api.openai.com`
- Google (Gemini) — `generativelanguage.googleapis.com`

When you click the analyze button, the extension sends the following **directly from your browser to the provider you selected**:

- The log entries currently visible in the viewer, in the columns currently shown (up to the most recent 300 entries).
- The log format name and a short instruction prompt.
- Your API key, to authenticate the request.

Nothing is sent through any server operated by the developer. Log content can contain sensitive information such as hostnames, usernames, file paths or IP addresses, so review what is visible before you click analyze, and use filters to narrow it down if needed. Once sent, the data is handled under the chosen provider's own terms and privacy policy, and your API account's settings — not this policy:

- Anthropic: https://www.anthropic.com/legal/privacy
- OpenAI: https://openai.com/policies/privacy-policy
- Google: https://policies.google.com/privacy

## Permissions

The extension requests no Chrome API permissions. It requests access only to the three AI provider hosts listed above, and only uses them for the optional AI analysis feature. It does not read your browsing history, your open tabs, or any website's content.

## What the extension does not do

- It does not collect personal information.
- It does not use analytics, advertising, cookies or tracking.
- It does not sell or transfer user data to third parties, except the optional AI request you trigger yourself, sent to the provider you chose.
- It does not use or transfer user data for purposes unrelated to the extension's core functionality, or to determine creditworthiness or for lending.
- It does not load or run remotely hosted code.

## Children

The extension is a tool for IT and technical users and is not directed at children. It does not knowingly collect any information from anyone.

## Changes to this policy

If the extension's data handling changes, this policy will be updated and the "Last updated" date above will change. The current version is always the one in this repository.

## Contact

Questions about this policy: macgproductions@macgworld.com
