# Contributing

Thank you for helping to make Gemini Studio better. This page tells you how to report a problem and how to send a code change.

## Report a problem

Before you report:

1. Hard-refresh the page (Ctrl+Shift+R, or Cmd+Shift+R on a Mac) to get the latest version.
2. In Settings > API keys, click **Test**. The result tells you if the provider can be reached from your browser.
3. Look at the [open issues](../../issues). If the same problem is there, add a comment to that issue.

Then [open an issue](../../issues/new/choose) with the bug report form.

**Do not paste API keys** in issues, logs or screenshots. Issues are public.

## Ask for a feature

Use the feature request form. If the feature copies the real Gemini app, attach a screenshot or a short screen recording. Most of this app was built from such references.

## Send a code change

1. Fork the repository and make a branch from `main`.
2. Make the change in `index.html`.
3. Obey the code rules below.
4. Open the page in a desktop browser and in a phone-size window. Check the dark theme and the light theme.
5. Open a pull request. Tell what you changed and how you tested it.

### Code rules

- Keep the app one file, `index.html`. Do not add a build step: GitHub Pages serves the file as it is.
- The page uses a pre-built Tailwind stylesheet. A new Tailwind class has no style. Put new styles in the custom `<style>` block instead.
- The light theme is in `<style id="light-theme">`. When you add a dark color, add the light version too.
- Put app logic in the `GeminiApp` class. Use `const` and `let`, not `var`.
- Never put text from a model, a file or an imported chat into `innerHTML` without escaping it or passing it through DOMPurify.
- Never send a key to an address that is not its provider or the custom endpoint that the user set.

## License

When you send a change, you agree that it is published under the [MIT license](LICENSE) of this repository.
