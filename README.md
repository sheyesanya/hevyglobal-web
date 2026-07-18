# Hevy Global — Website

Master homepage for hevyglobal.com, built from a Stitch export and hand-polished.

## Structure
```
index.html              — the site (single page for now)
assets/images/           — logo + photography
  logo.png
  hero-hq.jpg
  executive-keynote.jpg
  boardroom.jpg
  network-abstract.jpg
  brandcasta-preview.jpg
DESIGN.md                — Stitch's original design token notes
```

## Local preview
No build step needed — it's plain HTML + Tailwind (via CDN). Just open `index.html`
in a browser, or serve it locally:
```
npx serve .
```

## Deploy (Vercel)
1. Push this folder to a GitHub repo.
2. In Vercel: New Project → Import the repo → Framework preset: **Other** →
   Root Directory: `/` → Deploy.
3. In the project's Domains settings, add `hevyglobal.com`.
4. In Cloudflare DNS for hevyglobal.com, add the CNAME record Vercel gives you.
   Set proxy status to "DNS only" (grey cloud) until SSL is issued.

## Subdomains (Live, Sports, Sounds, Hub, Conference)
Each becomes its own Stitch export + its own folder/repo (or its own app inside
a monorepo), deployed as a separate Vercel project pointed at
`live.hevyglobal.com`, `sports.hevyglobal.com`, etc. Add a CNAME per subdomain
in Cloudflare the same way as above.

## To do before full public launch
- [ ] Build out real subpages for Insights, Investor Relations, Privacy Policy,
      Terms, Ethics Portal (currently placeholder `#` links)
- [ ] Replace placeholder contact details (email, HQ address) with real ones
- [ ] Add Google Analytics / Search Console
- [ ] Compress Tailwind via a build step instead of the CDN script for
      production performance (optional, CDN is fine to launch with)
