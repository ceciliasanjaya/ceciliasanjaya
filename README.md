# Portfolio Starter

A minimal, fast personal website ready for GitHub Pages, Netlify, or Vercel.

## Quick start (GitHub web UI)
1. Create a new repo named **yourhandle.github.io**.
2. Upload all files from this folder (or just upload `portfolio-starter.zip` and extract in the web UI).
3. Visit `https://yourhandle.github.io` in ~1–3 minutes.

## Local edit
```bash
git clone https://github.com/yourhandle/yourhandle.github.io
cd yourhandle.github.io
# Replace placeholders in index.html, resume.html, assets/og-image.svg
git add . && git commit -m "Initial site" && git push
```

## Custom domain
- In repo Settings → Pages → Custom domain: `yourname.com`, enable **Enforce HTTPS**.
- In your domain DNS, add a CNAME for `www` → `yourhandle.github.io` and A records if you want apex on GitHub Pages.

## SEO
- Keep your exact name in `<title>`, `<h1>`, and JSON-LD in `index.html`.
- Add your site link to LinkedIn, GitHub, etc.
- Submit the site to Google Search Console and your `sitemap.xml`.
