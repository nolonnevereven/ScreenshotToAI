# Privacy Policy — Screenshot to AI

**Last Updated: April 2026**

---

## Overview

Screenshot to AI is a browser extension that captures screenshots and sends them to AI services for analysis. Supported AI services include ChatGPT, Grok, Gemini, Copilot, Perplexity, and Claude. This extension is primarily designed for Japanese users.

---

## Operating Modes

This extension offers three operating modes:

| Mode | Description |
|------|-------------|
| **Normal** | Captures a screenshot and sends it to an AI service when you click the capture button. The AI's response is displayed in the extension toolbar. |
| **Display** | Captures a screenshot and sends it to an AI service when you click the capture button. The AI's response is displayed as an overlay banner on the current page. |
| **Automatic** | Automatically and repeatedly captures screenshots and sends them to an AI service, then executes screen operations (such as clicking buttons or selecting options) based on the AI's response. See [Automatic Mode — Important Notice](#automatic-mode--important-notice) below. |

---

## Automatic Mode — Important Notice

Automatic mode uses AI to perform screen operations automatically on your behalf. **Before using this mode, you must read and agree to the following:**

- Automatic mode may cause unintended actions or results, and may violate the terms of service or applicable laws of the target service.
- It may not function correctly due to changes in the target site or differences in the operating environment.
- If any damages arise from use of this feature — including submission errors, impact on exam results or grades, account suspension or restriction, or any other losses — **the user bears full responsibility. The developer assumes no liability whatsoever.**

> Users are required to confirm their understanding and agreement each time they initiate Automatic mode.

---

## Data Collection

This extension does **NOT** collect, store, or share any user data. All processing is done locally on your device.

### What we do NOT do

- We do not collect personal information
- We do not track your browsing history
- We do not send data to external servers (other than the AI services you choose)
- We do not use analytics or tracking tools
- We do not store your screenshots on any server

### What the extension does

- Captures screenshots of the currently visible tab (only when triggered by you, or automatically in Automatic mode with your prior consent)
- Temporarily stores the screenshot in your browser's local storage
- Sends the screenshot to your chosen AI service by pasting it into that service's web interface
- In Automatic mode, reads the AI's response and executes screen operations on the current page accordingly
- Stores your preferences (image quality, prompt, destination, mode) locally in your browser

---

## Permissions Explained

| Permission | Purpose |
|------------|---------|
| `activeTab` | To capture a screenshot of the currently visible tab |
| `scripting` | To inject the toolbar UI into web pages and to automatically paste images into AI service pages; in Automatic mode, also to execute screen operations based on AI responses |
| `storage` | To save your preferences locally |
| `tabs` | To find and switch to existing AI service tabs |
| `contextMenus` | To add a right-click context menu for sending screenshots |

### Host Permissions

The extension requires access to all URLs (`<all_urls>`) for the following purposes:

- To display the quick-access toolbar on any web page you visit
- To capture screenshots of any page using the region selection feature
- To inject scripts into AI service pages to paste images automatically
- In Automatic mode, to execute screen operations on any page based on AI responses

> No data from visited pages is collected or transmitted beyond what is necessary to send your screenshot to the AI service you have chosen.

---

## Remote Code

This extension does **NOT** use any remote code. All code is contained within the extension package.

---

## Third-Party Services

When you send a screenshot to an AI service, the image is processed by that service according to its own privacy policy:

| Service | Privacy Policy |
|---------|---------------|
| OpenAI (ChatGPT) | https://openai.com/privacy |
| xAI (Grok) | https://x.ai/legal/privacy-policy |
| Google (Gemini) | https://policies.google.com/privacy |
| Microsoft (Copilot) | https://privacy.microsoft.com |
| Perplexity AI | https://www.perplexity.ai/hub/legal/privacy-policy |
| Anthropic (Claude) | https://www.anthropic.com/privacy |

---

## Disclaimer

This extension is provided "as is" without warranty of any kind. The developer is not responsible for any damages or losses arising from the use of this extension, including but not limited to damages resulting from Automatic mode operations.

---

## Contact

If you have any questions about this privacy policy, please contact us through the Chrome Web Store support page.

---

## Changes to This Policy

We may update this privacy policy from time to time. Any changes will be posted on this page.

---

## Summary

This extension processes everything locally. We do not collect any data. Your screenshots are only sent to the AI service you choose, and that happens directly in your browser. In Automatic mode, the AI's responses are used to perform screen operations on your behalf — please use this feature responsibly and at your own risk.
