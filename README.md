# Mohammad Mahmoud — bilingual personal website

## Contents
- `index.html`: language selector
- `ar/index.html`: Arabic homepage (RTL)
- `en/index.html`: English homepage
- `styles.css`: shared responsive styling
- `script.js`: small progressive enhancement
- `assets/`: place your profile photo here

## Add your profile photo
1. Add your chosen portrait image to `assets/`.
2. The current pages intentionally show a safe placeholder rather than a broken image. To show the photo, replace the `.portrait` placeholder in both `ar/index.html` and `en/index.html` with:
   `<div class="portrait"><img src="../assets/portrait.jpg" alt="محمد محمود / Mohammad Mahmoud"></div>`
3. Use a photo you have the right to publish. Recommended: JPG or WebP, cropped square or portrait, ideally under 500 KB.

## Before publishing
- Verify name spelling, job titles, dates, publications, and the episode titles.
- Add a dedicated professional email address after creating it. Do not publish private phone numbers unless you want to.
- Verify all publication links and add publisher/page details.
- Add a favicon and social sharing image if desired.
- If using a custom domain, buy it from a registrar, then configure DNS for the chosen host.
- Test both language versions on mobile and desktop.
- Add a privacy notice if you later add analytics, forms, cookies, or newsletter signup.
- Do not upload copyrighted full books or audio unless you have permission.

## Publish free with GitHub Pages
1. Create/sign in to a GitHub account at https://github.com/
2. Create a new **public** repository named `mohammad-mahmoud-site` (or another available name).
3. Upload the *contents* of this folder to the repository root (so `index.html`, `styles.css`, `script.js`, `ar/`, `en/`, and `assets/` appear at the top level).
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish and use the URL shown under Settings → Pages. The first deployment may take several minutes.
7. For a custom domain, purchase the domain separately and follow GitHub Pages' current custom-domain and DNS instructions: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
8. Enable HTTPS in Pages settings once available.

## Domain and email
- The domain `mohammadmahmoud.com` is only a suggested example; availability has not been checked.
- A domain purchase does not automatically include a mailbox. You can use a professional email provider or a domain registrar's email service; compare current prices and renewal terms.
- To avoid exposing your personal email, publish a separate mailbox or a contact form hosted by a trusted provider.

## Notes
This starter site is a static website. It does not include a backend, CMS, contact-form processing, or analytics. It is publishable as static files after your final content review. The publication descriptions are based on CV information supplied by the owner and are marked for bibliographic verification where needed.
