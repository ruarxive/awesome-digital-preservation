# Project Context

## Purpose
Curated "Awesome" list of digital preservation tools, standards, and
organizations, with a strong emphasis on web archiving. The goal is to be a
high-signal, easy-to-scan index for practitioners and newcomers.

## Tech Stack
- Markdown (GitHub README as primary artifact)
- Git/GitHub for collaboration and distribution

## Project Conventions

### Code Style
- Markdown-first: headings for sections, bullet lists for entries.
- Entry format: `- [Name](URL) - short description` (sentence case).
- Keep descriptions concise (one sentence) and avoid marketing language.
- Prefer consistent punctuation and spacing; avoid trailing whitespace.

### Architecture Patterns
- Single source of truth is `README.md`.
- Group content by domain sections and sub-sections for scanability.
- Supplementary planning lives under `dev/docs/`.

### Testing Strategy
- No automated tests. Use manual review for formatting, clarity, and link
  correctness when adding or editing entries.

### Git Workflow
- Main branch is the canonical list. Use small, focused changes per commit.
- Prefer descriptive commit messages that match the list update scope.

## Domain Context
Digital preservation covers web archiving, social media capture, archival file
formats (e.g., WARC/WACZ/CDX), preservation tooling, and institutions. The list
is curated to surface practical tools, standards, and organizations that help
capture, store, replay, and analyze digital materials.

## Important Constraints
- Accuracy matters: entries should be relevant, active when possible, and
  accurately described.
- Avoid duplicates across categories; prefer the most appropriate section.
- Keep the list concise and readable; don't add speculative or low-signal items.

## External Dependencies
- GitHub (repository hosting and external project links)
- Awesome badge asset (external image URL in README)
