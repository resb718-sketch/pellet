# Agent 4 — Semiconductor ecosystem / tooling / test (PARTIAL pass 1, as-of 7 Oct 2026)

**Method limit:** search snippets only; no ISM/MeitY/PIB/Cabinet note was opened. All SECONDARY or UNKNOWN. Several snippets are old (2023–2025) and are flagged. Not done: subsidy sanctioned-vs-disbursed per project; exact approval dates/capex for each project; any published vendor-day notice.

## ITEM 4.1: ISM approved projects and status
- **ANSWER:** 12 projects approved with ~₹1.64 lakh Cr pipeline (1 fab, 2 compound-semiconductor fabs, 9 packaging/OSAT units), as of Jun 2026 (Hitavada, SECONDARY). Fiscal support up to 50% of project cost, pari passu (central). ISM 2.0 announced in Budget 2026-27, focused on equipment, materials, indigenous IP and supply chains (SECONDARY) — **this is the part relevant to a tooling/consumables founder.**
- **Per project (SECONDARY):**
  - **Micron, Sanand (ATMP):** US$2.75 B project (Micron ~US$826 M, remainder central + Gujarat subsidy); commercial production started, first made-in-India modules shipped to Dell; guidance: "tens of millions" of chips this year → "hundreds of millions" in 2027.
  - **Tata Electronics, Dholera (fab):** ₹91,000 Cr; 28 nm plus power-management chips; mass production targeted 2027. One snippet mislabels it "compound semiconductor" — treat as an error in that source; not reconciled.
  - **CG Power–Renesas–Stars OSAT, Sanand:** "pilot production expected by July 2025" — OLD snippet; current status DATA NOT AVAILABLE — needs field verification.
  - **Kaynes Semicon:** first paying OSAT customer reported; MoU with Lightspeed Photonics (Singapore).
  - **HCL–Foxconn, Jewar (UP):** 20,000 wafers/month, 36 million chips/month (as reported); status not found.
- **Approval dates, per-project capex, subsidy sanctioned vs disbursed:** DATA NOT AVAILABLE — needs field verification.
- **SOURCES:** https://www.thehitavada.com//Encyc/2026/6/29/-rs-164-lakh-cr.html ; https://inc42.com/buzz/micron-begins-semiconductor-production-from-2-75-bn-sanand-plant/ ; https://india-briefing.com/news/setting-up-a-semiconductor-fabrication-plant-in-india-what-foreign-investors-should-know-22009.html ; https://www.multibagg.ai/market-pulse/articles/india-semiconductor-mission-2-funding-cmr0befix1hoto20jwhfl9fsw
- **CONFIDENCE:** Medium (Micron production, ISM 2.0 focus); Low (everything else).

## ITEM 4.2: DLI scheme
- **ANSWER:** 23 chip-design projects sanctioned; total outlay ₹803.08 Cr including EDA tool costs (MeitY, 30 Jul 2025). Incentives: Product Design Linked Incentive up to 50% of eligible expenditure, capped ₹15 Cr per application; Deployment Linked Incentive 6%→4% of net sales over five years, capped ₹30 Cr. Allocation inside Semicon India: ~₹1,000 Cr (INR 10 bn) for design. Funds are released against milestones.
- **Disbursed to date / outcomes (chips taped out or deployed):** DATA NOT AVAILABLE — needs field verification.
- **Calc:** ₹803.08 Cr ÷ 23 ≈ ₹34.9 Cr average per project (includes EDA costs).
- **TAG:** SECONDARY. **AS-OF:** Jul 2025 (stale by ~15 months).
- **SOURCES:** https://www.india-briefing.com/news/india-backs-23-semiconductor-chip-design-projects-39003.html/ ; https://new.intellinews.com/articles/india-boosts-domestic-chip-design-393796 ; https://elcina.com/assets/pdfs/Guidelines_for_Design_Linked_Incentive_(DLI)_Scheme.pdf (guidelines, not opened)
- **CONFIDENCE:** Medium on approvals; Low on outcomes.

