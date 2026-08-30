# Michael J. Muirhead — Municipal Electric Utility Consulting

A single-page consulting website for Michael J. Muirhead, retired Director of
Public Works & Utilities for Garden City, Kansas, and longtime KMEA Executive
Committee officer, now consulting in the municipal electric utilities space.

The design takes inspiration from premium engineering-consultancy sites
(e.g. Exponent's utilities practice page) while keeping the focus where it
belongs for a one-person practice: Mike's career, projects, and recognition.

## Stack

Plain, dependency-free static HTML and CSS — no build step, no framework.

- `index.html` — the entire site (single page, anchored sections)
- `styles.css` — design system and layout
- `favicon.svg` — site icon

Typography is loaded from Google Fonts (Source Serif 4 + Inter); everything
else is self-contained, including all illustrations (inline SVG).

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

The site is ready for any static host. For GitHub Pages: repository
**Settings → Pages → Deploy from a branch**, choose the default branch and
`/ (root)`.

## Before launch — checklist

- [ ] **Contact email**: `index.html` currently links to
      `mike@michaeljconsulting.example` (a reserved placeholder domain).
      Search for `TODO` in `index.html` and replace it with Mike's real
      consulting address.
- [ ] **Portrait photo**: the About section uses a monogram graphic as a
      stand-in. Replace it with a real photograph of Mike (see the `TODO`
      comment in the About section of `index.html`).
- [ ] Review all copy for accuracy with Mike, especially dates and figures.

## Sources

Site copy is drawn from public coverage of Mike's career:

- City of Garden City, KS — "Garden City Public Works & Utilities Director
  Mike Muirhead Announces Retirement"
- KMEA — "Celebrating Mike Muirhead's Retirement and Years of Service" and
  the Gilbert E. Hanson Jr. Outstanding Service Award (2020/2021)
- Public Power Current (APPA) — Q&A with Mike Muirhead on the Garden City
  utility's master plan, reliability programs, and community engagement
