# Michael Muirhead — Municipal Electric Utility Consulting

A single-page consulting website for Michael "Mike" Muirhead, retired Director
of Public Works & Utilities for Garden City, Kansas, and longtime KMEA
Executive Committee officer, now consulting in the municipal electric
utilities space.

The design takes inspiration from premium engineering-consultancy sites
(e.g. Exponent's utilities practice page) while keeping the focus where it
belongs for a one-person practice: Mike's career, projects, and recognition.

## Stack

Plain, dependency-free static HTML and CSS — no build step, no framework.

- `index.html` — the entire site (single page, anchored sections)
- `styles.css` — design system and layout
- `favicon.svg` — site icon

Typography is loaded from Google Fonts (Source Serif 4 + Inter); everything
else is self-contained, including all illustrations (inline SVG). The only
JavaScript is a small inline snippet for the mobile menu; the site works
fully with JavaScript disabled.

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
- [ ] **Name check**: public sources consistently say "Mike Muirhead"; the
      site uses "Michael Muirhead" formally. Confirm with Mike how he wants
      his name rendered (and whether to add a middle initial).
- [ ] **Quote check**: the two colleague quotes (Matt Allen, Paul Mahlberg)
      and Mike's own quotes were recovered from public articles via search
      excerpts; verify exact wording against the original announcements
      before launch.
- [ ] Review all copy for accuracy with Mike, especially dates and figures.

## Sources

Site copy is drawn from public coverage of Mike's career, including:

- City of Garden City, KS — "Garden City Public Works & Utilities Director
  Mike Muirhead Announces Retirement" (June 2026)
- KMEA — "Celebrating Mike Muirhead's Retirement and Years of Service";
  Gilbert E. Hanson Jr. Outstanding Service Award (2020/2021); Mark Crisson
  Award coverage
- American Public Power Association / Public Power Current — Q&A with Mike
  Muirhead (Apr 2024) on the master plan, reliability programs, and
  community engagement; "Garden City, Kansas, Utility Buys T&D Facilities,
  Marking Final Major Step for Power System Revamp" (2021)
- Kansas Municipal Utilities — Edgar P. Schowalter Award (2021)
- Western Kansas News / ICMA — Jameson Energy Center coverage (2013–2016)

Deliberately omitted as unverifiable from public sources: total
years-in-industry figures, Gillette-era role dates, the Jameson Energy
Center's exact opening date and cost, and per-office years for Mike's KMEA
officer terms.
