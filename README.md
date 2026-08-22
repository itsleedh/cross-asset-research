# Independent Research Notes — Quarto + GitHub Pages

A minimal research-site starter designed for long-form macro / markets / quantitative-finance notes.

## 1. Personalize the site

Edit `_quarto.yml` and replace:

- `YOUR_GITHUB_USERNAME`
- `YOUR_REPOSITORY`
- `YOUR_LINKEDIN_SLUG`
- the site title/description if desired

## 2. Preview locally

Install Quarto, then run:

```bash
quarto preview
```

## 3. Publish with GitHub Pages

1. Create a GitHub repository and push this folder to `main`.
2. In **Settings → Pages**, set the source to **Deploy from a branch**.
3. Select the `gh-pages` branch once the workflow creates it.
4. Future pushes to `main` will republish automatically.

If you use a repository named `<username>.github.io`, set `site-url` accordingly and omit the repository suffix.

## 4. Add a new research note

Create:

```text
posts/YYYY-MM-short-slug/index.qmd
```

Recommended front matter:

```yaml
---
title: "Title"
date: YYYY-MM-DD
description: "One-sentence thesis"
categories: [Macro, Rates]
---
```

Keep the first screen decision-oriented: thesis, evidence, signposts, and the full-report link. Put detailed methodology and long evidence chains below.

## 5. Versioning policy

For dated market research, do not silently rewrite history. Prefer:

- original dated report preserved as-is;
- a new dated update when the thesis materially changes;
- a short changelog linking old and new views.

That makes the site useful as a research track record rather than just a collection of polished hindsight notes.
