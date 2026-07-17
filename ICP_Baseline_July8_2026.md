# ICP Baseline Reference — Updated July 17, 2026
**ICP 4 (Tank 150) and ICP 3 (S2 600) samples sent July 8, received July 16.**

> **Travel hold confirmed:** Today is Friday, July 17, 2026. All trace element dosing (Tank 150 and S2 600) is paused July 18–26. Automated Alk/Ca pumps continue running unattended on both tanks. Dosing resumes **Monday, July 27**.

> **Tank naming/volume correction:** "Tank 90" is renamed **S2 600** (after the Cade S600 S2 system). Actual system volume is **70 gallons total**, not 90 — current water volume in tank + sump is approximately **65 gallons**. This affects dosing-per-gallon calculations; any dose targets or consumption-rate math referencing this system should use 65–70 gal, not 90 gal.

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

**Ca pump update:**
| Date | Pump | Trident reading | Notes |
|---|---|---|---|
| Jul 15, 2026 | Reduced to 90 ml/day | 470 mg/L | Ca had been creeping up on Trident readings; pump trimmed from 100 ml/day. |
| Jul 16, 2026 | 90 ml/day | 461 mg/L | ~9 mg/L/day decline (Trident-based). Note: Trident Ca is known unreliable (offsets +5 to +67 mg/L per prior ICP cross-referencing) — treat this rate as a rough signal only. Get a Salifert reading to confirm before further pump adjustments. |
| Jul 17, 2026, 14:41 | 90 ml/day | **Salifert: 470 mg/L** | Salifert shows no decline from the earlier 470 mg/L baseline, despite Trident showing a drop to 461 the day before. This is exactly the kind of Trident/Salifert mismatch flagged earlier — hold at 90 ml/day and keep using Salifert (not Trident) as the basis for any further pump changes. Still above the 420–440 ceiling. |

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
| Jul 11, 2026 (approx.) | 20 gal (actual) | ~31% of ~65 gal current volume | ESV Alk pump confirmed OFF post-WC (Reef Crystals adds ~1 dKH). Counts as 1 of 2 planned WCs to dilute Fluoride overdose (~3.12 mg/L) back toward target. |
| Jul 12, 2026, 13:30 | — | ~24 hrs post-WC test | Alk 8.8 dKH (still above 8.5 restart threshold — ESV Alk stays off), Ca 470 mg/L (above 440 ceiling — ESV Ca stays off), Mg 1320 mg/L (back in 1300–1350 range, down from 1410 — good). |
| Jul 16, 2026, 14:17 | — | retest, 4.03 days later | Alk 7.3 dKH (below 7.8 floor), Ca 450 mg/L (still above 440 ceiling), Mg 1305 mg/L (still in range, low end). **Consumption rates calculated over this interval: Alk ~0.37 dKH/day, Ca ~5.0 mg/L/day, Mg ~3.7 mg/L/day.** |
| Jul 16, 2026 | — | ESV Alk restarted | Restarted ESV Alk Component 1 at **10 ml/day** (same rate as pre-WC, which previously held Alk in range). Retest planned ~2–3 days (Jul 18–19) — adjust up in small increments if not climbing back toward 7.8–8.5 by then. Ca pump remains OFF (450 mg/L, still above 440 ceiling; ~5 mg/L/day consumption should bring it into range around Jul 18). |

---

## Tank 50 — Current Status
*Not part of this ICP round, but tracked alongside since parameters are actively moving*

| Parameter | Reading (Jul 12) | Target | Status |
|---|---|---|---|
| Alkalinity | 8.8 dKH | 7.8–8.5 | 🔴 Above restart threshold — ESV Alk stays off |
| Calcium | 490 mg/L | 420–440 | 🔴 Above ceiling (up from 450) — ESV Ca stays off |
| Magnesium | 1365 mg/L | 1300–1350 | 🟡 Slightly above range |

**Dosing status:** Both ESV Alk and Ca pumps currently off. Restart Alk when Salifert reads below 8.5; restart Ca at 2 ml/day when below 440.

**Note:** Ca rising from 450 → 490 while dosing is off is a bit more than the ~0.3–0.5 mg/L/day consumption rate would predict — worth a re-test in a few days to confirm the reading rather than reacting to a single data point (Salifert Ca variability is ±10 mg/L).

---

## Daily Status Log

**July 12, 2026** — All daily dosing completed for Tank 150 and S2 600. Pump status confirmed:
- Tank 150: Alk (144 ml/day) and Ca (100 ml/day) automated pumps running normally. All daily trace elements dosed.
- S2 600: ESV Alk and Ca pumps both OFF (post-WC recovery — Alk 8.8, Ca 470, both above restart thresholds). Daily trace elements dosed as scheduled; Cobalt/Selenium/Vanadium/Fluoride remain stopped pending ICP.
- Tank 50: ESV Alk and Ca pumps both OFF (Alk 8.8, Ca 490, both above restart thresholds).

