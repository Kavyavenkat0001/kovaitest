# Getting started with kovaitest

This repository is used to validate the Document360 GitHub extension, which
syncs Markdown content from GitHub into a Document360 knowledge base
category.

## What this repo contains

- `docs/articles/` — Markdown files. Each file becomes an article in the
  linked Document360 category.
- `docs/.document360/assets/` — images and other media referenced by the
  articles.

## How the sync works

- Only the `main` branch is synced.
- Content is read-only in Document360 — all edits happen here in GitHub and
  are picked up automatically on the next push to `main`.
- New articles are added by committing a new Markdown file under
  `docs/articles/`.
