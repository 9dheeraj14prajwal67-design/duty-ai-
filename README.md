# Duty AI — installable website starter

## What's included
- `index.html`: mobile-friendly Duty AI interface
- `manifest.json`: installable web-app metadata
- `icon.svg`: app icon
- `sw.js`: basic offline caching for the app shell

## Publish free with GitHub Pages
1. Sign in to GitHub and create a **public** repository named `duty-ai`.
2. Upload all four files from this folder to the repository root.
3. Open repository **Settings → Pages**.
4. Under the build/deployment source, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then Save.
6. Wait for the published URL shown in the Pages section. It will usually look like `https://YOUR-USERNAME.github.io/duty-ai/`.

## Install on Android
1. Open the published HTTPS URL in Chrome.
2. Tap ⋮ → **Install app** or **Add to Home screen**.
3. Confirm and launch Duty AI from the home screen.

## Important limitations
- The image mode uses a third-party public image endpoint. Availability, privacy, rate limits, and output quality are controlled by that service; do not send sensitive prompts.
- Text and idea modes are starter templates, not full AI model responses.
- Before public or commercial launch, connect a trusted AI provider through a server-side backend. Never put private API keys in browser JavaScript.
- The included SVG icon works in many modern browsers; for maximum PWA install compatibility, add 192×192 and 512×512 PNG icons to the manifest.
- GitHub Pages publishes a website/PWA, not an app-store listing. Google Play publication is a separate process requiring app packaging, developer registration, and store review.
