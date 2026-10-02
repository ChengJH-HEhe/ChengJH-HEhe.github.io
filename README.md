# Junhong Cheng — Academic Homepage

Personal academic website based on [Academic Pages](https://github.com/academicpages/academicpages.github.io), customized from the CV updated October 1, 2026.

## Local preview

Install Ruby 3.2 and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve --host 0.0.0.0
```

Open `http://localhost:4000`. Production check:

```sh
JEKYLL_ENV=production bundle exec jekyll build --strict_front_matter
```

## Update content

- `_config.yml`: name, email, sidebar, site URL.
- `_pages/about.md`: homepage.
- `_pages/research.md`: research experience.
- `_pages/cv.md` and `files/CV.pdf`: web CV and downloadable CV (update both).
- `_pages/projects.md`: selected projects.
- `_publications/`: manuscripts and papers. Preserve the explicit review/acceptance status.
- `_posts/YYYY-MM-DD-title.md`: articles.
- `_data/navigation.yml`: navigation.
- `images/junhong-monogram.svg`: initials avatar; replace the `author.avatar` setting with a personal photo when available.

### Add an article

Create `_posts/2026-10-02-example.md`:

```markdown
---
title: "Your article title"
date: 2026-10-02
permalink: /articles/your-article-slug/
excerpt: "A short summary."
tags: [systems, security]
---

Write your article in Markdown here.
```

Use the actual publication date; future-dated posts are hidden. Chinese and English articles are supported. Articles appear automatically in `/articles/`, the homepage's recent-articles list, and `/feed.xml`.

## GitHub Pages

The existing default branch is `CF`. To publish with GitHub's built-in Jekyll support, set **Settings → Pages → Deploy from a branch → CF → /(root)**. The build workflow validates changes and does not change Pages settings. If Pages currently uses a custom Actions deployment, update that deployment to build the Jekyll sources before publishing.

The original July 24, 2024 diary is migrated with a redirect from its previous URL. The old Hello World URL remains available but is excluded from the article list. The old website remains recoverable in Git history.

## Attribution

Academic Pages is based on Minimal Mistakes. The upstream MIT license is retained in `LICENSE`.
