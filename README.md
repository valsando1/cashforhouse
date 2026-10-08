# Cash4Houses — Metro Atlanta Seller Landing Page

Static, mobile-responsive landing page for motivated sellers. Plain HTML/CSS, no build step.

## Structure
```
index.html              the full page
assets/images/          hero photo + FAQ video poster frames
assets/videos/          3 FAQ answer videos (10s each, 16:9 MP4)
```

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Deploy
Works on GitHub Pages, Cloudflare Pages, Netlify or any static host — point it at this folder.
GitHub Pages: repo Settings → Pages → Deploy from branch → `main` / root.

## Before going live
- [ ] Replace the two dashed placeholders in the hero (search `GoHighLevel survey embed` and `GoHighLevel form embed`) with your GHL survey + form embed code.
- [ ] Paste Meta Pixel / GTM code where marked in `<head>`.
- [ ] Link `[Privacy Policy]` and `[Terms]` in the footer (required for Meta ads).
- [ ] Swap the text logo for the real logo file if wanted.
- [ ] Review the comparison-table estimates (5–6% commission, 2–4 months) and the service-area city list.
