# American Traditional Construction — website

Static site for American Traditional Construction (CBC 1266228).

- `public/index.html` — the homepage
- `public/styles.css` — colors, fonts and layout (brand colors are at the top)
- `public/images/` — logo and photos; see `public/images/README.txt` for file names

Hosted on Cloudflare (Workers, static assets): every commit to `main` publishes automatically. `wrangler.jsonc` points Cloudflare at the `public` folder. No build step.
