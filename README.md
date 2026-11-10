# Slušaj

Live Serbian and Slovak to English subtitles for your iPhone. Listen-only, bring your own API key.

- It never speaks and never replies. It only shows text.
- No backend. The browser sends short audio chunks straight to the provider you
  pick (OpenAI or xAI) with your own API key. The key is kept only in this
  browser's localStorage on your device.
- Speech-to-text and translation can use different providers
  (e.g. xAI speech-to-text + OpenAI translation).

## Use

1. Open the page in Safari, tap Share, then "Add to Home Screen".
2. Open it from the home screen, tap the gear, pick providers, paste your API key(s), tap "Test keys".
3. Tap the big mic button and allow microphone access.
4. Put the phone in the middle of the table. Keep the screen on.

Set a monthly spending limit on your provider account.

## Files

- `index.html` – the whole app (HTML, CSS, JS inline)
- `manifest.webmanifest`, `icon-*.png` – home-screen install
