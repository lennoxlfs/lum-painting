# LFS Deployment Playbook

## Standard launch path
1. Final QA
2. Commit locally
3. Push to GitHub
4. Deploy to Vercel
5. Verify production
6. Re-test highest-value actions

## Prelaunch checklist
- correct repository and branch
- latest approved content/assets
- mobile navigation verified
- forms verified
- CTA buttons verified
- phone, email, and map links verified
- page titles and meta descriptions present
- schema present where expected
- robots directives correct
- sitemap available or generated
- analytics/tag manager installed if required
- favicon / Open Graph basics present

## Commit guidance
Use a clear message such as:
- feat: launch final Chardon PT production site
- fix: finalize mobile CTA and contact form before launch
- seo: refine titles, schema, and local service copy before production deploy

## Post-push / Vercel checks
- latest deployment succeeded
- production domain resolves correctly
- SSL is working
- forms submit on production
- thank-you / confirmation behavior works
- analytics fires on production
- primary CTA path works end to end
- pages render correctly on mobile and desktop

## If access is missing
If GitHub or Vercel access is missing, prepare:
- launch checklist
- commit message suggestion
- files ready for push
- list of required access/details
