# public static void async

Personal site powered by [Astro](https://astro.build/), deployed to GitHub Pages.

## Publish an article

Add a Markdown file under `src/content/writing/`:

```md
---
title: My article title
description: One-sentence summary.
date: 2026-11-23
---

Article content here.
```

Merge the change into `master`; GitHub Actions builds and deploys automatically.

## Local development

```sh
npm install
npm run dev
npm run build
```

In repository Settings → Pages, choose **GitHub Actions** as the build and deployment source before merging.

**Before deploying:** Migrate the original 2017 Jekyll articles and check their old URLs for redirects. They are not yet migrated.
