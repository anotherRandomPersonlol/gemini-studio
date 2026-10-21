<!-- Thank you for the change. Fill in the parts that apply and delete the others. See CONTRIBUTING.md. -->

## What changes

<!-- What does this pull request change, and why? If it copies the real Gemini app, attach a screenshot or a short screen recording of the original. -->

## Tested with

<!-- Browsers and devices, and what you did to test. Do not show API keys in screenshots or logs. -->

- [ ] Desktop browser
- [ ] Phone-size window or a phone
- [ ] Dark theme
- [ ] Light theme

## Checklist

- [ ] The app is still one file, `index.html`, with no build step.
- [ ] New styles are in the custom `<style>` block (the pre-built Tailwind stylesheet has no style for new classes).
- [ ] Each new dark color has a light version in `<style id="light-theme">`.
- [ ] Text from a model, a file or an imported chat is escaped or passed through DOMPurify before it goes into `innerHTML`.
- [ ] A key is only sent to its provider or to the custom endpoint that the user set.
- [ ] `CHANGELOG.md` is updated.
- [ ] The description has no closing keyword such as "fixes #12". The maintainer closes issues after testing.
