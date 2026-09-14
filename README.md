# NTCX / NOVA

English-language website for NovaTechCoreX and the NOVA smartphone accessory concept.

## Import status

The GitHub Pages deployment configuration is being prepared. The approved website source and product images still need to be imported from the saved `NTCX-NOVA-GitHub-Site.zip` archive. The website has not been published.

## Expected website files

- `index.html`
- `styles.css`
- `script.js`
- `assets/ntcx-logo.png`
- `assets/nova-hero.png`
- `assets/nova-colors.png`

Use the supplied product renders and logo. Product capabilities should be described as planned until validated; do not add invented traction, specifications, or investment figures.

## Deployment

The deployment workflow publishes the static website after changes to its files on `main`. It checks the expected source and image files before uploading a Pages artifact.

GitHub Pages must have **GitHub Actions** selected as its build source in the repository's Pages settings.

The deployment job reports the actual published URL after it succeeds.
