# advprasannghate.com

Static website for **Adv. Prasann Ghate** — property law & documentation, Wagholi, Pune.
Built as plain HTML/CSS so it loads fast, ranks well, and is trivial to host on Cloudflare Pages.

## Files
| File | Purpose |
|------|---------|
| `index.html` | The whole single-page site + SEO meta + JSON-LD structured data |
| `styles.css` | All styling (responsive, mobile-first) |
| `robots.txt` | Allows Google, Bing and AI crawlers (ChatGPT, Perplexity, Claude, Gemini) |
| `sitemap.xml` | Tells search engines about the page |
| `404.html` | Friendly not-found page |
| `favicon.svg` | Browser tab icon |
| `site.webmanifest` | PWA/metadata |
| `_headers` | Cloudflare Pages caching + security headers |

## Business details already filled in
- **Name:** Adv. Prasann Ghate
- **Phone / WhatsApp:** +91 87888 95452
- **Email:** `official@advprasannghate.com`
- **Office:** Gat No. 648/2, Kesnand Phata, Pune – Nagar Rd, Wagholi, Pune, Maharashtra 412207

## Before you go live
Email (`official@advprasannghate.com`) and the exact office map coordinates are already set.
Two things left (you said you'll do these later):

1. **OG image (optional but recommended):** add `assets/og-image.jpg` (1200×630) — a photo
   or a simple banner with name + "Property Lawyer, Wagholi". This is the preview shown when
   the link is shared on WhatsApp/Facebook.
2. **Google Business Profile:** create a free listing at business.google.com with the exact
   same name/address/phone as above. This is the single biggest factor for showing up in the
   Google map pack when people search "property lawyer Wagholi".

## Deploy to Cloudflare Pages (no build step needed)
### Option A — drag & drop (fastest)
1. Go to **dash.cloudflare.com → Workers & Pages → Create → Pages → Upload assets**.
2. Drag this whole folder in. Deploy.
3. In the project → **Custom domains** → add `advprasannghate.com` and `www.advprasannghate.com`.
   (Since the domain is already on Cloudflare, DNS is set automatically.)

### Option B — connect a Git repo (auto-deploys on every change)
1. Push this folder to a GitHub repo.
2. Cloudflare Pages → Create → connect the repo. Framework preset: **None**.
   Build command: *(leave empty)*. Output directory: `/`.
3. Add the custom domain as above.

## After going live — get found
1. **Google Search Console** (search.google.com/search-console): add the domain, then
   submit `https://www.advprasannghate.com/sitemap.xml`.
2. **Bing Webmaster Tools**: same — add site, submit sitemap.
3. Verify structured data at https://validator.schema.org/ (paste the live URL).
4. Check mobile speed at https://pagespeed.web.dev/.

## Want to rank even higher later?
The strongest next step is adding one dedicated page per key service/area, e.g.
`/sale-deed-wagholi`, `/property-registration-kharadi`, `/nri-property-lawyer-pune`.
Each targeted page gives Google a clear match for that exact search. Ask and this can be
extended into that multi-page structure.
