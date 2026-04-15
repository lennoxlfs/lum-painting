---
name: github-vercel-launch
description: Use when a website is ready to go live and the LFS deployment path should be followed: final QA, commit, push to GitHub, deploy to Vercel, and verify production.
---

# GitHub Vercel Launch

Use this skill when the user wants to launch a site using the standard LFS flow.

## Inputs
- deployment-ready codebase
- repository name / remote
- branch name
- Vercel project details
- production domain details if relevant
- tracking requirements
- analytics installation requirements

## Standard flow
1. Run final QA.
2. Verify core conversion actions, analytics installation, and production-critical SEO items.
3. Prepare a clear commit summary.
4. Commit locally.
5. Push to GitHub.
6. Deploy through Vercel.
7. Validate the live deployment and production domain.
8. Re-test forms, CTA buttons, phone links, and analytics on production.

## Minimum prelaunch checks
- homepage renders correctly
- primary service pages render correctly
- mobile navigation works
- CTA buttons work
- forms submit correctly
- phone and email links work
- location/map links work
- titles and meta descriptions are present
- robots / sitemap behavior is correct for launch
- Vercel Web Analytics is installed if required
- Vercel Speed Insights is installed if required
- analytics tags are present if required
- key events are planned or implemented if required
- schema is present where expected

## Output
Provide:
- launch checklist status
- commit message suggestion
- deployment note / handoff note
- post-launch validation list
- any blockers that must be resolved before GitHub push or Vercel deployment

## Rule
Do not call the site live until the GitHub push is complete, the Vercel deployment is complete, and production checks pass.


## Analytics launch rule
Before calling a site ready, confirm whether the base analytics stack is installed.
All LFS sites should launch monthly-ready, even if the client is not yet on the monthly package.
