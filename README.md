# Mark Trifunovic — Static Site

Rebuilt from marktrifunovic.com (Wix) as a fully static site.

## Structure

```
site/
  index.html          — Home (showreel)
  films.html          — Film portfolio grid
  othercreations.html — Other creative work
  about.html          — Bio with cinematic background
  contact.html        — Contact form + direct contact info
  style.css           — All styles
```

## Deploy to Cloudflare Pages

1. Push this `site/` folder to a GitHub repo
2. Connect repo to Cloudflare Pages
3. Build command: (none — static)
4. Output directory: `/`
5. Transfer domain from Wix to Cloudflare Registrar

## Contact Form

Uses Formspree (free tier). Replace `placeholder` in contact.html with
the actual Formspree form ID after creating a free account at formspree.io.

## Notes

- Images served from Wix CDN (works as-is; swap for local files when Mark
  provides hi-res originals)
- YouTube embed ID: 7qzuFt1eGzM (Showreel 2024)
- Film title names inferred from URL slugs — confirm with Mark
