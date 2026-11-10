# LE-2026-11-10-L1IMPORTS — Lead L1 worked: import content of the AI capex boom, Census HS detail (LEDGER ENTRY)

- **Logged:** 2026-11-10 (Tue), chat session, at author instruction ("work lead L1 with the Census data"). Works lead L1 of MACRO-TRANSMISSION-01 v0.2 §8 and the open item "large share of AI capex is imported equipment" from LE-2026-11-09-KRUGMAN §1 (NOT VERIFIED).
- **Type:** Ledger entry. **No state change.** No score, node, limb or threshold changed. **MONITOR ONLY / NO TRADE.** L1 → **CLOSED (answered)**; two annotations proposed (§4).
- **Touches:** MACRO-TRANSMISSION-01 v0.2 (M1 sizing, QUIET, zero weight); Physical_AI_Demand (9, context only); LE-2026-11-10-FOOLMACRO §1 (tariff-rate row).
- **Primary sources:** U.S. Census Bureau International Trade API (`timeseries/intltrade/imports/hs`), general imports, customs value (GEN_VAL_MO) and calculated duties (CAL_DUT_MO), monthly 2024-01 to 2026-09, pulled 2026-11-10. FRED NIPA series A679RC1Q027SBEA, Y034RC1Q027SBEA, B935RC1Q027SBEA, B985RC1Q027SBEA, GDP (Q3-26 advance, updated 2026-10-29).
- **Standing rule:** PERSONAL-DATA-EXCLUSION-01.

## 1. Answer

**Yes: the import surge is AI hardware, and the equipment side of the capex boom is almost entirely imported.**

- Total goods imports rose from $818.0B (Q4-25) to **$1,022.8B (Q3-26), +$204.8B (+25%)**.
- HS chapters 84 and 85 (machinery and electronics) account for **+$144.0B, 70%** of that rise. Oil (chapter 27) adds $14.7B. Nothing else exceeds $6B.
- Computers and parts alone (HS 8471 + 8473) went from $111.5B to **$197.4B, +$85.9B, 42%** of the rise.
- Imports of finished computers (HS 8471) now run **above** total US business investment in computers: $548B annualised against $504B (NIPA, Q3-26).

## 2. Data

### 2.1 Imports by quarter (Census, customs value, $B, not seasonally adjusted)

| | Q4-24 | Q3-25 | Q4-25 | Q1-26 | Q2-26 | Q3-26 |
|---|---|---|---|---|---|---|
| Total goods imports | 847.9 | 831.5 | 818.0 | 816.4 | 929.7 | **1,022.8** |
| 8471 Computers (ADP machines) | 38.0 | 68.4 | 81.2 | 88.3 | 106.2 | **136.9** |
| 8473 Computer parts | 15.9 | 19.8 | 30.3 | 31.2 | 40.1 | **60.5** |
| 8517 Network and telecom equipment | 34.9 | 33.1 | 43.9 | 39.9 | 47.6 | 54.9 |
| 8542 Integrated circuits | 11.0 | 9.6 | 12.4 | 12.8 | 13.9 | 15.1 |
| Four-code basket | 99.8 | 130.9 | 167.9 | 172.2 | 207.8 | **267.4** |
| Basket share of all imports | 11.8% | 15.7% | 20.5% | 21.1% | 22.3% | **26.1%** |

Monthly: 8471 imports were **$50.4B in Sep-26**, a record, +147% y/y and 3.5× Sep-24. The four-code basket was $98.4B in Sep-26 (27.8% of all imports).

### 2.2 Which products (HS6, $B per quarter)

| HS6 | Description | Q3-25 | Q4-25 | Q3-26 |
|---|---|---|---|---|
| 847150 | Processing units (servers) | 47.7 | 59.6 | **101.6** |
| 847330 | Parts and accessories (boards, modules) | 19.7 | 30.2 | **60.3** |
| 851762 | Switching and routing equipment | 21.3 | 26.9 | 38.5 |
| 847130 | Laptops | 12.4 | 11.0 | 15.3 |
| 851713 | Smartphones | 10.4 | 15.6 | 14.8 |
| 847180 | Other processing units | 2.8 | 3.8 | 9.3 |
| 847170 | Storage units | 3.7 | 4.1 | 8.4 |
| 854231 | Processors (imported as bare chips) | 7.4 | 9.7 | 9.2 |
| 854232 | Memory chips | 0.5 | 0.7 | 3.4 |

