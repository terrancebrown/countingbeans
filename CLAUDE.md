Repo: ~/Sites/countingbeans (branch: main)
Theme: Bear Blog (Hugo port)
Hugo version: 0.161.1+extended+withdeploy
Deployment: Cloudflare Pages via GitHub push to main. Build command: hugo --minify. HUGO_VERSION env var is set to 0.161.1.
Registrar: xneelo (.co.za domain)
Editor: VSCodium (primary), micro in terminal.

Content structure:
- All posts are flat .md files in content/blog/
- No date prefix on slugs
- Front matter is YAML (--- delimiters)
- Archetype scaffolds: date, draft, title only — keep front matter minimal
- New post command: hugo new content/blog/slug.md

Front matter convention (minimal by design):
```yaml
date: 'YYYY-MM-DD'
draft: true
title: Post Title
```

Tagline: "Notes from a small life." Tone is slow, reflective, and personal. Keep everything as sparse as possible — no tags, categories, or descriptions. The owner is South African, writes in South African English (en-GB spelling).
