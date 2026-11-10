# Vikaskush policy website

Static GitHub Pages site containing:
- `index.html` — application homepage
- `privacy.html` — draft privacy policy
- `terms.html` — draft terms of service
- `style.css` — shared styling

## Before publishing
1. Replace `[ADD YOUR SUPPORT EMAIL]` in all three HTML pages with an email address you control.
2. Review the privacy policy against the app's actual implementation. In particular, do not claim encryption, deletion, or offline behaviour until those features are implemented and tested.
3. Update the last-updated date whenever the policy changes.

## Publish with GitHub Pages
1. Create a public GitHub repository named `vikaskush-legal`.
2. Upload all five files to the repository root.
3. In repository Settings → Pages, choose **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`, then Save.
5. Wait for GitHub Pages to publish the site.

Expected URLs (replace `YOUR-GITHUB-USERNAME`):
- Home: `https://YOUR-GITHUB-USERNAME.github.io/vikaskush-legal/`
- Privacy: `https://YOUR-GITHUB-USERNAME.github.io/vikaskush-legal/privacy.html`
- Terms: `https://YOUR-GITHUB-USERNAME.github.io/vikaskush-legal/terms.html`

## Google OAuth Branding
Use the published homepage and privacy-policy URLs in Google Auth Platform Branding. Add the terms URL if the console asks for it. Google may require domain verification/authorization depending on the OAuth configuration. Do not invent a custom domain or claim verification that has not happened.
