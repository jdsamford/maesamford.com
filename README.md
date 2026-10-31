# maesamford.com

Mae's babysitting website. Plain static HTML/CSS, no framework and no build step.

- `index.html` – the page
- `styles.css` – styles (Poppins from Google Fonts)
- `mae.jpg` – photo
- `favicon.svg`, `favicon.ico`, `apple-touch-icon.png` – icons
- `og-image.jpg` – 1200×630 preview image shown when the link is texted or shared
- `og-template.html` – source used to make `og-image.jpg` (screenshot it at 1200×630 to regenerate)

To preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.

Hosting: Vercel (personal Hobby account), framework preset "Other", no build command,
output directory = repo root.
