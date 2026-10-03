# Contributing to Lollipop Help Center

Use plain customer-facing language. Write for normal users, not developers.

## Voice and terminology

- Say **Authenticator**, not wallet, unless a technical note makes it unavoidable.
- Say **account**, not wallet.
- Keep security warnings simple and direct.
- Do not invent features that are not documented or implemented.

## Screenshots

Place screenshots in the relevant product folder under `assets/`.

Example:

```text
assets/chrome-authenticator/create-password.png
assets/ios-app/home.png
assets/android-app/claim-reward.png
assets/dashboard-desktop/analytics.png
```

### iOS screenshot style

Keep every iOS screenshot consistent:

- Take it on the iPhone 17 Pro simulator with a clean status bar (9:41, full battery).
- Highlight what to tap with a Lollipop red (`#E51A48`) rounded outline and dim the rest of the screen.
- Number each highlight with a red circle badge that matches the step number in the text.
- Use one highlight per step. Crop to the relevant area for small controls like the lollipop bar.
- Embed at `width="300"` inside a `<figure>`.

Use this format when a screenshot is missing:

```text
[Screenshot needed: describe the exact screen here]
```

## Page structure

Each page should help a user complete one task. Use clear headings, short paragraphs, and direct steps.
