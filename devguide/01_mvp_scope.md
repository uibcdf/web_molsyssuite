# MVP scope — MolSysSuite Product Site

    This file defines what “version 1” includes, what it explicitly excludes, and what is planned next.

    ## MVP (v1)
    - Landing home page with value proposition and ecosystem map.
- Pages: Ecosystem, Workflows, Get started, Updates (blog), Community.
- Ecosystem cards for key components (MolSysMT, MolSysViewer, TopoMT, etc.).
- Workflows page with 2–4 representative scenarios (high-level, not API docs).
- Get started page with minimal install guidance + links to per-repo Sphinx docs.
- Updates/blog with release notes, workshops, and design notes (lightweight).
- Deployed to `www.uibcdf.org/molsyssuite/` from this repo using `gh-pages`.

    ## Non-goals (v1)
    - This site does not replace Sphinx docs for any library.
- No heavy interactive documentation or notebooks on the product site (links out instead).
- No backend, logins, or hosted services in v1.
- No automated social feeds (avoid fragile integrations).

    ## Phase 2 ideas
    - Optional: add a small “media” section (talks/videos) with curated content.
- Optional: add “case studies” page with longer narratives.
- Optional: introduce Decap CMS to streamline updates posting.
- Optional: implement a simple release widget that reads GitHub releases at build time (if desired).
