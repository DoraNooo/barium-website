# Barium website

Static site (plain HTML/CSS, no build step, no cookies, no tracking): English at the root, French in `fr/`.

- `index.html`, `fr/index.html`: modules with links to the Odoo Apps Store and the demo videos.
- `guides/`, `fr/guides/`: articles that bring search traffic (PageSpeed, accessibility / EAA).
- `style.css`: shared styles. `robots.txt`, `sitemap.xml`: for search engines (domain barium-saas.fr).

Before going live:
1. `legal.html`: fill in name, address, SIRET and hosting provider (GitHub Pages: GitHub, Inc., 88 Colin P.
   Kelly Jr Street, San Francisco, CA 94107, USA).
2. GitHub: Settings > Pages > deploy from branch `main`, folder `/`.
3. DNS of barium-saas.fr: records pointing to GitHub Pages, then Settings > Pages > Custom domain
   `barium-saas.fr` and "Enforce HTTPS" (GitHub creates the CNAME file).
4. Google Search Console: add the domain and submit `https://barium-saas.fr/sitemap.xml`.
