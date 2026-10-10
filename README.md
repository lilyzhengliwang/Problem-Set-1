# Problem-Set-1
The Cost of Living Brief
Question

A regional employer is deciding whether to raise its starting wage. It believes the official Consumer Price Index (CPI) overstates what its workers actually face. This notebook builds a household price index for a specific household and compares it with the official series.

Approach
Household: a two-earner, mid-to-low-income household that owns a home with a mortgage, drives to work, and has two college-age children.
Index: a base-weighted (Laspeyres) index over eight spending categories, comparing 2019 and 2024 prices (2019 = 100).
Official series: monthly CPI series from FRED (headline CPI plus category proxies), rebased to 2019 = 100.
Checks: a missing-data audit, a common-sample comparison, a seasonally adjusted vs. unadjusted comparison, and a sensitivity test on the household's spending weights.


Notes and limits
Household prices are estimates, not survey data.
October 2025 is missing from most CPI series because the 2025 federal government shutdown prevented BLS from collecting it. It is left as missing, not filled in.
AI was used for the sensitivity analysis (Task 4.1). The full prompt, reply, and my corrections are in the notebook under "AI Transcript."
Data source
Federal Reserve Bank of St. Louis, FRED (https://fred.stlouisfed.org).
