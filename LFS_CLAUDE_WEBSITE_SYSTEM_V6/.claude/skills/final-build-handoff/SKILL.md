# Final Build Handoff

Use this skill when the project already has a Research Package, Brand Package, and Internal Sales Report and it is time to build or refine the final production website.

## Required inputs
- `research-package.md`
- `brand-package.md`
- `internal-sales-report.md`
- the current codebase
- any client-approved direction or change notes

## Purpose
Turn strategy documents into production implementation.
Do not leave the reports as passive references.

## Workflow
1. Read `research-package.md` and extract the problems that must be solved.
2. Read `brand-package.md` and extract the visual/brand constraints that must be preserved or elevated.
3. Read `internal-sales-report.md` and extract the approved fixes, strongest improvements, and any implementation priorities.
4. Convert all of that into an implementation checklist.
5. Apply the checklist to the real codebase.
6. Keep a concise implementation log of what changed.
7. Prepare the project for QA, git push, and Vercel deployment.

## Output requirements
Always produce:
1. a concise implementation checklist before code changes
2. the actual code changes
3. an `implementation-log.md` update summarizing what was changed and why
4. a short QA list for the final pass

## Guardrails
- preserve the approved design direction
- preserve brand DNA
- do not ignore research findings
- do not ignore the internal sales report
- keep the build production-focused and implementation-oriented
