# Automotive Industry — Ownership Network

Interactive force-directed graph mapping the ownership and control relationships
between the world's major automotive groups, their brands, holding companies,
and key shareholders — verified against primary sources (corporate filings and
press) as of July 2026.

**Live page:** https://graph-ist.github.io/automotive-industry/

**Full research & methodology:** [RESEARCH.md](RESEARCH.md) — sourcing notes,
revision history, and caveats behind every figure in the graph.

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
- `RESEARCH.md` — the underlying research notes, sourcing and methodology.
- `archive/` — earlier Italian-language drafts and source research (kept
  locally, git-ignored).

## Tech

Single self-contained HTML file, [D3.js](https://d3js.org/) force simulation,
no build step or dependencies to install.
