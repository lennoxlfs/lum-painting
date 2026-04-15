# Monthly Analytics Install Playbook

## Goal
Every LFS site should launch with the measurement stack needed for monthly SEO work.

## Base install on every site
1. Vercel Web Analytics
2. Vercel Speed Insights
3. GA4 base tracking
4. planned GA4 key events
5. robots.txt and sitemap.xml
6. structured data validation
7. Search Console setup checklist
8. Bing Webmaster setup checklist

## Repo-level work Claude can usually do
- install Vercel analytics package
- install Vercel speed insights package
- add components/snippets to the app
- create analytics setup docs/checklists
- create robots.txt and sitemap.xml if missing
- add notes for GA4 event hooks
- verify structured data on key pages

## Account-level work the user must usually finish
- enable Vercel Analytics in dashboard if needed
- verify Search Console Domain property
- verify Bing Webmaster Tools
- create or connect GA4 property
- connect GBP ownership or manager access

## Default GA4 key events to plan
- generate_lead
- contact_form_submit
- phone_click
- email_click
- book_now_click
- appointment_request
- quote_request
- map_directions_click
- scheduler_complete
- chat_start

## Post-launch validation
- analytics package is live in production
- speed insights package is live in production
- key conversion actions work
- robots.txt resolves
- sitemap.xml resolves
- Search Console verification step is documented
- Bing verification step is documented
