---
name: analytics-install-and-setup
description: Install and configure the measurement stack every LFS site should launch with so the project is ready for monthly SEO work: Vercel Analytics, Speed Insights, GA4 event planning, Search Console/Bing setup checklist, robots/sitemap checks, and AI-search discoverability readiness.
---

# Analytics Install and Setup

Use this skill during the final build and before launch.
It is for installing and configuring the measurement layer that every LFS site should have, even before the client upgrades to monthly SEO.

## Core job
1. install Vercel Web Analytics
2. install Vercel Speed Insights
3. prepare GA4 event plan and implementation points
4. verify robots.txt and sitemap.xml
5. verify schema is present where expected
6. prepare Search Console Domain property setup steps
7. prepare Bing Webmaster Tools setup steps
8. verify OpenAI search discoverability intent via robots.txt
9. produce a post-launch analytics validation checklist

## Default stack for every site
- Vercel Web Analytics
- Vercel Speed Insights
- GA4 base tracking
- GA4 key events suited to the business model
- Search Console Domain property checklist
- Bing Webmaster checklist
- robots.txt and sitemap.xml validation
- Rich Results Test on homepage and priority pages

## What this skill must output
1. What is already installed
2. What still needs to be installed or configured
3. The exact code/config changes needed in the repo
4. The account-level tasks the user still needs to complete manually
5. A post-launch validation list

## Guardrails
- Do not pretend account-verification tasks are finished if they require the user's Google, Bing, or Vercel dashboard access.
- Separate repo-level work from account-level setup.
- Keep the implementation lightweight and production-safe.
- Prefer install-once, measure-forever instrumentation.
