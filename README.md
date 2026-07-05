# Ivan Temelkov Blog

This repository contains a small personal blog built with Jekyll for GitHub Pages.

The site is intended for short articles, notes, and reflections about software development, engineering practices, AI-assisted development workflows, and lessons learned.

## Writing

Published posts belong in `_posts/` and use this naming format:

```text
YYYY-MM-DD-short-kebab-title.md
```

Drafts belong in `_drafts/` and use this naming format:

```text
short-kebab-title.md
```

Post images belong under:

```text
assets/images/posts/YYYY-MM-DD-post-slug/image-name.png
```

Use lightweight tags in front matter rather than a complex category hierarchy.

## Local preview

GitHub Pages can build this site with its native Jekyll support. No custom GitHub Actions workflow is required.

If Jekyll is already installed locally, preview with:

```powershell
jekyll serve
```

Do not install tooling just to work on a post; GitHub Pages rendering can be verified after pushing.

## Licensing note

The repository currently includes an MIT License for website source code such as layouts, includes, configuration, and custom CSS.

Written content, personal reflections, images, diagrams, screenshots, and other media are intended to remain © Ivan Temelkov. All rights reserved unless otherwise stated.

A dedicated content licensing notice may be added later after explicit approval.
