# Teecanva Website

Single-page static site. Free to host forever on Netlify.

## Files
- `index.html` — the whole site (hero, services, how it works, pricing, design bundles, order form, footer)
- `styles.css` — green & gold brand styling, mobile-responsive
- `logo.png` — the gold TC mark

## Deploy (about 20 minutes, all free)

1. **GitHub** — create a free account at github.com, make a new repository called `teecanva-site`, and upload these three files.
2. **Netlify** — create a free account at netlify.com → "Add new site" → "Import an existing project" → connect GitHub → pick `teecanva-site` → Deploy. You get a free `teecanva-site.netlify.app` URL instantly.
3. **Domain** — in Netlify: Site settings → Domain management → Add custom domain → enter your domain. Netlify shows you DNS records; add them where your domain is registered. (HTTPS is automatic.)
4. **Order form** — the form already uses Netlify Forms. After first deploy: Site settings → Forms → enable form notifications → add your email. Test it once with a fake submission.

## Before launch checklist
- [ ] Replace the two `#` Etsy links with your real Etsy shop URL
- [ ] Confirm `www.teecanva.com` is your actual domain (update footer if not)
- [ ] Confirm pricing tiers with your chosen screen printer
- [ ] Swap the bundle placeholder cards with real design mockups when ready
- [ ] Submit the form once to verify email notifications arrive
