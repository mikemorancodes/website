# Mike Moran Codes website

A simple static site for GitHub Pages.

## Before publishing

1. Review the shared privacy page at `/apps/privacy/` and add accurate app-specific details as needed.
2. Confirm `support@mikemorancodes.com` is set up to receive messages.
3. Add the App Store link to `index.html` when available.

## GitHub Pages

1. Create a new GitHub repository, e.g. `mikemorancodes-website`.
2. Add these files to the repository's root.
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for the site to publish at `https://YOUR-USERNAME.github.io/mikemorancodes-website/` (or the URL GitHub displays).
6. In **Settings → Pages → Custom domain**, enter `mikemorancodes.com` and follow GitHub's instructions.
7. Configure DNS at Cloudflare using the exact records GitHub documents for your setup. If using Cloudflare as DNS, set the GitHub Pages records to **DNS only** while setting up and verifying the domain.
8. Enable **Enforce HTTPS** when GitHub makes it available.

Important: this template uses root-relative links (such as `/assets/styles.css`) intended for the custom domain. If you preview it at the project subpath before connecting your custom domain, some links may not work correctly. Test after the custom domain is connected.

Keep the domain registered at Cloudflare. You do not need to transfer it to GitHub.
