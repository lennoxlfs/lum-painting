# Lum Painting — Project Instructions

This project uses the **LFS_CLAUDE_WEBSITE_SYSTEM_V6** as its authoritative brain.

## Active system
- Read and follow: `LFS_CLAUDE_WEBSITE_SYSTEM_V6/CLAUDE.md`
- Reference playbooks: `LFS_CLAUDE_WEBSITE_SYSTEM_V6/reference/`
- Templates: `LFS_CLAUDE_WEBSITE_SYSTEM_V6/templates/`

V6 overrides any conflicting guidance in parent `CLAUDE.md` files.

## Stack (project-specific override)
This site is a **single-file static HTML** project (`index.html`), not Next.js.
- No build step. No framework.
- Served locally via `serve.mjs` if present; deployed via Vercel static hosting.
- Tailwind CDN rules in parent CLAUDE.md do not apply — styles live inline in `<style>` within `index.html`.
- Edits happen directly in `index.html`. Preserve existing design, branding, and working functionality unless a change is explicitly approved.

## Standard implementation files
Standard V6 files live at the project root:
- `research-package.md`
- `brand-package.md`
- `client-sales-report.md`
- `internal-sales-report.md`
- `monthly-client-report.md`
- `monthly-internal-implementation-report.md`
- `implementation-log.md`
- `analytics-setup-checklist.md`

Treat these as implementation inputs, not passive docs (per V6 handoff doctrine).

## Deployment
Local edits → GitHub `main` → Vercel auto-deploy. Do not push or deploy without explicit approval.
