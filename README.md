# Automotive Industry — Ownership Network

Interactive force-directed graph mapping the ownership and control relationships
between the world's major automotive groups, their brands, holding companies,
and key shareholders — verified against primary sources (corporate filings and
press) as of July 2026.

**Live page:** https://graph-ist.github.io/automotive-industry/

## What it shows

- **Parent groups, holdings, brands, shareholders and external partners** as
  color-coded nodes, sized by their role in the ownership hierarchy.
- **Ownership, control, minority stakes, joint ventures, alliances and ended
  relationships** as distinctly styled edges.
- An **orange halo** on edges where capital and voting rights diverge (e.g.
  loyalty shares, capped voting, non-voting preferred stock), since a single
  percentage would misrepresent those cases.
- Filters to isolate shareholders, external entities, historical relationships,
  divergence cases, or unlisted carmakers only.
- Adjustable force-simulation parameters (centering, repulsion, link strength,
  link distance).
- A timeline of verified structural events and a list of open/unresolved data
  points.

## Files

- `index.html` — the interactive graph (English).
- `gruppi_automobilistici_integrato_EN.md` — the underlying research/notes in
  document form.
- `archive/` — earlier Italian-language drafts and source research.

## Tech

Single self-contained HTML file, [D3.js](https://d3js.org/) force simulation,
no build step or dependencies to install.