No pump restarts needed as of this date. Next checkpoints: Tank 150 Ca retest ~July 14, S2 600/Tank 50 Alk+Ca retest in a few days, ICP 3 & 4 results ~July 18.

---

## ICP Results Received — July 16, 2026

*Lab analysis date: July 16. Samples were collected July 8 (before dosing, before lights) — these values reflect tank chemistry as of July 8, not current-day conditions.*

### Tank 150 — ICP 4 (MSR236096)

| Parameter | ICP (true) | Compare to | Notes |
|---|---|---|---|
| Calcium | 454 mg/L | Trident 486 / Salifert 470 (both Jul 8) | Trident offset this cycle: +32 mg/L — within the established +5 to +67 unreliable range. Salifert ran ~16 high. Reinforces Salifert-only for Ca decisions. |
| Magnesium | 1357 mg/L | Trident 1327 → formula (+17) predicted 1344 | Formula landed within 13 mg/L of true value — holds up reasonably well. |
| Phosphate | 0.051 mg/L | Hanna 0.13–0.14 (Jul 8) | ICP shows in-range (0.02–0.09 target); Hanna showed above ceiling same week — worth a fresh Hanna check now. |
| Nitrate | 1.99 mg/L | Hanna 2.2–3.6 | Confirms NO3 is genuinely low, not a Hanna artifact. |
| Fluoride | 1.05 mg/L | — | Post-correction-cycle level (cycle completed Jul 6). |
| Alkalinity | 8.26 dKH | Trident 7.91 (Jul 8) → true 8.43 via +0.52 offset | Direct ICP alk reading available this cycle; in target range 7.8–8.5. |
| Salinity | 37.8 PSU | — | Slightly above the usual 34–35 target — worth a refractometer cross-check. |
| Barium | 8.56 µg/L | — | Post-correction-cycle level. |
| Strontium | 7.2 mg/L | — | Post-correction-cycle level. |
| Zinc | 0.25 µg/L | — | Post-correction-cycle level. |
| Iron | 0.03 µg/L | — | Low — likely pre-dose trough (sample taken before daily dosing per protocol). |
| Copper | 0.24 µg/L | — | Likely pre-dose trough. |
| Manganese | 0.14 µg/L | — | Likely pre-dose trough. |
| Cobalt | 0.21 µg/L | — | No established Tank 150-specific ceiling. |
| Chromium | 1.23 µg/L | — | — |
| Selenium | 0.369 µg/L | — | — |
| Vanadium | 0.76 µg/L | — | — |
| Nickel | 3.09 µg/L | Dashboard target ~2.5 | Slightly above; minor, not flagged as urgent. |
| Iodine | 98.6 µg/L | Target 75–95 | Slightly above ceiling; minor. |
| Lithium | 412 µg/L | — | Informational; BRS 2-part system avoids ESV lithium accumulation issue. |
| Silicate | 238 µg/L | — | Informational. |

**No stop/resume trace actions needed for Tank 150** — this ICP mainly confirms the existing Salifert-only Ca approach and validates the Mg offset formula.

### S2 600 — ICP 3 (MSR235795)

| Parameter | ICP (true) | Compare to | Notes |
|---|---|---|---|
| Calcium | 471 mg/L | Salifert 470 (Jul 8 baseline) | Excellent agreement — Salifert has been accurate for Ca on this tank. |
| Magnesium | 1428 mg/L | Salifert 1410 (Jul 8) | Close match, consistent with known "Salifert reads low" pattern here. |
| Phosphate | 0.331 mg/L | Hanna 0.39–0.54 | Same conclusion (well above ceiling), different magnitude due to method. |
| Nitrate | 23.02 mg/L | Hanna 18.7–19.3 | Confirms still above ceiling. |
| Nitrite | 0.046 mg/L | *(new — not previously tracked)* | Small but present; worth watching. |
| Alkalinity | 8.22 dKH | Salifert 7.3 (afternoon Jul 16) | ICP reflects Jul 8 sample, predates the Alk decline/restart — not directly comparable to the Jul 16 low reading. |
| Salinity | 37.1 PSU | — | Slightly above the usual 34–35 target — worth a refractometer cross-check. |
| Nickel | 3.27 µg/L | Dashboard target ~2.5 | Slightly above; minor. |
| **Iodine** | **227.6 µg/L** | **Target 75–95** | 🔴 **Over 2× ceiling** — same scale of deviation as the Cobalt/Selenium/Vanadium overcorrection last cycle. Recommend stopping Iodine dosing (6–8 drops/day) until retested and back in range. |
| Lithium | 677 µg/L | Was 807 µg/L (prior ICP) | Declining as expected via water-change dilution — not a concern. |
| Strontium | 16.3 mg/L | Was 20.7 mg/L (prior ICP), no-dose threshold <12 | Declining but still above threshold — no dosing. |

