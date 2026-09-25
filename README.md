# InTempo website

The public home page and privacy policy for the InTempo app. Google's sign-in setup links to these pages.

This repository is **public**, because GitHub Pages is only free for public repositories. The app's code lives in a separate, private repository. Keep anything private out of this one.

## Publish with GitHub Pages
1. In GitHub Desktop, choose **File → Add local repository…**, pick this folder, then click **create a repository** and **Create repository**.
2. Click **Publish repository**, and **untick "Keep this code private"**.
3. On github.com, open the repository and go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, then choose the `main` branch and the `/ (root)` folder. Click **Save**.
5. After a minute or two, the site is live at `https://<your-github-username>.github.io/intempo-site/`.

## Use it in Google Cloud (Google Auth Platform → Branding)
- **Application home page:** `https://<your-github-username>.github.io/intempo-site/`
- **Application privacy policy link:** `https://<your-github-username>.github.io/intempo-site/privacy.html`
- **Authorised domains:** `<your-github-username>.github.io`
- Click **Save**, then go to **Audience → Publish app**.

## Files
- `index.html`: the home page.
- `privacy.html`: the privacy policy. Update its "Last updated" date whenever you change it.
- `styles.css`: shared styles.
- `logo.svg`: a copy of the app logo (`InTempo/src/assets/logo.svg`).
