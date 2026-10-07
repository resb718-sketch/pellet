# Agent 3 — BESS / PCS / EMS (PARTIAL pass 1, as-of 7 Oct 2026)

**Method limit:** search snippets only; no SECI/NTPC tender document, MoP order or customs data was opened. Everything is SECONDARY, ESTIMATE or UNKNOWN. Not done: 3.3 evidence (tender BoMs, customs data), 3.4 an Indian-government order on Chinese inverters, capacity numbers for Delta/Statcon/Exicom/Waaree/Hitachi/L&T.

## ITEM 3.1: Unsubsidised economics, tenders, VGF
- **Tariffs (SECONDARY, units as reported):** SECI on-demand BESS, Reliance Power 500 MW/1,000 MWh at ~₹3.819 lakh/MW/month; NTPC Green Energy 200 MW/800 MWh (WBSEDCL tender) at ₹4.35 lakh/MW/month; Odisha SECI 125 MW/500 MWh auction: "₹3.04–3.75 per kW per month" (Coal India won Cluster I at ₹3.04). **Unit flag:** ₹3.04/kW/month = ₹3,040/MW/month, which is not plausible next to ₹3.8–4.35 *lakh*/MW/month; the Odisha numbers are probably misreported. Treat as UNKNOWN until read from the SECI result. Dates of the first two tenders: not stated in snippet.
- **VGF:** ₹5,400 Cr from PSDF for 30 GWh; ₹18 lakh/MWh; 15 states (25 GWh) + NTPC (5 GWh); investment expected ₹33,000 Cr by 2028. Second tranche reported (IESA/pv-magazine). **Sanctioned vs disbursed:** DATA NOT AVAILABLE — needs field verification. SJVN 265 MW/530 MWh Haryana project cited with ₹18 lakh/MWh VGF.
- **Capex per MWh (ESTIMATE from sourced inputs):** ₹33,000 Cr ÷ 30,000 MWh = ₹1.1 Cr/MWh (= ₹110 lakh/MWh); VGF share = ₹18 lakh ÷ ₹110 lakh ≈ 16.4% (₹5,400 ÷ ₹33,000 Cr agrees). In USD at an assumed ~₹88/$ ≈ $125/kWh (FX assumption, not a sourced rate; I did not sanity-check against an independent BNEF/IEA benchmark).
- **Market flow:** ~3.16 GW of standalone BESS tendered in Aug 2026 (SECONDARY, IEEFA PDF surfaced, unopened).
- **SOURCES:** https://solarquarter.com/2026/03/02/seci-concludes-125-mw-500-mwh-standalone-bess-auction-in-odisha/amp/ ; https://www.energetica-india.net/news/ntpc-green-energy-secures-200-mw-800-mwh-in-wbsedcl-2-gwh-bess-auction ; https://solarquarter.com/2025/06/10/ministry-of-power-launches-%e2%82%b95400-crore-vgf-scheme-to-boost-30-gwh-battery-energy-storage-capacity/ ; https://ieefa.org/sites/default/files/2026-09/ESSjmk-0926.pdf (unopened)
- **CONFIDENCE:** Medium (VGF scheme terms); Low (tariffs, units).

## ITEM 3.2: Local-content rules
- **ANSWER:** MoP directive (Dec 2025) requires **minimum 20% local content (of total project cost)** in BESS under VGF; this includes indigenously developed EMS software, which was already required by the VGF guidelines amendment dated **4 Aug 2025**. Reported: cell-level localisation trajectory aligned with ACC-PLI, with separate domestic-content benchmarks for BMS, power conversion and balance of plant (details not read).
- **Applies to:** VGF-supported projects — NOT shown to apply to non-VGF tenders. ALMM-like battery list: DATA NOT AVAILABLE — needs field verification. Order numbers/text: not read.
- **INFERENCE:** EMS software and balance-of-plant count toward the 20%, so software/PCS from Indian vendors gets a built-in demand pull, but a 20% total-cost threshold can be met by civil/BoP without PCS.
- **SOURCES:** https://www.pv-magazine-india.com/2025/12/31/india-mandates-20-domestic-content-in-battery-storage-projects ; https://www.energy-storage.news/india-introduces-20-domestic-content-rule-for-viability-gap-funding-of-battery-storage/ ; https://solarquarter.com/2025/12/24/ministry-of-power-clarifies-make-in-india-rules-for-bess-projects-under-vgf-scheme/
- **CONFIDENCE:** Medium.

