# Changelog

The app has no version numbers. The GitHub Pages site always serves the latest `main` branch. This file lists the changes by date.

## 2026-10-19

### New
- Streamed words now fade in one by one instead of appearing all at once.
- Reply text is near-white (#f1f3f4) instead of grey, and bold is pure white, matching the Gemini app.
- Phone: the welcome screen shows a wavy pattern of tiny sparkles for about a second, like the Gemini app.

### Fixed
- Phone: the greeting and Gemini icon no longer show through the "You're in control of your settings" notice.
- Sidebar icons are sharper. The search and sidebar icons are grey again.

## 2026-10-17

### New
- Issue forms for bug reports and feature requests, `SECURITY.md`, `CONTRIBUTING.md` and a new README.

## 2026-10-16

### New
- DeepSeek, Qwen, Kimi and Llama as providers, with their logos. A provider list next to the key box, because several providers use `sk-` keys.
- Custom endpoint: send one provider's requests through your own proxy.
- Claude and ChatGPT logos on keys, in the key dialog and in the model menu.
- "Add your API key" dialog when you send a message without a key.
- The **@** menu: Avatar, your skills and the Google connectors. A compact version on phones.
- Gemini Auto: the app picks Flash or Pro for each message.
- YouTube cards under replies that link a video.
- Temporary chat, with its own start screen and grey glow.
- Images page: "Create images", aspect ratio menu, photo templates and a "Creating your image" placeholder.
- New default system instruction.

### Changed
- Settings dialog in the Material style of Google apps.
- New wording of the "You're in control of your settings" notice.
- Spacing of the sidebar logo and bottom block, measured from the real app.

### Fixed
- An empty "runtime" key caused "unregistered callers" errors.
- The key box was white in the dark theme.
- The blue glow did not come back when you opened a new chat.
- Test connection could pass while chat requests were blocked.
- Clearer errors when a provider blocks browser requests or when image creation needs billing.

## 2026-10-15

### New
- Location: typed, from your device or from your IP address, with an option to give it to the model.
- Real-style model menu with More models and Thinking level. The Gemini model list loads from the API.
- Pin icon on pinned chats.
- Gemini logo as the page icon.
- Option to use Google's current wording ("All" instead of "Recents").

### Fixed
- Chrome offered to save the API key as a password.
- The attach sheet on phones had the wrong colors.
