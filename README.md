# Number Hunt — Website

Static landing page + Privacy Policy + Terms of Service for the Number Hunt
Android app, meant to satisfy Google Play Store's requirement for a publicly
hosted privacy policy URL.

No build step — plain HTML/CSS. Deploy as-is.

## Deploy on GitHub Pages

1. Push this folder's contents to a repo (or a `docs/` folder / `gh-pages` branch).
2. In the repo, go to **Settings → Pages**, pick the branch/folder that contains
   `index.html`, and save.
3. Your Privacy Policy URL for Play Console will be:
   `https://<your-username>.github.io/<repo-name>/privacy.html`

## Deploy on Netlify

1. Drag-and-drop this folder onto [app.netlify.com/drop](https://app.netlify.com/drop),
   or connect the repo and Netlify will pick up `netlify.toml` automatically
   (publish directory `.`).
2. Your Privacy Policy URL for Play Console will be:
   `https://<your-site-name>.netlify.app/privacy.html`

## Before you publish

- Replace `himelhim31@gmail.com` in `privacy.html` and `terms.html` if you want a
  different contact address.
- Replace the Google Play link in `index.html` with your real Play Store listing
  URL once the app is published.
- Update the "Last updated" dates if you edit the policy text later.
