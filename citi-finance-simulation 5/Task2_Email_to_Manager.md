**To:** Joe (Manager at Citi Finance)
**From:** Jesal Chaudhari (Financial Analyst at Citi Finance)
**Subject:** Verification of risk-weighted assets provided by operating units

Dear Joe,

I have independently recalculated the risk-weighted assets (RWA) and capital adequacy ratios (CET1 / RWA) submitted by Operating Units A to D. I used the FRB standardized risk weights (Loans for Cards 100%, Consumer Mortgages 55%, Retail Banking 90%, Unsecured Retail Lending 100%) and the 10.5% minimum from the Basel III methodology note.

In summary, no unit's reported RWA or ratio matches my recalculation, and Units C and D are below the minimum.

| ($'m) | CET1 | Reported RWA | Recalculated RWA | Reported ratio | Recalculated ratio | vs. 10.5% minimum |
|---|---|---|---|---|---|---|
| Unit A | 10.0 | 70.25 | 74.00 | 14.23% | 13.51% | Meets |
| Unit B | 15.0 | 59.50 | 67.00 | 25.21% | 22.39% | Meets |
| Unit C | 20.0 | 244.00 | 256.75 | 8.20% | 7.79% | Below |
| Unit D | 20.0 | 200.23 | 462.50 | 9.99% | 4.32% | Below |

**Discrepancies and inconsistencies**

1. **Wrong card risk weight (all units).** The units' workbook shows Loans for Cards at 25% instead of 100%. Units A, B and C used it, and their RWA reconciles exactly on that basis. This understates RWA and overstates their ratios.
2. **Unit D's RWA cannot be reconciled.** Its reported RWA of $200.23m is below any weighting of its own assets. Even using the incorrect 25% card weight, the total would be $447.50m. The corrected RWA is $462.50m, so the true ratio is 4.32%, less than half the reported 9.99%. I recommend we ask Unit D how it derived $200.23m.
3. **Shortfalls against the 10.5% minimum.** Unit C needs about $27.0m of CET1 against $20.0m held (shortfall about $7.0m). Unit D needs about $48.6m against $20.0m held (shortfall about $28.6m).
4. **Hard-coded submission.** The workbook contains hard-coded RWA and ratio values with no formulas, and the "Below Minimum Capital Adequacy Ratio?" row is blank for every unit.
5. **Definition of the minimum.** The methodology note describes 10.5% as total capital (Tier 1 plus Tier 2, including the 2.5% conservation buffer), whereas the task tests CET1 / RWA against it, which is stricter. Please confirm which measure applies.

**Suggested next steps:** return the corrected card risk weight to all units, ask Unit D to explain its RWA, and ask Units C and D for a capital plan to close their shortfalls.

Many thanks,
Jesal Chaudhari
Financial Analyst, Citi Finance
