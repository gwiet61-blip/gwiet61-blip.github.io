# ICP Baseline Reference — July 8, 2026
**Samples sent today. Expected results: ~July 18, 2026 (10-day turnaround)**

> **Tank naming/volume correction (added July 9, 2026):** "Tank 90" is renamed **S2 600** (after the Cade S600 S2 system). Actual system volume is **70 gallons total**, not 90 — current water volume in tank + sump is approximately **65 gallons**. This affects dosing-per-gallon calculations; any dose targets or consumption-rate math referencing this system should use 65–70 gal, not 90 gal.

---

## Tank 150 (SPS) — Baseline

| Parameter | Raw Reading | Converted/True | Target | Status |
|---|---|---|---|---|
| Alkalinity (Trident) | 7.91 dKH | **8.43 dKH** (+0.52 offset) | 7.8–8.5 | ✅ In range |
| Calcium (Trident) | 486 mg/L | *Unreliable — Salifert below* | 420–440 | — |
| Calcium (Salifert) | 470 mg/L | 470 mg/L | 420–440 | 🔴 Above ceiling — holding pump at 100 ml/day, recheck in 5–7 days |
| Magnesium (Trident) | 1327 mg/L | **1344 mg/L** (+17 offset) | 1300–1350 | ✅ In range |
| PO4 (Hanna) | 0.13 mg/L | — | 0.02–0.09 | 🔴 Above ceiling |
| NO3 (Hanna) | 2.2 mg/L | — | 4–15 | 🔴 Below floor (fell further from 3.6) |

**Pump settings at time of sampling:**
- Alk (NaHCO3): 144 ml/day (just reduced from 149)
- Ca (CaCl2): 100 ml/day

**Open question for this ICP cycle:** Ca consumption rate — Salifert variability (±10 mg/L) has made this hard to pin down; estimated 3–6 mg/L/day. This ICP should help calibrate definitively.

**Watch item:** NO3 trending the wrong direction (3.6 → 2.2) despite TDO pellets — may need to reassess if it doesn't reverse soon.

---

## S2 600 (formerly "Tank 90") — Baseline
*70 gal total system volume · ~65 gal current water volume (tank + sump)*

| Parameter | Reading (Salifert/Hanna) | Target | Status |
|---|---|---|---|
| Alkalinity | 8.1 dKH | 7.8–8.5 | ✅ In range |
| Calcium | 470 mg/L | 420–440 | 🔴 Above ceiling |
| Magnesium | 1410 mg/L | 1300–1350 | 🟡 Overshot (corrected from 1170→1380 recently, now creeping higher) |
| PO4 | 0.39 mg/L | 0.02–0.09 | 🟡 Improving from 0.54, still above ceiling |
| NO3 | 19.3 mg/L | 4–15 | 🔴 Above ceiling (ticked up from 18.7 despite WC) |

**Pump settings at time of sampling:**
- Alk (ESV Component 1): 10 ml/day (just restarted)
- Ca (ESV Component 2): OFF

**Trace elements — stopped, awaiting this ICP to confirm resume thresholds:**
- Cobalt: stopped at 0.83 µg/L, resume when <0.50
- Selenium: stopped at 0.732 µg/L, resume when <0.45
- Vanadium: stopped at 3.45 µg/L, resume when <2.0
- Fluoride: stopped after accidental overdose (~3.12 mg/L), resume only when <2.0
- Strontium: no further dosing (was 20.7 mg/L, >12 ceiling)

**Watch items:**
- Mg overshoot — don't let it become another crash-correct cycle
- NO3 moved wrong direction post-WC — check if WC cadence/volume is actually netting export
- Hammer recession — primary focus, target feed mysis every 2–3 days lights-out, photo every 3–4 days
- Lithium (807 µg/L) — confirmed benign/ESV-sourced, just tracking via WC dilution, not a concern

**Water change log:**
| Date | Volume | % of system | Notes |
|---|---|---|---|
| Jul 9, 2026 | 20 gal (actual) | ~31% of ~65 gal current volume | ESV Alk pump paused before/during change (Reef Crystals adds ~1 dKH). Restart only when Salifert Alk confirmed below 8.5. Counts as 1 of 2 planned WCs to dilute Fluoride overdose (~3.12 mg/L) back toward target. Also expected to help pull Mg (1410 mg/L) back down and provide some NO3 export (19.3 mg/L). Post-WC Alk/Ca/Mg/PO4/NO3 recheck pending. |

---

## Action Items Before Results Land (~July 18)
- [ ] Tank 150: get a Salifert Ca reading to have alongside this Trident-only baseline
- [ ] Tank 150: monitor NO3 trend — consider KNO3 if not >4 mg/L within 2 weeks
- [ ] Tank 90: continue Hammer mysis feeding + photo tracking
- [ ] Tank 90: reassess NO3 export strategy if next WC doesn't show a drop
- [ ] Tank 90: watch Mg — don't let ESV Ca stay off long enough to crash it again
- [ ] Tank 50: not part of this ICP round, but Alk/Ca crossover points likely to hit in this same window — keep Salifert checks going
