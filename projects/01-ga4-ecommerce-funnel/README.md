# GA4 Ecommerce Funnel Analysis

**Independent portfolio project**

## Business question

Where do shoppers leave the purchase journey?

## Tools

BigQuery SQL, Excel, Power BI and Python/pandas

## Data and scope

Historical, obfuscated Google Merchandise Store sample data, November 2020–January 2021.

## Findings and work completed

The ordered, same-session funnel contains 77,020 product-view sessions, 14,380 add-to-cart sessions, 5,187 checkout sessions and 2,778 completed purchase sessions. Overall completion is 3.61%; 81.33% drop out before add-to-cart. Mobile conversion is 3.77%, desktop 3.50% and tablet 3.59%.

## Recommendations and interpretation

Investigate product-page friction and compare add-to-cart rates by product and traffic source before testing a change. These observations do not establish causes. Tablet results contain only 61 completed sessions.

## Files

- [case-study.pdf](case-study.pdf)
- [funnel-validation.xlsx](funnel-validation.xlsx)
- [ordered-session-funnel.csv](ordered-session-funnel.csv)
- [device-funnel.csv](device-funnel.csv)
- [dashboard.pbix](dashboard.pbix)

## Limitations and reproducibility

The report describes SQL and pandas validation, but the actual SQL files and pandas validation script were not supplied. Add the original code when available; no replacement code has been invented.

Prepared by Shramana Das.
