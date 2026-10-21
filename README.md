# Banking Intelligence 360° | Power BI Portfolio Project

An interactive, six-page Power BI report exploring a **synthetic Canadian retail banking dataset** through executive KPIs, customer intelligence, lending and credit risk, transaction activity, and actionable business insights.

> **Data disclosure:** This is a portfolio demonstration using synthetic data, not real customer or bank records. Report figures are illustrative. Measures have not been independently audited against every source record.

## Report pages

1. **Executive Banking Overview** — headline banking KPIs, loan portfolio composition, origination trends, and provincial exposure.
2. **Customer Intelligence** — customer segmentation, age distribution, account types, income, and geography.
3. **Loan & Credit Risk Analytics** — loan balances, default rates, risk bands, and delinquency.
4. **Banking Transactions & Financial Performance** — transaction activity, inflows and outflows, cash flow, and regional patterns.
5. **Executive Insights & Recommendations** — key observations and business recommendations.
6. **Loan Portfolio Deep Dive** — a hidden drillthrough destination for loan-type-specific KPIs, risk, and geographic exposure.

## Dashboard gallery

Preview all six report pages below. Click an image to open the full-size screenshot.

### 1. Executive Banking Overview

[![Executive Banking Overview](screenshots/01-Executive%20Banking%20Overview.png)](screenshots/01-Executive%20Banking%20Overview.png)

### 2. Customer Intelligence

[![Customer Intelligence](screenshots/02-Customer%20Intelligence.png)](screenshots/02-Customer%20Intelligence.png)

### 3. Loan & Credit Risk Analytics

[![Loan & Credit Risk Analytics](screenshots/03-Loan%20and%20Credit%20Risk%20Analysis.png)](screenshots/03-Loan%20and%20Credit%20Risk%20Analysis.png)

### 4. Banking Transactions & Financial Performance

[![Banking Transactions & Financial Performance](screenshots/04-Banking%20Transactions%20and%20Financial%20Performance.png)](screenshots/04-Banking%20Transactions%20and%20Financial%20Performance.png)

### 5. Executive Insights & Recommendations

[![Executive Insights & Recommendations](screenshots/05-Executive%20Insights%20and%20Recommendations.png)](screenshots/05-Executive%20Insights%20and%20Recommendations.png)

### 6. Loan Portfolio Deep Dive (Drillthrough)

[![Loan Portfolio Deep Dive (Drillthrough)](screenshots/06-Loan%20Portfolio%20Deep%20Dive-Hidden.png)](screenshots/06-Loan%20Portfolio%20Deep%20Dive-Hidden.png)

## Features and skills

- Power BI data modeling with related customer, account, loan, branch, credit risk, transaction, and date tables
- DAX measures for financial KPIs, ratios, and time intelligence
- Interactive slicers and cross-filtering
- Drillthrough from loan portfolio visuals to detailed analysis, with Back navigation
- Executive dashboard design and business storytelling

## Repository files

- `Banking-Intelligence-360.pbix` — Power BI Desktop report
- `DAX-Measures.csv` — exported DAX measure definitions
- `screenshots/` — screenshots of all six report pages

## How to explore

1. Download `Banking-Intelligence-360.pbix`.
2. Open it with **Microsoft Power BI Desktop**.
3. Use the slicers on the main pages to explore segments and periods.
4. On the Executive Banking Overview page, right-click a loan type in the loan portfolio chart and choose **Drill through → Loan Portfolio Deep Dive**.
5. Use the Back button to return.

## Important interpretation notes

- Original loan amount and outstanding loan balance are distinct measures.
- The loan default rate is loan-count-based rather than balance-weighted.
- Interpret deposit and transaction totals according to the underlying synthetic dataset's definitions.
- This is a demonstration project and should not be used to make real financial decisions.

## Built with

Power BI Desktop · DAX · Power Query · Data Modeling · Data Visualization