The growth is in data-center lines (servers, parts, switching, storage). Consumer lines (laptops, smartphones) are roughly flat. Bare chip imports are small and flat: the chips arrive already inside servers and boards.

**Data-center hardware basket** (847150 + 847180 + 847170 + 847330): $97.7B (Q4-25) → **$179.6B (Q3-26)**, +$81.9B, 40% of the total import rise. With switching gear (851762): $124.6B → $218.1B, +$93.5B, 46%.

### 2.3 Where from (8471 + 8473, $B per quarter)

| Origin | Q4-25 | Q3-26 | Share Q3-26 |
|---|---|---|---|
| Mexico | 28.5 | **64.4** | 33% |
| Taiwan | 49.1 | 52.3 | 26% |
| Vietnam | 13.0 | 30.5 | 15% |
| Thailand | 10.0 | 13.8 | 7% |
| South Korea | 3.1 | 12.9 | 7% |
| Malaysia | 2.0 | 7.2 | 4% |
| China | 2.2 | 5.0 | 3% |

Krugman's "Korea and Taiwan" is **PARTLY CONFIRMED**. Taiwan is the second-largest origin and Korea is small but up fourfold. The largest origin, and the fastest-growing in dollars, is **Mexico** (server assembly). Origin is recorded by last substantial transformation, so Taiwanese and Korean chips inside Mexican-assembled servers count as Mexico.

### 2.4 Against the national accounts (NIPA, $B SAAR)

| | Q4-25 | Q3-26 | Change |
|---|---|---|---|
| IPE + software (M1 numerator, A679) | 1,495.0 | 1,765.4 | +270.4 |
| of which software (B985) | 774.9 | 831.5 | +56.5 |
| of which information-processing equipment (Y034) | 720.1 | 933.9 | +213.9 |
| of which computers and peripherals (B935) | 339.5 | 504.1 | +164.6 |
| Imports of 8471, annualised (×4, NSA) | 324.8 | 547.6 | +222.8 |
| Imports of data-center hardware basket, annualised | 390.8 | 718.4 | +327.6 |

- Finished-computer imports (8471) equal **109%** of NIPA computer investment in Q3-26. Some imports go to households, government, inventories and re-export, so the ratio can exceed 100%. It means domestic value added in the computers line is close to nil.
- The data-center hardware basket equals **77%** of all information-processing equipment investment and **41%** of the M1 numerator.
- At the margin the leakage is total: since Q4-25 the basket's imports rose $328B annualised against a $214B rise in equipment investment.

## 3. What it means for the thesis

1. **The M1 sizing in LE-2026-11-09-KRUGMAN §2.2 overstates the direct GDP hit.** That entry sized a capex reversion at about −1.2pp of GDP "before import leakage". Imports are subtracted in GDP, so a fall in imported equipment investment is largely offset by a fall in imports. Rough re-sizing (not a forecast):
   - If the unwind is proportional across M1 (−23%, the 2000–03 analogue): equipment −0.65pp and software −0.58pp gross. With ~80% of equipment imported, the domestic hit is about **−0.7pp**.
   - If the unwind is concentrated in computers (computers back to the Q4-24 level, −$318B, −1.0pp gross): with ~90–100% imported, the direct domestic hit is about **−0.1pp**.
   - Range: **−0.1 to −0.7pp of GDP direct**, against −1.2pp gross. The domestic exposure sits in **software** (2.5% of GDP), in data-center construction and power (not in M1; not measured here), and in the wealth channel (M3), which the Krugman entry already ranked first.
