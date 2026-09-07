# HodlSolo.com

A lightweight static personal site designed for GitHub Pages.

## Files

- `index.html` — homepage
- `contact.html` — contact page
- `styles.css` — all styling and responsive layout
- `script.js` — mobile navigation + automatic footer year
- `favicon.svg` — site icon
- `404.html` — GitHub Pages custom 404
- `CNAME` — custom domain (`hodlsolo.com`)
- `.nojekyll` — tells GitHub Pages to serve the files as-is

## Publish on GitHub Pages

1. Create a new public repository, for example `hodlsolo`.
2. Upload all files from this folder to the root of the repository.
3. Commit them to the `main` branch.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select `main` and `/ (root)`, then save.
7. Under **Custom domain**, enter `hodlsolo.com`.
8. Configure your domain DNS as GitHub Pages requires. GitHub will show the current DNS check status in the Pages settings.
9. Once the certificate is available, enable **Enforce HTTPS**.

## Before publishing

The site deliberately does not invent a public email address. The contact page currently directs people to X, Bitcoin Events UK and Bridge2Bitcoin. When you decide which email address you want to publish, replace the `04 / EMAIL` card in `contact.html` with a `mailto:` link.

## Design direction

- terminal / retro-computing aesthetic
- ASCII artwork
- bitmap-like typography using local monospace system fonts
- restrained Bitcoin-orange accent
- no external fonts
- no analytics or tracking
- no framework or build step

## Editing

Everything is plain HTML/CSS. Text can be edited directly in GitHub's web editor without installing anything.
