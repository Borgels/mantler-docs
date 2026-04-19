# mantler-docs

Documentation site for [Mantler](https://mantler.ai) — deployed at [docs.mantler.ai](https://docs.mantler.ai).

Built with [Fumadocs](https://fumadocs.vercel.app) and Next.js.

## Development

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Content

Documentation lives in `content/docs/`. Files are MDX with frontmatter:

```mdx
---
title: Page title
description: Short description shown under the title.
---

Content here.
```

Sidebar order is controlled by `meta.json` files in each directory.

## Structure

```
content/docs/
  index.mdx               # Introduction
  getting-started.mdx     # Quickstart guide
  machines/               # mantlerd daemon documentation
  stacks/                 # Stack (mantle) documentation
  api/                    # API reference
  security.mdx            # Security overview
```

## Deployment

The site deploys automatically to Vercel on push to `main`.
