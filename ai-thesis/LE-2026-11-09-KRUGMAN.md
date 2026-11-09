# LE-2026-11-09-KRUGMAN — Krugman 11-08 "After the Bubble Bursts" (T3) graded against FRED and price primary (LEDGER ENTRY, proposed)

- **Logged:** 2026-11-09 (Mon), chat session. The author pasted the article without instructions; this entry grades it the same way LE-2026-11-01-SNDK graded the Motley Fool piece.
- **Type:** Ledger entry. **No state change.** No score, node, limb or threshold changed. **MONITOR ONLY / NO TRADE.**
- **Touches:** Financing_Availability (8, BORDERLINE — context only); Capital Reflexivity Stage 4 (context); Composite SUSPENDED (unchanged). Adds a macro-transmission frame (bust → recession → policy space) that the thesis does not yet score.
- **Nature of the source:** a conditional opinion primer ("*if* AI is a bubble and it bursts, what follows"). It does not argue that the bust is happening. Its historical and data claims can be checked; its forecasts cannot.
- **Primary sources:** FRED (St. Louis Fed API), series GDP, A191RL1Q225SBEA, A679RC1Q027SBEA, FEDFUNDS, DFF, LNS12300060, HOUST, UNRATE, BOGZ1FL893064105Q, pulled 2026-11-09. Prices: Tiingo adjusted closes, 2025-06-01 to 2026-11-06 (last close before the article's Nov 8 date).
- **Standing rule:** PERSONAL-DATA-EXCLUSION-01.

## 1. Fact check

| Article claim (T3) | Primary | Grade |
|---|---|---|
| 8 official recessions in the past 60 years | NBER since 1966: 1969–70, 1973–75, 1980, 1981–82, 1990–91, 2001, 2007–09, 2020 = 8 | **CONFIRMED** |
| "Volcker" double-dip recession "of 1973-1975" | The Volcker recessions were 1980 and 1981–82; 1973–75 is the Ford recession named in the same sentence | **TEXT ERROR** (dates repeated; not a substantive claim) |
| Real GDP "growing at 8.6 percent a year by early 1984" | A191RL1Q225SBEA: 9.4% (Q2-83), 8.2% (Q3-83), **8.6% (Q4-83)**, 8.1% (Q1-84) | **CONFIRMED** (the 8.6% print is Q4-83, released early 1984) |
| Volcker squeeze cut housing starts "roughly in half" | HOUST: 2,197k (Apr-78) → 837k (Nov-81) = **−62%** | CONFIRMED, **understated** |
| Recovery from the 1970 recession was fast; 1991 and 2001 recoveries saw prime-age employment keep falling after the official end | LNS12300060: after Nov-70 the trough was only 0.4pt lower and the pre-recession level was regained by Mar-73. After Mar-91: fell to 78.1 (Feb-93), regained Sep-94. After Nov-01: fell to **78.6 (Sep-03)**, 24 months on −1.25%, and the pre-recession 81.3 was **not regained within 5 years** | **CONFIRMED** |
| Unemployment did not return to pre-crash levels until 2015 | UNRATE: 2007 low 4.4% (Mar-07); first ≤5.0% in Sep-15, first ≤4.6% in Feb-17 | CONFIRMED on a ~5% pre-crash basis; **2017** on the 2007 low |
| Fed funds was 6.5% when the IT bubble burst, cut to 1% | FEDFUNDS: 6.54% (Jul-00); 0.98% (Dec-03) | **CONFIRMED** |
| Fed funds "only 4 percent" today | DFF **3.88%** (Oct 20 – Nov 5) | **CONFIRMED** (rounded). Maximum cut to zero ≈ **3.9pp vs the 5.5pp used in 2001–03** |
| Tech spending as a share of GDP is "substantially bigger" than the 1990s (Chart 5) | Info-processing equipment + software (A679RC1Q027SBEA / GDP): 1990s peak **4.46% (Q4-00)**; Q2-26 5.05%; **Q3-26 5.35%** | **CONFIRMED**, gap +0.9pp of GDP |
| "These data only go up through the second quarter of 2026" | Q3-26 advance GDP was published **Oct 29**, ten days before the article | **STALE** — the newer print makes the article's point stronger (+0.30pp of GDP in one quarter) |
| Overall stock market cap / GDP fell ~50% in the dot-com bust (Chart 6) | Corporate equities, all sectors (Z.1) / GDP: 210% (Q1-00) → 112% (Q3-02) = **−47%** | **CONFIRMED** |
| Valuations / GDP much higher this time | Same series: 321% (Q4-21), 346% (Q4-25), **380% (Q2-26)** — 1.8× the 2000 peak | **CONFIRMED** |
| "Prices of hyperscaler stocks are down 27 percent since their peak" | Drawdown from peak (since 2025-06) to Nov 6: MSFT −4.5%, GOOGL −29.2%, AMZN −8.7%, META −22.5%, ORCL −64.1%. Equal-weight big four **−16.2%**; with ORCL **−25.8%** | **NOT REPRODUCED** for the big four; consistent only if Oracle is in the basket. Basket not named in the article |
| Cost of default insurance on AI-company bonds "has soared" | Already in ledger: CRWV CDS ~903bp (Oct 12) → record 1,167bp (Oct 22), S&P series (LE-2026-11-01-FINGATE §4). Not re-retrieved | CONSISTENT with ledger, not re-checked |
| Large share of AI capex is imported equipment (Korea, Taiwan) | Not checked against import data this session | NOT VERIFIED (plausible) |
| Bernstein–Cummings: AI bust shock ~3× the dot-com bust | Op-ed not retrieved | NOT VERIFIED |

**Overall grade:** the history and data are accurate. There are two date slips and one stale chart. The one current market figure (−27%) cannot be reproduced without knowing the basket.

## 2. What matters for the thesis (beyond the article)

1. **The macro gate has not opened yet.** The article is conditional, and the primary data show the condition has not been met: real GDP +3.4% in Q3-26, unemployment 4.1% (Oct), prime-age EPOP 80.7 (Oct, flat since spring). The AI capex share is still **rising** (5.05% → 5.35% of GDP in Q3). There is no sign yet of a capex rollover in the national accounts; the next read is Q4-26 advance GDP (late Jan).
2. **Size of the hole if capex reverts.** The 2000–03 unwind took IPE + software from 4.46% to 3.43% of GDP (−1.0pp, −23%). The same proportional drop from Q3-26 is about **−1.2pp of GDP** before import leakage and multipliers. A drop back to the pre-boom 2023–24 level (~4.1%) is also about −1.2pp. This is a rough sizing anchor, not a forecast. Krugman's import caveat (chips made in Asia) would shrink the domestic hit; this session did not measure it.
3. **The wealth channel is bigger than the capex channel.** Equities / GDP at 380% vs 210% in 2000 means a given percentage fall removes about 1.8× as much wealth relative to income. This is the article's strongest point, and the data support it. Wealth losses so far are concentrated: SPY −5.6% and equal-weight RSP −3.3% from peak, against QQQ −13.6%, NVDA −22%, ORCL −64% and CRWV −75%. So far the selloff looks like **rotation, not a move to cash**, which is the mild case Krugman describes. Watch the RSP/QQQ spread.
4. **Policy room is thinner, on the article's own numbers.** There is ~3.9pp of rate room against the 5.5pp used in 2001. This bears on how much a financing shock spreads to the wider economy. It does not bear on whether the shock happens (Financing_Availability).
5. **Overlap with existing gates:** the CoreWeave/Oracle debt concern is the same one already tracked under Financing_Availability 8 BORDERLINE and HY-CREDIT-01. The article adds no new data on it.

## 3. Disposition

- **No state change.** Financing_Availability 8 HELD (BORDERLINE); Capital Reflexivity Stage 4 unchanged; Composite SUSPENDED; all other scores unchanged.
- **Proposed annotations (author):**
  1. Consider a **macro-transmission watch** (no weight yet), keyed to primary series: (a) IPE+software / GDP falls q/q (first sign of a capex rollover); (b) prime-age EPOP falls ≥0.5pt from 80.7 over 3 months; (c) equities / GDP (Z.1, Q3-26 due ~Dec) falls >15% from 380%. A trigger means "the bust has reached the real economy". It is separate from the financing gates.
  2. Record the **policy-space fact**: fed funds 3.88% vs 6.54% at the 2000 peak.
  3. Watch the RSP vs QQQ gap as the rotation-vs-cash test Krugman sets out (equal-weight holding up = rotation).
- **DECISION: MONITOR ONLY / NO TRADE.**

## 4. Sources

- Article: Paul Krugman, "After the Bubble Bursts: What past recessions can tell us about the AI hangover," Substack (paid), 2026-11-08 (author-pasted text).
- FRED API (api.stlouisfed.org), series listed in the header; GDP/investment last updated 2026-10-29 (Q3-26 advance); labor series updated 2026-11-06 (Oct data); Z.1 equities updated 2026-09-11 (through Q2-26).
- Tiingo daily adjusted closes for MSFT, GOOGL, AMZN, META, ORCL, CRWV, NVDA, SPY, QQQ, RSP through 2026-11-06. Peaks are measured from 2025-06-01 onward.
- Prior ledger: LE-2026-11-01-FINGATE §4 (CRWV CDS series).
