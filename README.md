# InTempo website

The public home page and privacy policy for the InTempo app. Google's sign-in setup links to these pages.

This repository is **public**, because GitHub Pages is only free for public repositories. The app's code lives in a separate, private repository. Keep anything private out of this one.

## Where it lives
- Repository: **DancingMist/DancingMist.github.io**. GitHub serves a repository with this special name at the account's root address, which Google needs so it can verify the domain.
- Live at **https://dancingmist.github.io/** (published from the `main` branch, root folder, under Settings → Pages).
- Verified in Google Search Console as a **URL prefix** property (`https://dancingmist.github.io/`), using the `google-site-verification` meta tag in `index.html`. **Don't remove that tag.** A "Domain" property can't be verified on github.io.

## Used by Google Cloud (Google Auth Platform → Branding)
- **Application home page:** `https://dancingmist.github.io/`
- **Application privacy policy link:** `https://dancingmist.github.io/privacy.html`
- **Authorised domains:** `dancingmist.github.io`

## Files
- `index.html`: the home page.
- `privacy.html`: the privacy policy. Update its "Last updated" date whenever you change it.
- `styles.css`: shared styles.
- `logo.svg`: a copy of the app logo (`InTempo/src/assets/logo.svg`).
