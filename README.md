# Apportionment Calculator — support site

Two static pages for the App Store and Play Store listings:

- `index.html` — Support URL
- `privacy.html` — Privacy Policy URL

## Publishing on GitHub Pages

1. Create a **public** repo in the `ticerapps` account, e.g. `apportionment-calculator`.
2. Push this folder to it:

   ```bash
   git remote add origin https://github.com/ticerapps/apportionment-calculator.git
   git push -u origin main
   ```

3. In the repo: **Settings ▸ Pages ▸ Build and deployment ▸ Deploy from a branch**,
   branch `main`, folder `/ (root)`, then Save.

The pages appear a minute or two later at:

- Support: `https://ticerapps.github.io/apportionment-calculator/`
- Privacy: `https://ticerapps.github.io/apportionment-calculator/privacy.html`

Those two URLs go in App Store Connect (Support URL, and App Privacy ▸ Privacy Policy URL)
and in the Play Console listing.
