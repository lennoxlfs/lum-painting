# Monthly Implementation Workflow

## Every month
1. Gather the inputs
   - Search Console
   - GA4
   - Vercel Analytics
   - Vercel Speed Insights
   - PageSpeed / Lighthouse
   - GBP / Bing notes if relevant
2. Generate reports
   - monthly-client-report.md
   - monthly-internal-implementation-report.md
3. Review with the client
4. Approve changes
5. Use the internal report to prompt Claude Code
6. Implement the changes
7. QA
8. Git push
9. Vercel deploy
10. Log the month’s changes in implementation-log.md

## Minimum monthly prompt for Claude Code
Read `monthly-internal-implementation-report.md` and use it as the implementation brief for this month’s approved SEO updates. Apply the approved changes, update `implementation-log.md`, run a short QA pass, and prepare the repo for GitHub push and Vercel deployment.