**Resume-threshold trace elements:**

| Element | ICP value | Resume threshold | Verdict |
|---|---|---|---|
| Cobalt | 0.23 µg/L | <0.50 | ✅ Clear to resume |
| Selenium | 0.31 µg/L | <0.45 | ✅ Clear to resume |
| Vanadium | 1.23 µg/L | <2.0 | ✅ Clear to resume |
| Fluoride | 2.04 mg/L | <2.0 | 🔴 Still just above — keep stopped, recheck after travel |
| Iodine | 227.6 µg/L | back in 75–95 range | 🔴 Over 2× ceiling — stop dosing, recheck after travel |

**Decision:** Since trace dosing is paused for travel Jul 18–26 regardless, hold off resuming Cobalt/Selenium/Vanadium until return (**Monday, July 27**, confirmed) rather than starting them one day before the pause. Fluoride, Strontium, and now Iodine all stay stopped either way — recheck Fluoride and Iodine specifically after the trip, with Iodine being the bigger outlier of the two.

---

## Correction Dosing Plan — from Reef Moonshiner's ICP-MS Tool (computed Jul 17, 2026)

*Computed directly from the actual RM ICP-MS Assessment tool (Rev. R11a) using the Jul 16 ICP results. Corrections scheduled starting Jul 27 (end of travel hold). Going forward, correction dosing is computed fresh from each ICP rather than following a fixed calendar cycle.*

### Tank 150 (150 gal)

| Element | Target | Dose | Duration | Days |
|---|---|---|---|---|
| Barium | 15 µg/L | 36.57 ml/day | 1 day | Jul 27 |
| Molybdenum | 15 µg/L | 14.76 ml/day | 1 day | Jul 27 |
| Rubidium | 300 µg/L | 17.38 ml/day | 1 day | Jul 27 |
| Potassium | 410 mg/L | 220.17 ml/day | 1 day | Jul 27 |
| Caesium | 5 µg/L | 1.08 ml/day | 2 days | Jul 27–28 |
| Strontium | 10 mg/L | 9.81 ml/day | 3 days | Jul 27–29 |
| Zinc | 5 µg/L | 0.90 ml/day | 3 days | Jul 27–29 |
| Fluoride | 1.5 mg/L | 51.10 ml/day | 5 days | Jul 27–31 |
| Calcium, Magnesium, Nickel | — | **No correction needed** | — | already at/above target |

### S2 600 (65 gal)

| Element | Target | Dose | Duration | Days |
|---|---|---|---|---|
| Potassium | 410 mg/L | 85.36 ml/day | 1 day | Jul 27 |
| Rubidium | 300 µg/L | 20.37 ml/day | 1 day | Jul 27 |
| Molybdenum | 15 µg/L | 6.03 ml/day | 2 days | Jul 27–28 |
| Caesium | 5 µg/L | 0.42 ml/day | 2 days | Jul 27–28 |
| Calcium, Magnesium, Strontium, Barium, Fluoride, Zinc, Nickel | — | **No correction needed** | — | already at or above target |

**Data gap:** Boron and Bromine cannot be assessed — neither ICP-MS CSV contains columns for them. Any tool output suggesting otherwise is an artifact of leaving those fields blank, not a real reading.

**Daily elements clarified (per Handbook):** Cobalt, Selenium, Chromium, Iron, Manganese, Copper are daily-dosed at small standard increments — they are not "correction-band" elements, and low ICP readings for these don't indicate deficiency the way Calcium or Magnesium would. Vanadium and Iodine are dosed daily *until* their target is reached (1–2 µg/L and 75–95 µg/L respectively), then maintained — Iodine on S2 600 is currently well above that range (227.6 µg/L) and should stay stopped until retested.

---

## Action Items
- [x] Tank 150: Salifert Ca reading obtained (470, later retested 470 again Jul 17)
- [ ] Tank 150: monitor NO3 trend — consider KNO3 if not >4 mg/L within 2 weeks
- [ ] Tank 90/S2 600: continue Hammer mysis feeding + photo tracking
- [ ] Tank 90/S2 600: reassess NO3 export strategy if next WC doesn't show a drop
- [ ] Tank 90/S2 600: watch Mg — don't let ESV Ca stay off long enough to crash it again
- [ ] Tank 50: not part of ICP rounds so far — keep Salifert checks going
- [ ] **Post-travel (Monday, July 27): resume Cobalt, Selenium, Vanadium dosing on S2 600** (all confirmed clear by ICP 3); also assess Iodine (was 227.6 µg/L, over 2× ceiling) before resuming
- [ ] **Post-travel: recheck Fluoride on S2 600** — was 2.04 mg/L, just above the 2.0 resume threshold
- [ ] Tank 150: recheck Hanna PO4 — ICP showed in-range (0.051) but Hanna showed above ceiling same week
