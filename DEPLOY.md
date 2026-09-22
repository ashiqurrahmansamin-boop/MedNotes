# Publish MedNotes

This package is ready for static hosting.

## Easiest options

### GitHub Pages
1. Create a GitHub repository, e.g. `mednotes`.
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`.
5. Save. GitHub will provide the public site address.
6. Replace `YOUR-DOMAIN.example` in `robots.txt` and `sitemap.xml` with the final site address.

### Netlify
1. Create an account at Netlify.
2. Choose **Add new site → Deploy manually**.
3. Upload this folder (or drag the folder into the deployment area).
4. Netlify will give you a public URL.
5. Replace `YOUR-DOMAIN.example` in `robots.txt` and `sitemap.xml` with your final domain.

### Custom domain
After hosting, connect a domain such as `mednotes.example` through the host's domain settings. HTTPS should be enabled by the host.

## Before publishing
- Replace placeholder author/about text with your own details.
- Review every medical claim and reference.
- Add real DOI/PMID/guideline links to articles.
- Replace the demo newsletter form with a real email service if you want subscriptions.
- Update `robots.txt` and `sitemap.xml` after choosing the final domain.
- Do not publish identifiable patient information.

## Important
The newsletter form in this starter is a demo UI; it does not actually send emails until connected to an email/newsletter provider.
