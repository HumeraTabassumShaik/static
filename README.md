# Social Post Static Site (SEO-friendly)


This repo contains a tiny static HTML page that imitates a social media post page and is optimized for SEO and social previews (Open Graph + Twitter Card + JSON-LD schema).


## What’s included
- `index.html` — main page with meta tags and structured data
- `preview.png` — (replace with your image)
- `robots.txt` — allows crawling and points to sitemap
- `sitemap.xml` — basic sitemap


## How to host (GitHub Pages)
1. Create a new public GitHub repository named `social-post-static-site`.
2. Add these files (index.html, preview.png, robots.txt, sitemap.xml, README.md) to the repo and commit.
3. Push to GitHub.
4. In your repo, go to **Settings → Pages** and set the publishing branch to `main` (or `gh-pages`) and folder `/ (root)`.
5. Your site will be available at `https://<USERNAME>.github.io/social-post-static-site/`.


## Tips to get the site indexed by search engines
- Replace `USERNAME` in the files with your GitHub username and update the real image URL.
- Add the site to Google Search Console and submit the sitemap: `https://USERNAME.github.io/social-post-static-site/sitemap.xml`.
- Share the URL on social media and backlinks to get crawled faster.


## Alternative free hosts
- Netlify / Vercel / Cloudflare Pages — connect the Git repo and deploy automatically.


## SEO checklist used
- Unique title & meta description
- Canonical URL
- Open Graph & Twitter Card for social previews
- JSON-LD structured data
- robots.txt and sitemap
- Fast static assets (no heavy JS)
