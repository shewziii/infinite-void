# CODE STANDARDS
---
## Purpose

This document defines coding, content, and Git practices for this repository.
The goal is consistency, readability, and a clean project history.

---
# 1) Project Structure

## Source code

* `src/` contains all application code
* `src/components/` for reusable UI components
* `src/pages/` for Astro routes
* `src/layouts/` for page layouts

## Content

* `src/content/blog/` for blog posts
* `src/content/newsletters/` for newsletters
* Markdown content is treated as first-class product surface

---
# 2) Branching Strategy

## Main branch

* `main` is always production-ready
* All work happens in short-lived branches

## Branch prefixes
Use kebab-case names with one of the following prefixes:
```
feature/   # new user-facing functionality
fix/       # bug fixes
refactor/  # internal code changes, no behavior change
chore/     # tooling, config, dependencies
content/   # blog posts, newsletters, copy changes
```

### Examples
```
feature/markdown-preview
fix/rss-build-crash
refactor/image-pipeline
chore/cloudflare-adapter
content/private-markdown-app
content/2026-02-stp-newsletter
```

---
# 3) Commit Message Standards
## Format
```
type: short summary

Optional longer description
```

## Allowed types
```
feat:
fix:
refactor:
chore:
docs:
content:
perf:
```

## Examples
```
feat: add markdown preview to editor
fix: prevent sitemap build crash
refactor: simplify Astro image pipeline
chore: update Cloudflare adapter config
content: publish blog post on private markdown apps
```

## Rules
* Use imperative mood: "add", not "added"
* Keep subject under 72 characters
* One logical change per commit
* Avoid "and" in commit titles

---
# 4) Content Workflow (Astro Markdown)
## Branching
* One blog post or newsletter = one `content/` branch
* Draft commits are allowed during writing

## Publishing
Before merging to `main`:
* Squash all draft commits into one commit
* Final commit message format:
```
content: publish <title or topic>
```

### Example
```
content: publish blog post on private markdown apps
```

## Rule
**One published content item = one commit on main.**

---
# 5) Git History Philosophy
* Feature branches may be messy
* `main` must be curated and readable
* Squash before merging whenever possible

### Preferred workflow
1. Work on branch
2. `git rebase -i main` and squash
3. Merge to main
4. Delete branch

---
# 6) Code Style
## Formatting
* Prettier is the source of truth
* No manual formatting wars

## Linting
* ESLint for JavaScript/TypeScript
* Fix lint errors before merging

## Naming
* Use kebab-case for files and folders
* Use camelCase for variables and functions
* Use PascalCase for components

---
# 7) Refactors vs Features
## Use `feature/` when:
* Behavior changes
* New UI or functionality is added

## Use `refactor/` when:
* Code structure changes
* No user-facing behavior change

---
# 8) Deployment
* `main` deploys to production
* Never push broken builds to `main`
* Test locally before merging

---
# 9) Philosophy
* Treat content like code
* Treat main like a published book
* Optimize for future readability
* Prefer boring, consistent conventions over cleverness
