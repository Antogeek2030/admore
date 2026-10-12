# AC Repair Ardmore OK — Astro Site

Static Astro site for **acrepairardmorepa.com**, optimized for Cloudflare Pages.

## Features
- Responsive, mobile-first design
- Cool blue + cyan color theme for AC/cooling feel
- OpenStreetMap embed for 1704 Lake Murray Dr S, Ardmore, OK 73401
- SEO: meta tags, canonical, JSON-LD LocalBusiness schema, sitemap, robots.txt
- Blog section powered by Markdown content collections
- Fast static build for Google indexing
- Cloudflare Pages ready (static output, no adapter needed)

## Phone number
Placeholder: **(580) 555-0199** — replace across the site (search for `5805550199` and `555-0199`).

## Location
1704 Lake Murray Dr S, Ardmore, OK 73401, USA

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub/GitLab repo.
2. In Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Build settings:
   - **Framework preset:** Astro
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Add custom domain `acrepairardmorepa.com`.
5. Submit `https://acrepairardmorepa.com/sitemap-index.xml` in Google Search Console.

## Local development
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```
Output is in `dist/`.

## Notes
- Site is fully static — ideal for Pages and SEO.
- `@astrojs/sitemap` generates `/sitemap-index.xml` at build time.
- `public/robots.txt` points crawlers to the sitemap.
- Blog posts live in `src/content/blog/*.md`.
