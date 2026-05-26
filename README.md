# pachesnyi.github.io

Personal site and blog built with Astro and Markdown.

## Development

```sh
npm install
npm run dev
```

## Writing

Add posts as Markdown files in `src/content/blog`.

Required frontmatter:

```yaml
---
title: "Post title"
description: "Short summary for lists and SEO"
pubDate: 2026-05-25
tags: ["AI", "Frontend"]
draft: false
---
```

## Deployment

The site is static and can be deployed to GitHub Pages or Netlify.

For Netlify, the included `netlify.toml` builds with `npm run build` and publishes `dist`.
