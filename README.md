![](https://github.com/oluwagbemiga01/Seplat-fy2025-financial-analysis/blob/main/Dashboard%20Image.png)

# Inside Seplat Energy's FY2025 Numbers
### Revenue grew 144%. Net income grew only 13%. Here's why and what it means for Seplat's exposure to oil price risk.

An independent financial analysis of Seplat Energy's FY2025 results, built entirely from publicly disclosed data. This project traces exactly where Seplat's revenue growth was absorbed by rising costs, and builds a forward-looking oil price sensitivity model to identify the company's approximate net income breakeven point.

---

## Agenda

- [Problem Statement](#problem-statement)
- [Data Overview](#data-overview)
- [Tools & Methods](#tools--methods)
- [Analysis & Findings](#analysis--findings)
- [Methodology Notes & Limitations](#methodology-notes--limitations)
- [Recommendations](#recommendations)
- [About Me](#about-me)

---

## Problem Statement

In FY2025, Seplat Energy reported a 144% increase in revenue, driven primarily by the MPNU offshore acquisition. On the surface, this looks like an outstanding year. But net income grew by only 13% over the same period — a disconnect large enough to warrant investigation.

This project set out to answer three questions:

1. **Where exactly did the additional $1.6B in revenue go**, if so little of it reached net income?
2. **Which costs are structural** (tied to the business model, the acquisition, or government terms) versus which are operational and within management's control?
3. **How exposed is Seplat to a falling oil price**, given its current cost structure and at what price does the business stop being profitable?

---

## Data Overview

All figures used in this analysis are sourced directly from Seplat Energy's publicly disclosed financial statements:

- **FY2025 Financial Results** (published February 2026)
- **FY2024 Annual Report** (published April 2025)

Both documents are publicly available at [seplatenergy.com/investors](https://www.seplatenergy.com). No internal, confidential, or non-public information was used at any point in this project.

**Key line items extracted:** Revenue, Production Costs, Royalties, DD&A (Depreciation, Depletion & Amortisation), Regulatory Fees, G&A Expenses, Other Income, Net Finance Costs, Income Tax Expense, Net Income, Production Volumes, and Average Realised Oil Price.

---

## Tools & Methods

| Tool | Purpose |
|---|---|
| **Excel** | Financial statement modelling, cost waterfall construction, oil price sensitivity analysis, breakeven calculation |
| **Power BI** | Three-page interactive dashboard — Power Query (data shaping/unpivoting), DAX (calculated measures), data visualization |
| **Power BI DAX** | Custom measures for YoY growth, margin ratios, effective tax rate, and cost composition |

---

## Analysis & Findings

### 1. The Revenue to Profit Gap

Of the **$1,609.7M** increase in revenue between FY2024 and FY2025, only **$18.8M** survived to net income. The rest was absorbed by:

| Cost Driver | YoY Change |
|---|---|
| Royalties | +$329.3M (+226%) |
| DD&A (Depreciation) | +$355.4M (+183%) |
| Production Costs | +$340.2M (+83%) |
| Income Tax | +$212.6M (+168%) |
| G&A Expenses | +$103.8M (+71%) |

The effective tax rate climbed from **47.3%** to **68.0%** year over year, driven largely by the offshore assets acquired through the MPNU transaction, which sit under a different and more burdensome tax regime than Seplat's legacy onshore portfolio.

### 2. Margins Diverged Sharply

| Margin | FY2024 | FY2025 |
|---|---|---|
| Gross Margin | 31.6% | 33.2% |
| EBITDA Margin | 46.6% | 44.9% |
| **Net Income Margin** | **12.6%** | **5.8%** |
| Effective Tax Rate | 47.3% | 68.0% |

Gross and EBITDA margins held broadly stable — meaning the *operational* side of the business performed reasonably well. The collapse is concentrated almost entirely in the **post EBITDA** items: depreciation, finance costs, and tax — all largely outside operational control in the short term.

### 3. Oil Price Sensitivity & Breakeven

Using Seplat's FY2025 cost structure as a fixed base, a six-point oil price sensitivity model was built, flexing only the oil price assumption:

| Oil Price ($/bbl) | Modelled Net Income ($M) |
|---|---|
| $45 | ($39.8) |
| $55 | $43.6 |
| $65 | $126.9 |
| $70.29 (FY2025 actual) | $171.0 |
| $80 | $252.0 |
| $90 | $335.3 |


**Approximate net income breakeven: $49.78/bbl**

This figure sits remarkably close to Seplat's own disclosed hedging floor of **$50–55/bbl** — suggesting the company's own risk management approach is calibrated around a very similar pressure point to what this independent model identified.

---

## Methodology Notes & Limitations

In the interest of transparency, this model carries a few documented simplifications:

- **NGL Revenue** (a new revenue stream from the offshore assets in FY2025) was derived as a residual figure (~$79.4M) rather than pulled from a disclosed line item, since it was not separately broken out in the summary results.
- **A ~$37.4M variance** exists between this model's calculated Profit Before Tax and Seplat's reported figure at the actual FY2025 oil price, attributable to additional non-operating/financing items not separately itemized in the public summary results.
- **An adjustment of $100.4M** was applied to FY2024 (as "Other Financial Income") to reconcile modelled Profit Before Tax to the reported figure; no equivalent adjustment was required for FY2025, where modelled and reported figures aligned directly.
- The sensitivity model assumes Seplat's **FY2025 cost structure remains fixed** across all price scenarios — in reality, severe price declines could trigger cost-cutting measures not captured here.

These variances are immaterial to the directional conclusions of the analysis but are disclosed here in full, consistent with sound modelling practice.

---

## Recommendations

Based on this analysis, the following are offered as discussion points rather than prescriptions:

1. **Monitor the offshore cost base closely.** Production costs and DD&A tied to the MPNU acquisition are structurally higher per barrel than the legacy onshore portfolio. Continued cost discipline here has the most leverage over future margin recovery.
2. **Hedging strategy appears well calibrated.** The independently modelled breakeven ($49.78/bbl) sits just below Seplat's disclosed hedge floor ($50-55/bbl), suggesting the existing hedging programme is appropriately positioned against downside price risk.
3. **Tax exposure warrants continued attention.** With the effective tax rate at 68% in FY2025, any structural relief (e.g. PIA-related conversions already underway for onshore assets) could materially improve net income conversion going forward, independent of operational performance.

---

## About Me

I'm **Oluwagbemiga Agbeje**, a Geology graduate (BSc, Federal University of Technology Akure, 2023) based in Nigeria, building toward a career as an Energy Data Analyst in Nigeria's oil and gas sector. I work primarily in Power BI, SQL, Python, and Excel.

This project was built entirely from public data, independently, as a demonstration of how I think about energy sector data.

**Portfolio:** [agbeje.netlify.app](https://agbeje.netlify.app)
**LinkedIn:** [https://www.linkedin.com/in/oluwagbemiga-agbeje/]
**Email:** [Gbemiga100@gmail.com]

---

*All data used in this analysis is sourced from Seplat Energy's publicly disclosed financial statements. This is an independent, unaffiliated analysis and does not represent the views or positions of Seplat Energy plc.*
