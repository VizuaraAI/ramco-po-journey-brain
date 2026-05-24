# Ramco PO Journey Brain — Teaching Page

A self-contained, single-file teaching site explaining how the Purchase Order journey-graph chat assistant works for Ramco ERP.

## What's here

- `index.html` — the entire site. Loads Fonts (Fraunces, Inter, JetBrains Mono) from Google Fonts. No build step, no server.
- `.nojekyll` — tells GitHub Pages to serve files as-is, not run Jekyll.

## Sections

1. **Hierarchy figure** — the four-layer mental model: Graph → 13 Journeys → Steps → Slots + Splices.
2. **The Problem** — before/after: 14 screens vs. one conversation.
3. **See It Live** — six-turn simulated conversation, side-by-side chat and backend.
4. **How We Built It** — twelve phases that produced the knowledge graph.
5. **The 13 PO Journeys** — entry-point-disjoint, lifecycle-linked; opens the full master graph in a modal.
6. **Drill into Create Direct PO** — the only fully-built journey: 7 steps · 49 slots · 27 splices · 19 rules.
7. **Splice fan-out** — one slot value, three different conversations.
8. **Five sources for one slot** — how API specs, screens, SPs, training docs, and the service catalog all ground a single field.

## Deploy

This is hosted on [GitHub Pages](https://pages.github.com/) directly from `main`.

## License

Internal demo material. Ramco-specific artifacts and structures are referenced for illustration only.
