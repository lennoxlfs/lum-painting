# LFS Claude Website System V5

This is the current LFS local-business website, SEO, AI-search, analytics, and monthly-growth operating system.

It is designed to help Claude:
- follow the finalized LFS sales and delivery process
- build a Step 2A Research Package and Step 2B Brand Package
- build a sample site that is unique, easy to navigate, on-brand, and structurally strong
- generate a client-facing comparison report that protects the proprietary edge
- generate an internal LFS report with talking points and close strategy
- optimize for modern Google Search, local SEO, Google AI features, Bing, and OpenAI search discoverability
- install and configure the analytics stack needed for monthly SEO work on every site
- produce monthly client-facing and internal implementation reports for paying monthly SEO clients
- turn monthly reports into prioritized action plans and actual site-edit recommendations
- launch sites through the LFS deployment path: GitHub first, then Vercel

## Core folders

- `CLAUDE.md` — master operating system and rules
- `.claude/skills/` — reusable specialist skills
- `reference/` — Google-first SEO, AI search, analytics, local SEO, and monthly optimization guidance
- `templates/` — standard package/report templates

## Fast usage

Typical workflow:
1. Build Research Package
2. Build Brand Package
3. Build Sample Site
4. Build Client Report + Internal LFS Report
5. Prepare meeting
6. Build final site after close
7. Install analytics stack
8. Run final QA
9. Push to GitHub
10. Deploy to Vercel
11. Verify analytics and search-readiness
12. Run monthly SEO evolution only for paying monthly clients

## New in V5

- monthly SEO evolution is merged directly into the main system
- all sites are now instructed to launch with the analytics stack needed for monthly SEO work
- a dedicated analytics-install-and-setup skill was added
- monthly reporting templates are built in
- OpenAI search discoverability guidance was added
- launch and QA now include analytics and measurement readiness

## Important note

The files define the process and decision logic.
They do not create outside tool access by themselves.
If Lighthouse, PageSpeed, Search Console, GA4, GBP, Bing Webmaster, or Vercel analytics data are not available automatically, supply the reports or summaries manually.


## V6 update
- adds explicit implementation handoff rules
- adds final-build-handoff and monthly-implementation-handoff skills
- treats internal reports as Claude Code build briefs
- adds standard prompt templates and implementation log template