2. **The same fact cuts the other way on the upside.** The equipment boom has added little net to US GDP so far. The Q3-26 real GDP growth of +3.4% is not being carried by AI hardware spending in an accounting sense.
3. **No rollover in physical demand through September.** Server imports hit a record in Sep-26 and accelerated in Q3 (8471: +29% q/q). This is hard, monthly, customs-recorded evidence consistent with Physical_AI_Demand 9 (held). It is a quantity-times-price figure, so rising memory and GPU prices are inside it.
4. **Census imports lead M1.** Monthly HS data arrive roughly five weeks after month-end, ahead of the GDP release, and they are nearly the same dollars as NIPA computer investment. A fall in 8471 + 8473 imports would show a capex rollover before M1 can fire.
5. **Trade exposure has shifted to Mexico and Vietnam.** An AI capex unwind would hit Mexican, Taiwanese and Vietnamese exports first. Mexico's share makes USMCA terms relevant to AI hardware cost; not examined here.
6. **Tariff-rate row of LE-2026-11-10-FOOLMACRO, refined.** Census calculated duties ÷ customs value: 9.89% (Q4-25) → **6.52% (Q3-26)**, in line with the NIPA 6.85%. The four-code basket pays **0.4%**; everything else pays 8.7% (down from 12.1%). Of the 3.4pp fall, about **2.9pp is lower rates on other goods** (the non-AI rate stepped down from ~10.4% to ~8.55% in Mar-26; the cause was not researched) and about **0.5pp is mix shift** toward near-duty-free AI hardware. AI hardware is effectively outside the tariff wall.

**Caveats:**
- Census figures are customs-basis and not seasonally adjusted; NIPA is balance-of-payments basis, seasonally adjusted at annual rates. Ratios are approximate.
- HS codes do not identify AI use. 847150 includes non-AI servers and desktop units; 847330 includes PC parts. The basket is an upper bound on AI hardware and the import-content percentages are upper bounds too.
- Imported parts (847330) may be assembled into servers in the US. The parts are still import content, but final assembly adds some domestic value.
- The re-sizing covers only the direct investment-minus-imports arithmetic. It leaves out multipliers, construction, power, and financial channels.

## 4. Disposition

- **L1 → CLOSED (answered).** MACRO-TRANSMISSION-01 v0.2 §8 updated to point here. The Krugman-entry item "large share of AI capex is imported" moves from NOT VERIFIED to **CONFIRMED** (origin mix partly confirmed, §2.3).
- **No state change.** MACRO-TRANSMISSION-01 stays QUIET / ZERO WEIGHT; M1's definition is unchanged. Physical_AI_Demand 9 HELD. Composite SUSPENDED.
- **Proposed annotations (author):**
  1. **M1 net-of-imports note.** Keep the M1 limb as defined (it detects the rollover), but record alongside every M1 read a **domestic-exposure line**: software / GDP (B985 ÷ GDP; 2.52% in Q3-26) and the equipment import ratio from this entry. A fired M1 should be read as "capex is rolling over", with the GDP hit sized from the software and construction pieces, not from the gross share.
  2. **Side indicator S3 (monthly lead for M1, no fire):** Census imports of HS 8471 + 8473, monthly, 3-month sum. Baseline **$197.4B (Jul–Sep 2026)**. Flag for the author if the 3-month sum falls for two consecutive months. Next data: Oct-26, expected in early December (date not checked against the Census calendar).
- **DECISION: MONITOR ONLY / NO TRADE.**

## 5. Sources and method

- Census API: `https://api.census.gov/data/timeseries/intltrade/imports/hs`, variables GEN_VAL_MO, CAL_DUT_MO, I_COMMODITY, CTY_CODE, COMM_LVL (HS2, HS4, HS6). Totals are the sum of all HS2 chapters. Country rows use 4-digit country codes only (regional aggregates excluded); their sum (197.4) matches the HS4 total.
- Quarterly values are the sum of three months. "Annualised" = quarterly sum × 4.
- Duty rate = CAL_DUT_MO ÷ GEN_VAL_MO. Mix-versus-rate split holds the Q4-25 basket share (20.5%) fixed and applies Q3-26 rates.
- FRED API for the NIPA series listed in the header; GDP Q3-26 $33,010.0B SAAR.
- Prior ledger: LE-2026-11-09-KRUGMAN, LE-2026-11-09-MACROWATCH (v0.2), LE-2026-11-10-FOOLMACRO.
