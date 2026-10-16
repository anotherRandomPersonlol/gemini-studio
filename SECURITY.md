# Security policy

## Supported version

Only the latest version on the `main` branch receives fixes. The GitHub Pages site always serves that version.

## Report a vulnerability

Do not open a public issue for a security problem.

1. Open the [Security tab](../../security) of this repository.
2. Click **Report a vulnerability**.
3. Describe the problem and how to reproduce it.

You get an answer as soon as possible. This is a one-person project, so a fix can take some days.

## What counts

- Code in the page that sends an API key, a chat or other data to an address that is not the provider of that key.
- Text from a model reply, a file name or an imported chat that can run script in the page (cross-site scripting).
- A way to read the keys, chats or settings of this page from another site.

A provider that rejects a request, or a reply that is wrong, is not a security problem. Use the [bug report form](../../issues/new/choose) for that.

## How the app keeps your data

- API keys, chats, notebooks, skills and settings are saved only in the local storage of your browser.
- The page sends each key only to its own provider. If you set a custom endpoint, the page sends the key to that address.
- Location detection, if you turn it on, sends a request to `ipwho.is` (IP mode) or `api.bigdatacloud.net` (device mode).
- The page loads three libraries from `cdnjs` and `jsdelivr` (Markdown, sanitizer and syntax highlighting) and the Google Sans Flex font from Google Fonts.
- When a reply links a YouTube video, the page loads its thumbnail from `i.ytimg.com`, and the player from `youtube-nocookie.com` only when you click it.
- The page has no server and no analytics.
