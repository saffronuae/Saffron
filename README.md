# Saffron uae — Export Website

A responsive, English-language static website for a saffron export business. Designed for GitHub Pages.

## Files

- `index.html` — page content and wholesale enquiry form
- `style.css` — responsive design
- `script.js` — mobile navigation and email enquiry draft

## Before publishing

1. Open `script.js`.
2. Replace `sales@saffronuae.com` with your real business email.
3. Review all product, origin, quality, shipping and export claims. Keep only claims you can verify.
4. The enquiry form uses `mailto:`. It opens the visitor's configured email app and does not send/store enquiries by itself.
5. The product photos are remotely hosted and require an internet connection. Confirm image licensing/usage before commercial launch, or replace them with your own licensed product photos.

## Publish using GitHub Pages (free for public repositories)

1. Sign in at https://github.com/
2. Create a new **public** repository named `saffron-uae-website`.
3. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root (not inside an extra nested folder).
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then click **Save**.
7. Wait for the deployment to finish. Open the URL shown in the Pages section. It will usually be:
   `https://YOUR-USERNAME.github.io/saffron-uae-website/`

## Important limitations

GitHub Pages hosts static websites. This form does not save enquiries to a database. For a form that works without the visitor's email app, connect a form service such as Formspree or build a backend. Do not put passwords, private keys, or secret API tokens in these files.

A custom domain can be connected later in the repository's Pages settings; purchasing a domain may cost extra.
