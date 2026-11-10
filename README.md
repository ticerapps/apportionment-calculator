# Apportionment Calculator — support site

Two static pages for the App Store and Play Store listings, served at
https://ticerapps.com/apportionment-calculator/ (the ticerapps.com custom domain of the
`ticerapps/ticerapps.github.io` user site):

- `index.html` — app page and Support URL (`#support`)
- `privacy.html` — Privacy Policy URL (also served as `/apportionment-calculator/privacy`)

Both pages use the main site's `/assets/site.css`, fonts, images and `/favicon.svg`, so
they only render fully on ticerapps.com. Keep the privacy text as written unless the app changes.

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
