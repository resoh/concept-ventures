# Iron & Oak Closets — Launch Project Plan

> **Status: Draft launch plan.** Iron & Oak Closets is the first of the four Concept Ventures playbooks slated for real-world deployment. Timelines below are sequencing/dependency estimates, not committed dates — insert actual start date, target metro, and budget before treating this as final. Sourced from `ironOak/claude.md` (product/pricing architecture) and `automate.md` (automation blueprint).

## Deployment Goal

Prove that the Tier 1 → Tier 2 install operation, the digital quoting funnel, and the White-Glove Reset add-on can run profitably in one metro before committing capital to Tier 3 (custom millwork), premium accessories, or a second market. Tier 3 and the accessory catalog (safes, licensed-trade hand-offs) are deliberately deferred out of the pilot — they carry the most compliance and supply-chain complexity per `claude.md` and `automate.md` and shouldn't gate the first deploy.

## Go / No-Go Criteria (before scaling past the pilot)

| Metric | Target |
| :--- | :--- |
| Completed installs | ≥ 20 (Tier 1 + Tier 2 combined) |
| Average gross margin realized | ≥ 65% (per-job guardrail from `claude.md` Financial Models) |
| Warranty/callback rate | Below an agreed threshold — **needs partner input** |
| Lead → booked-deposit conversion | Baseline established for future CAC math |
| Review generation | Automated digital sign-off → review flow (automate.md Pillar 4) firing on ≥ 90% of jobs |

---

## Phased Roadmap

### Phase 0 — Foundation & Legal (Weeks 1–3)
* Business entity, general liability insurance, and any contractor licensing required for structural wall-mounted install work in the target state/metro.
* Banking + bookkeeping stood up (QuickBooks/Xero) ahead of the Phase 2 automation build, per `automate.md` Pillar 5.
* Vendor commercial accounts opened: Ferguson/McMaster-Carr or a regional steel service center (Tier 1), Schulte/ClosetMaid Professional/Knape & Vogt (Tier 2).
* **Decision needed:** pilot metro/territory selection.

### Phase 1 — Product & Pricing Validation (Weeks 2–5, overlaps Phase 0)
* Build 2–3 physical prototype installs (Tier 1 + Tier 2) to validate the BOM, on-site labor-time assumptions, and the two wear-point fixes already logged in `decision-log.md` (clear satin lacquer on Tier 1 rod, nylon/Delrin bushings on Tier 2 clip points).
* Time-and-motion study against the target labor cost band (15–18% of job price) and the tier margin targets in `claude.md`.
* Lock Tier 1/2 SKUs and set initial safety-stock thresholds for reorder automation (Phase 2).

### Phase 2 — Digital & Automation Stack Stand-Up (Weeks 3–6)
Only the pieces of `automate.md` the pilot actually needs — Tier 3/premium-accessory automation is deferred to Phase 5+.
* **Intake & quoting:** web calculator + $99 deposit booking flow (Typeform/Tally + Calendly/HubSpot Meetings API).
* **CRM & lead nurture:** GoHighLevel or ActiveCampaign, including the 3-part drip for calculator-abandoners.
* **Field ops:** Jobber or Housecall Pro for dispatch, route optimization, and digital sign-off → Stripe invoicing → automated review request.
* **Financial guardrail:** per-job margin reconciliation alert wired to actual Jobber/Housecall Pro invoice data.
* Deferred until Tier 3 is in scope: BOM/inventory automation (Katana/Sortly), premium-accessory drop-ship coordination, licensed-trade hand-off automation, warranty-claim webform.

### Phase 3 — Marketing & Sales Assets (Weeks 4–6)
* Publish the public-facing pitch/marketing site content (distinct from the internal `ironOak/index.html` partner pitch).
* Produce the "Ironclad 500" demo video and Meta ad creative.
* Draft the Realtor Partner Closing Gift program materials (voucher terms, referral tracking) — hold the automated payout piece (Stripe Connect/Bill.com) until there's real referral volume to justify it.
* Recruit/vet 1–2 installers (contractor or hire) for the pilot territory.

### Phase 4 — Pilot Launch (Weeks 6–10)
* Soft-launch in the selected metro, Tier 1 + Tier 2 only.
* Weekly cadence: booked installs, margin-guardrail review, warranty registrations, review-generation rate.
* Explicitly out of scope for the pilot: Tier 3, premium accessories, gun-safe compliance flow, property-manager volume program — revisit in Phase 5 once core install ops are proven.

### Phase 5 — Review & Scale Decision (Week 11+)
* Evaluate against the Go/No-Go table above.
* Decide: open up Tier 3 + premium accessories, expand geography, or iterate on the pilot before either.
* Feed pilot learnings back into `ironOak/claude.md` and `decision-log.md` before using this plan as the template for the next venture deploy (Stockroom Standard).

---

## Open Decisions Needing Partner Input
* Pilot metro/territory.
* Actual start date and capital budget (tooling stack in Phase 2 has real monthly SaaS cost — Jobber/Housecall Pro, GoHighLevel/ActiveCampaign, etc.).
* Warranty/callback threshold for the Go/No-Go table.
* Resolution of the still-open item in [`decision-log.md`](https://github.com/resoh/concept-ventures/blob/main/decision-log.md#open--unresolved) (O-1: whether the Universal Top Rail is required on Tier 1, or Tier 1 goes direct-to-stud) — this affects the Phase 1 prototype build and should be settled before Phase 1 locks the BOM.

## References
* `ironOak/claude.md` — product architecture, pricing, warranty structure.
* `automate.md` — full six-pillar automation blueprint (this plan sequences a subset of it for the pilot).
* `decision-log.md` — partner concerns and resolutions to date.
