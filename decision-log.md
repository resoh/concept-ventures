# Decision & Concerns Log

Tracks partner/stakeholder comments and concerns raised during pitch review, and exactly where each was addressed across the four venture playbooks (`claude.md`) and pitch sites (`index.html`). Newest first.

| # | Date | Raised By | Concern / Comment | Ventures Affected | Resolution | Addressed In |
|---|------|-----------|--------------------|--------------------|-------------|---------------|
| 5 | 2026-09-19 | Business partner | Powder coating could wear off at contact points and cause issues | All four (Iron & Oak Tier 2; Stockroom Tier 1/2; Utility Line Tier 1/2; Bay & Bolt Tier 1/2) | Spec'd nylon/Delrin bushings at every moving contact point (bracket clips, drawer rails, overhead rack pins) — same OEM part family, no cost premium. Added a Lifetime Warranty exclusion for cosmetic coating wear at contact points. For Bay & Bolt and The Utility Line specifically (humid/wet-adjacent installs), spec'd galvanized steel at contact zones since wear there is a real rust risk, not just cosmetic. Field techs to carry a touch-up powder-coat pen. | `iron-oak-closets/claude.md` (Tier 2 sourcing, Lifetime Warranty Structure) + `index.html` (Warranty section callout)<br>`stockroom-standard/claude.md` (Tier 1/2 sourcing, Lifetime Warranty Structure) + `index.html` (Warranty section callout)<br>`the-utility-line/claude.md` (Tier 1/2 sourcing, Lifetime Warranty Structure) + `index.html` (Warranty section callout)<br>`bay-and-bolt/claude.md` (Tier 1/2 sourcing, Lifetime Warranty Structure) + `index.html` (Warranty section callout) |
| 4 | 2026-09-17 | User (Roy) | Requested a way to track document changes, concerns, and where they're resolved | All | Created this log. | `concept-ventures/decision-log.md` (this file) |
| 3 | 2026-09-17 | User (Roy) | Iron & Oak's black iron Tier 1 rod has a rough mill finish — hangers won't glide smoothly | Iron & Oak Closets only | Added a clear satin lacquer finish step to the pre-cut/threading prep, applied to every Tier 1 length. Scoped as cosmetic, not structural — may wear thin at the hanger-contact band, excluded from the Lifetime Structural Warranty. | `iron-oak-closets/claude.md` (Tier 1 sourcing — Surface Finish bullet) + `index.html` (System section track card + callout) |
| 2 | 2026-09-17 | User (Roy) | Wanted the business partner to clearly understand every pitch is a concept, not a finalized design | All four | Added a sticky "CONCEPT DRAFT" banner to every site and a status note at the top of every `claude.md`. | All four `claude.md` files (status blockquote under the title) + all four `index.html` files (`.concept-banner` at the top of `<body>`) |
| 1 | 2026-09-17 | User (Roy) | Disliked the "Ironclad 500" marketing hook's offer to replace a customer's wardrobe for free | Iron & Oak Closets only | Replaced the wardrobe-replacement tagline with "Built to outlast everything you own." — kept the chin-up/500lb demo concept, dropped the specific guarantee language. | `iron-oak-closets/claude.md` (Marketing Hooks & Messaging) + `index.html` (Go-To-Market section, hook-line) |

## Open / Unresolved

| # | Date Raised | Raised By | Concern | Status |
|---|-------------|-----------|---------|--------|
| O-1 | 2026-09-17 | User (Roy) | Questioned whether the Universal Top Rail should be required on Tier 1 at all — "Tier 1 should just be a strong rod that can hold a lot of weight." Tradeoff: the rail adds cost/labor to every Tier 1 job to subsidize an upgrade path that may never be used by most customers. | Discussed, not yet decided. Two options on the table: (a) keep the rail universal across all tiers as the core differentiator, or (b) make Tier 1 direct-to-stud (no rail, cheaper, no upgrade path) and reserve the rail for Tier 2/3 only. No playbook or site changes made pending this decision. |

## How to use this log

- Add a new row to the top table whenever a partner/stakeholder raises a concern or comment that results in a change to a playbook or site.
- Move an item from "Open / Unresolved" to the resolved table once a decision is made and applied.
- The "Addressed In" column should point to the specific file and section, not just the repo — so anyone can jump straight to the change.