## ITEM 4.3: Localisation / supplier categories
- **ANSWER:** Tata Electronics' Dholera plant is expected to have ~450 suppliers and is developing a 363-acre plug-and-play vendor park with a Singapore developer; suppliers must sit close to the fab (short mean-time-to-repair, spare parts, chemicals, gases). The framing is **international vendors acquiring land** in the park, not Indian-startup localisation. **No published supplier-localisation program or vendor-day notice from Micron, Kaynes, CG Semi or Tata found.** Which categories (test fixtures, burn-in boards, probe cards, cleanroom consumables, gases/chemicals) are open to small Indian suppliers vs locked to global OEMs: DATA NOT AVAILABLE — needs field verification.
- **INFERENCE:** proximity/service-level requirements favour global OEMs' local service entities; Indian small suppliers may fit in maintenance, spares, fixtures and consumables, but no document here supports that.
- **SOURCES:** https://hdfcsky.com/news/tatas-chip-plant-to-have-450-suppliers-building-363-acre-vendor-park-to-house-them-official ; https://visionias.in/current-affairs/upsc-daily-news-summary/article/2026-03-06/business-standard/economy/sanand-20s-swift-semicon-wave-accelerates-indias-chip-ambitions
- **CONFIDENCE:** Low.

## ITEM 4.4: Failures / delays
- **Foxconn–Vedanta US$19.5 B Dholera fab JV:** dissolved Jul 2023 (Foxconn: not moving fast enough). SECONDARY, multiple outlets, same underlying event.
- **Adani–Tower Semiconductor (~US$10 B):** talks paused 30 Apr 2025, reported ended by May 2025, citing demand uncertainty and Tower's financial commitment. SECONDARY. (A snippet header says "2026"; dates in text say 2025 — use 2025.)
- **Zoho:** suspended a US$700 M chip-manufacturing plan (reported a day after the Adani pause).
- **STMicroelectronics talks** collapsed after government insisted on deeper technical involvement (older report).
- **Pending subsidy payments:** Foxconn/Dixon asked India to pay pending production subsidies (Bloomberg, Jan 2025; electronics PLI, not ISM — different scheme, do not conflate).
- **SOURCES:** https://www.electronicsforu.com/technology-trends/indias-fab-vision-on-track-despite-recent-setbacks ; https://governancenow.com/news/regular-story/195-bn-foxconnvedanta-chip-deal-falls-flat ; https://www.bloomberg.com/news/articles/2025-01-08/foxconn-dixon-urge-india-to-pay-pending-production-subsidies (not opened)
- **CONFIDENCE:** Medium.

---
## Closing sections
**(a) Top 3 things that changed my view**
1. The only demand-side hook found for small suppliers is ISM 2.0's stated focus on equipment, materials and supply chains (Budget 2026-27) — not any anchor-fab procurement notice.
2. Anchor-fab supplier models point to global OEM vendors in a Dholera vendor park, with service-time requirements that favour incumbents.
3. Real volumes are still small: Micron "tens of millions" of chips this year; Tata fab not before 2027.

**(b) Evidence that would DISPROVE the case:** no vendor-localisation notices found; two big fab partnerships collapsed (Foxconn–Vedanta, Adani–Tower); Tata's fab not in volume until 2027 — a 12–24-month wait before tooling demand scales (INFERENCE from the 2027 target).

**(c) 6-gate re-score — Semis tooling/test (inference unless noted):**
- G1 demand scale: 3 — ₹1.64 lakh Cr pipeline is real, but spend on small-supplier categories is unknown.
- G2 cost lever 5–10×: 1 — no evidence.
- G3 anchor buyer: 2 — Micron/Tata/Kaynes exist; no localisation program found.
- G4 ₹5–50 Cr first milestone: 2 — no evidence.
- G5 India advantage: 2 — proximity to Sanand/Dholera clusters; ISM 2.0 tailwind (SECONDARY).
- G6 not already won: 3 — categories unverified; global OEMs likely hold the core.
Evidence-backed: only the facts above; the numeric scores are my inference.

**(d) Could not verify:** per-project approval dates, capex, status and subsidy disbursed; DLI disbursed/outcomes; any vendor-day or localisation notice; open-vs-locked supplier categories; CG Semi and HCL-Foxconn current status; all primary documents.
