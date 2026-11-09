# LE-2026-11-09-MACROWATCH — Register MACRO-TRANSMISSION-01 v0.1 (LEDGER ENTRY)

- **Logged:** 2026-11-09 (Mon), chat session, at author instruction ("add the macro-transmission watch to the ledger"). Applies proposed annotation 1 of LE-2026-11-09-KRUGMAN.
- **Type:** Ledger entry. **New watch registered: RESEARCH ONLY / ZERO WEIGHT.** No score, node, limb or threshold of any existing control changed. **MONITOR ONLY / NO TRADE.**
- **Touches:** new record MACRO-TRANSMISSION-01; cross-refs Financing_Availability (8, BORDERLINE), Capital Reflexivity Stage 4, Composite SUSPENDED (all unchanged).
- **Standing rule:** PERSONAL-DATA-EXCLUSION-01.

## 1. Purpose

The financing gates (Financing_Availability, HY-CREDIT-01, TW-VF-GUARANTEE-01) ask whether the AI build-out **can keep being funded**. This watch asks a different question: **has an AI capex or valuation unwind reached the real US economy?** Its signals are the transmission channels Krugman's primer sets out (LE-2026-11-09-KRUGMAN §2): the capex hole, labor, and household wealth. A firing does not change any score by itself. It flags the record for author review.

## 2. Limbs (primary series only, FRED)

| Limb | Series | Definition | Baseline (as of 2026-11-09) | Fires when | Next read |
|---|---|---|---|---|---|
| **M1 Capex rollover** | A679RC1Q027SBEA / GDP (nominal, SAAR) | Information-processing equipment + software as % of GDP | **5.35%** (Q3-26 advance); Q2-26 5.05% | Share falls q/q in any GDP release (advance or revised). Record the nominal level change alongside it, so that a fall caused by GDP growth outpacing flat capex can be told apart from an outright cut | Q4-26 advance GDP (~late Jan 2027) |
| **M2 Labor** | LNS12300060 (prime-age 25–54 EPOP, SA) | 3-month moving average | Oct-26 level **80.7**; 3-mo avg (Aug–Oct) 80.6 | 3-month average ≤ **80.2**, i.e. ≥0.5pt below the 80.7 baseline | Nov-26 jobs report (early Dec) |
| **M3 Wealth** | BOGZ1FL893064105Q / GDP (Z.1 corporate equities, all sectors, level ÷ nominal GDP) | Equities as % of GDP | **380%** (Q2-26) | Ratio ≤ **323%**, i.e. a >15% fall from 380% | Z.1 Q3-26 (~mid Dec) |

**Calculation notes:**
- Z.1 equities are in $ millions; GDP is in $ billions. Ratio = equities / 1000 / GDP × 100.
- M1 and M3 use the GDP vintage current on the read date. If the baseline is revised, carry the revised figure and note the revision.
- Every read must cite the series ID, observation date and FRED `last_updated`.

## 3. Status ladder

- **QUIET:** no limb fired (current status).
- **WATCH:** any one limb fired. Log a ledger entry; no score action.
- **ALERT:** two or more limbs fired within the same two-quarter window. Log a ledger entry and put to the author whether MACRO-TRANSMISSION-01 should get weight, and on which score. No automatic score change.
- **Reset:** a limb clears when its series recovers to its baseline.

## 4. Side indicator (not a limb)

The rotation-vs-cash test (LE-2026-11-09-KRUGMAN annotation 3) is **RSP vs QQQ drawdown from peak** (Tiingo adjusted closes). It is noted on each read, but it does not fire. The 2026-11-06 reading was RSP −3.3% and QQQ −13.6% (rotation). If RSP falls by as much as QQQ, the selloff has become a move to cash, and the M3 limb is likely to follow.

## 5. Initial read (2026-11-09)

| Limb | Value | Status |
|---|---|---|
| M1 | 5.35% (Q3-26), up 0.30pp q/q | not fired |
| M2 | 80.7 (Oct-26); 3-mo avg 80.6 | not fired |
| M3 | 380% (Q2-26) | not fired (Q3 pending) |

**MACRO-TRANSMISSION-01 v0.1: QUIET. ZERO WEIGHT.**

## 6. Disposition

- Registered as RESEARCH ONLY / ZERO WEIGHT. All AI Thesis scores unchanged; Composite SUSPENDED.
- LE-2026-11-09-KRUGMAN annotation 1 → **APPLIED** (this entry). Annotations 2 (policy-space fact) and 3 (RSP/QQQ) are carried here as §4 and below:
  - **Policy-space reference:** fed funds (DFF) 3.88% on 2026-11-05 vs 6.54% (FEDFUNDS, Jul-00). Room to zero ≈ 3.9pp vs 5.5pp used in 2001–03.
- **DECISION: MONITOR ONLY / NO TRADE.**
