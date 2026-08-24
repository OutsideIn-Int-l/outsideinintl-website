# Outside In International Limited — Website

Static multi-page website (no build step required).

## Pages

- `index.html` — Home
- `about.html` — About (vision, mission, OUTSIDE IN core values)
- `services.html` — Services (three pillars: A/B/C)
- `process.html` — 7-step process + lifecycle
- `contact.html` — Contact form + details
- `style.css` — shared stylesheet

## Deploy on GitHub Pages

1. Push these files to the root of the `main` branch.
2. In the repo: **Settings → Pages → Source: Deploy from a branch → main / (root)** → Save.
3. The site goes live at `https://<org>.github.io/<repo>/` within a minute or two.

## Point www.outsideinintl.com at it

1. In **Settings → Pages → Custom domain**, enter `www.outsideinintl.com` and save (this creates a `CNAME` file).
2. At your DNS provider, add a **CNAME record**: `www` → `outsidein-int-l.github.io`.
3. For the apex domain (`outsideinintl.com`), add **A records** to GitHub Pages IPs: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153.
4. Tick **Enforce HTTPS** once the certificate is issued.

## Contact form

The form posts to [FormSubmit](https://formsubmit.co) targeting `info@outsideinintl.com`.
On the first submission, FormSubmit emails a one-time activation link to that inbox — click it once and all future submissions are delivered. No account needed.
