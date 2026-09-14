# Jonathan Taylor's portfolio

Hugo site using the existing pinned PaperMod theme. Current professional focus: data intelligence and analytics leadership.

## Edit the content

- `layouts/home.html`: homepage introduction and selected work.
- `content/experience/_index.md`: current role and responsibilities.
- `content/about/_index.md`: professional background.
- `content/projects/*/_index.md`: historical case studies, ordered by `weight`; `featured = true` selects homepage case studies.
- `content/contact/_index.md`: contact links.
- `assets/css/extended/portfolio.css`: responsive visual styling.

Original reports and the Power BI file remain in `static/documents`. Preserve those historical artifacts when changing case-study summaries.

## Build and preview

Validated with Hugo Extended 0.152.2 and the existing PaperMod submodule commit.

```sh
git submodule update --init -- themes/PaperMod
hugo --minify --cacheDir ../hugo-cache
hugo server --bind 127.0.0.1 --port 4387 --baseURL http://127.0.0.1:4387/ --destination ../preview-site --cacheDir ../hugo-cache
```

The production build uses `public/`. Keep the preview destination separate so a production build cannot replace preview links with the production URL.

## Content evidence

The September 2026 update uses Jonathan's confirmed title, employer, dates, leadership direction, and high-level current responsibilities. It does not claim managerial authority, completed production adoption, or quantified business outcomes that have not been supplied.

Historical case-study summaries were reconciled with the reports in `static/documents`. The original analyses were not rerun. A refreshed resume and one specific current-work example with shareable outcomes can be added later; the previous resume file remains preserved, but is no longer advertised as current.
