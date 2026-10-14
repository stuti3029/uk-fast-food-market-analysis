# Data Sources, Metric Definitions & Scenario Assumptions

## Status

**Documentation in progress — source-level provenance still requires verification.**

The dashboard images and report design are available, but the underlying source workbook, citations, raw input tables and model formulas have not been supplied for independent checking here. **Do not present the numbers as audited company-reported data until the entries below are completed.**

## Source register — complete before publication or sharing numerical claims

| Data series | Period / scope in report | Original source and direct URL | Reporting definition / transformation | Verification status |
|---|---|---|---|---|
| Greggs annual revenue | 2016–2025; UK | To be added from original research | Distinguish reported vs estimate; GBP and fiscal-year basis | Pending |
| Greggs UK store count | 2016–2025 | To be added | Company-managed vs partner-operated locations | Pending |
| McDonald's UK revenue / system sales | UK comparison; through 2025 | To be added | Differentiate franchise systemwide sales from recognised revenue | Pending |
| KFC, Burger King, Subway UK revenue | UK comparison; through 2025 | To be added | Verify brand/entity, reporting year and scope | Pending |
| Global brand systemwide sales | Global comparison | To be added | Global system sales or company revenue? Currency conversion? | Pending |
| Global store counts | Global comparison | To be added | Financial year-end and franchising definitions | Pending |
| Average transaction value | Brand and format comparisons | To be added | Primary source vs constructed assumption | Pending |
| City-level Greggs revenue and shops | UK city comparison | To be added | Observed vs allocated/estimated figures; allocation formula | Pending |
| 2035 baseline revenue path | Scenario report | Model-derived (input assumptions to be added) | Growth formula, rates and base year | Pending |
| Strategic scenario values | Scenario report | Model-derived (input assumptions to be added) | ATV, store format, expansion and sensitivity assumptions | Pending |

Suggested places to retrieve **primary-source documentation** are the companies' official annual reports and investor-relations disclosures. These are possible source types, **not a claim that they were already used**. Preserve the original document URL, report year and relevant page number.

## Definitions to settle

**Revenue vs systemwide sales.** A franchised brand may report revenue recognised by the parent company and *systemwide sales* made at franchise locations. These are not automatically comparable with a different brand's reported revenue.

**Revenue per store.** Define the numerator, reporting scope, period and average/end-period store denominator. A computed global revenue-per-store number needs the same units on both sides. Verify the units displayed in the existing global comparison before making external claims.

**Average transaction value (ATV).** Usually total sales divided by number of transactions for the specified population and period. Flag any ATV values that are assumptions rather than observed figures.

**Market share.** State the denominator. A share calculated among the five brands in this project is *share of the compared-brand sample*, not national/global market share.

**Location-level estimated revenue.** If a city-level figure is allocated from national revenue rather than sourced from actual city transactions, label it **modelled/estimated** and document the allocation procedure.

## Scenario methodology — complete from the Power BI model

The scenario page compares a baseline with interventions such as an evening-trade expansion, drive-thru expansion and an illustrative McDonald's-style transaction-value case.

Record, for each scenario:

1. **Base year and starting revenue** — reported or estimated, with citation.
2. **Projection period and annual growth method** — rate, compound growth formula, time horizon.
3. **ATV assumption** — baseline, target, proposed mechanism and justification.
4. **Store count and format assumption** — additions, conversions, throughput and same-store effects.
5. **Overlaps and dependencies** — avoid counting the same uplift twice.
6. **Outputs and sensitivity** — best/base/worst cases, limitations and units.

### Unresolved checks for the existing screenshots

- Verify that all 2025 figures were available at the time of the underlying research, or explicitly label them as estimates.
- Confirm whether displayed global totals use GBP, another currency converted to GBP, or an inconsistent combination.
- Recompute revenue-per-store and reconcile any mismatch between amounts shown in different pages.
- Validate UK company revenue versus systemwide/franchise sales definitions.
- Establish evidence for city-level shop/revenue estimates and historical shop counts.
- Record the exact assumptions behind all 2035 revenue values.

## Reproducibility and files

- `dashboard/`: the original Power BI `.pbix` report, if published.
- `images/`: visual exports of four report pages.
- `documentation/data_sources.md`: this provenance and modelling record.

**Dataset licence check:** Only add source data to a public repository if the licence permits redistribution. Company facts can be discussed with proper attribution without redistributing restricted source tables.
