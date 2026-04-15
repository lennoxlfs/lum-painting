# Analytics Setup Checklist — Lum Painting

Domain: `lumpainting.com`
Stack installed in `index.html`.

## Installed (code-side)
- [x] Vercel Web Analytics — `/_vercel/insights/script.js`
- [x] Vercel Speed Insights — `/_vercel/speed-insights/script.js`
- [x] GA4 `gtag.js` — Measurement ID `G-43108TM6XK`
- [x] GA4 key events:
  - [x] `call_click` (tel: links)
  - [x] `email_click` (mailto: links)
  - [x] `directions_click` (Google Maps links)
  - [x] `outbound_click` (external links)
  - [x] `form_submit` (quote form)
  - [x] `generate_lead` (post-submit `?sent=1`)
- [x] `robots.txt` at root — allows Google, Bing, OAI-SearchBot, GPTBot, PerplexityBot, Google-Extended
- [x] `sitemap.xml` at root

## Pending — manual action required
- [ ] **Vercel dashboard:** confirm Web Analytics + Speed Insights toggles are ENABLED for the project
- [ ] **Google Search Console:** add Domain property `lumpainting.com`, verify via DNS TXT record (in progress)
- [ ] **GSC:** submit `https://lumpainting.com/sitemap.xml` after verification
- [ ] **Bing Webmaster Tools:** import from GSC once verified (in progress)
- [ ] **GA4:** mark the following as Key Events in the GA4 admin:
  - `call_click`
  - `form_submit`
  - `generate_lead`
  - `directions_click`
- [ ] **GA4:** link GA4 property to Google Ads (if/when running ads)
- [ ] **GA4:** enable enhanced measurement (default) and confirm Realtime events after deploy

## Post-deploy validation
- [ ] Visit `https://lumpainting.com/robots.txt` — returns 200 with allow rules
- [ ] Visit `https://lumpainting.com/sitemap.xml` — returns valid XML
- [ ] GA4 Realtime shows page_view within ~30s
- [ ] Click phone number; confirm `call_click` in GA4 DebugView
- [ ] Submit quote form; confirm `form_submit` + `generate_lead` fire
- [ ] Rich Results Test on `https://lumpainting.com/` — PaintingContractor / Organization / WebSite recognized
- [ ] PageSpeed Insights — confirm no regressions
- [ ] Lighthouse — SEO 100, A11y ≥ 95

## Monthly-ready
- Monthly templates live in `LFS_CLAUDE_WEBSITE_SYSTEM_V6/templates/`
- Future monthly loops consume `monthly-internal-implementation-report.md` as the build brief