## ITEM 3.3: Who supplies PCS/EMS to winners
- **ANSWER:** Evidence is thin. Found (SECONDARY): Sungrow supplied India's largest BESS (Phyang, Leh, up to 60.56 MWh, with Tata Power Solar), and reports ~13 GW Indian inverter shipments with 10 GW capacity in Bengaluru; Delta India won 110 MW of bi-directional PCS; Fimer 2 MVA units at Capgemini campuses. **Winner-by-winner BoM, customs data, DRHPs:** DATA NOT AVAILABLE — needs field verification. Sungrow's 13 GW figure comes from a vendor-sourced article; not independently confirmed.
- **SOURCES:** https://www.pvtime.org/?p=14157 ; https://www.energetica-india.net/keyword/power-conditioning-systems ; https://www.pv-magazine-india.com/?p=6983
- **CONFIDENCE:** Low.

## ITEM 3.4: Cyber / trusted-source rules (India)
- **ANSWER:** I found NO Indian CEA/MoP direction specifically on Chinese inverters/PCS in this pass. What surfaced: a CEA/MoP guideline for T&D/switchyard equipment allowing foreign suppliers via consortium/JV with Indian manufacturing + ToT (older, not dated here); and foreign developments (EU restricting funding for projects using inverters from high-risk countries; FCC drafting a US import ban; May 2025 US findings of undocumented comms modules). Those are NOT Indian rules — do not read them as such. Indian status/dates/text: DATA NOT AVAILABLE — needs field verification.
- **SOURCES:** https://www.iea.org/commentaries/inverter-supply-chains-and-cybersecurity ; https://eparlib.nic.in/bitstream/123456789/692831/1/44679.pdf
- **CONFIDENCE:** Low.

## ITEM 3.5: Indian PCS/EMS makers (competitors)
- **Named (SECONDARY):** Delta Electronics India (110 MW PCS win), WattPower (string PCS; >18 GW inverter sales), Feston SEV/FestGroup (entering BESS; 3 GWh/yr planned), plus Sungrow's Bengaluru plant (foreign-owned, India-made). Statcon, Exicom, Waaree, Hitachi Energy, L&T capacity/BESS PCS lines: not found this pass.
- **INFERENCE:** a new PCS/EMS entrant faces Delta, WattPower, Sungrow-India, and EMS software from integrators — not an empty field.
- **SOURCES:** https://www.pv-magazine-india.com/?p=13957 ; https://solarquarter.com/2026/04/06/fest-group-feston-sev-pvt-ltd-enters-bess-segment-sets-up-3-gwh-manufacturing-capacity/amp/
- **CONFIDENCE:** Low–Medium.

---
## Closing sections
**(a) Top 3 things that changed my view**
1. A local-content hook exists and explicitly names EMS software (20% of project cost under VGF, Aug/Dec 2025) — the best evidence-backed demand lever for an Indian EMS/PCS entrant.
2. Capex per MWh implied by the scheme (~₹1.1 Cr/MWh, ESTIMATE) with VGF covering ~16% suggests tenders are VGF-driven; unsubsidised economics are not established.
3. I found no Indian trusted-source/cyber ban on Chinese inverters, so that tailwind (present in the US/EU) is unproven for India.

**(b) Evidence that would DISPROVE the case:** Sungrow/Delta/WattPower already in India with scale; 20% local content can be met without PCS; no Indian cyber mandate found; tariffs (~₹3.8–4.35 lakh/MW/month) imply thin developer margins, pushing buyers toward lowest-cost PCS.

**(c) 6-gate re-score — BESS PCS/EMS (inference unless noted):**
- G1 demand scale: 4 — 30 GWh VGF + ~3.16 GW tendered in Aug 2026 (SECONDARY).
- G2 cost lever 5–10×: 1 — no evidence.
- G3 anchor buyer: 3 — SECI/NTPC/state agencies and developers exist but PCS is bought by winners/EPCs (inference).
- G4 ₹5–50 Cr first milestone: 2 — no capex data; software/EMS is cheaper than hardware (inference).
- G5 India advantage: 3 — EMS software named in local-content rule (evidence-backed, secondary); hardware advantage unproven.
- G6 not already won: 2 — Delta, WattPower, Sungrow-India present.

**(d) Could not verify:** primary tender results; Odisha tariff units; VGF disbursed; PCS/EMS supplier per winning bid; customs data; any Indian cyber/trusted-source order; Indian OEM capacities (Statcon, Exicom, Waaree, Hitachi, L&T); ALMM-like battery list; unsubsidised BESS economics.
