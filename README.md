# FinOps AI - Landing Page Variants

This repo contains the original FinOps AI landing page and three UI variants, each on its own branch.

## Branches

| Branch | Style | Description |
|--------|-------|-------------|
| `main` | Original | Clean landing with hero, features grid, blue accent |
| `variant-ramp` | Ramp-style | Yellow CTA, email capture, phone mockup with chat interface |
| `variant-shade` | Shade-style | Logo grid, tabs, app window mockup, floating panel |
| `variant-titan` | Titan-style | Serif font, split layout, abstract shapes, stats bar |

## Local preview

Open `index.html` in a browser or use a simple static server:

```bash
python3 -m http.server 8000
# or
npx serve .
```

## Push to new GitHub repo

To push this repo (with full git history) to a different GitHub repo:

```bash
cd finpage-variants
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
git push origin variant-ramp variant-shade variant-titan
```
