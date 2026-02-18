# Content model — MolSysSuite Product Site

This document describes the editable content in `web/src/content/` and how it is used on the site.

## Frontmatter conventions (all collections)

All markdown entries in `web/src/content/*` follow these fields:

- `title` (string) — page/post title
- `date` (YYYY-MM-DD) — publication/event date (used for sorting)
- `tags` (list of strings) — controlled vocabulary per site (see below)
- `summary` (string) — 1–2 lines used in cards/previews
- `draft` (boolean) — `true` means do not show in production lists
- `featured` (boolean, optional) — highlight on the home page

**Rules**
- Use ISO dates.
- Prefer 1–3 tags per entry.
- Slugs should be derived from the file name: `YYYY-MM-DD-short-kebab-title.md`.
- Keep `summary` plain text (no markdown).

## Collections

### `updates/`
Blog posts: releases, workshops, new features, design notes. Used for diffusion and to show activity.

### `components/`
One card per ecosystem component (libraries/tools). Used in Ecosystem map and related pages.

### `workflows/`
High-level, narrative workflows (not API docs). Used on the Workflows page.

### `roadmap/`
Roadmap items (optional). Can be used to render a simple roadmap section.

## Tags vocabulary

Use the following canonical tags (avoid ad-hoc tags unless you *intend* to expand the vocabulary):

- `release`
- `workshop`
- `design-note`
- `community`
- `announcement`


## Additional rules
**Tagging guidance**
- New version / release: `release`
- Workshops, courses, training: `workshop`
- Architectural notes and rationale: `design-note`
- Calls for contributors / community updates: `community`
- General announcements: `announcement`
