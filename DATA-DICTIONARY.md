# Data Dictionary: `single-bid-contracts-2024-2026.csv`

Column definitions for the open dataset published by **[Tenderline.uk](https://tenderline.uk/research/single-bid-contracts-2024-2026)** (Vivid Analytics Ltd, Companies House `#16555468`).

## Combined CSV Columns (`single-bid-contracts-2024-2026.csv`)

| Column | Type | Description |
| --- | --- | --- |
| `table` | string | Cut identifier: `contracts`, `sector_cpv_division`, `delivery_region_itl1`, `buyer_type`, `lot_value_band`, `sector_cpv_division_final_stage`, `delivery_region_itl1_final_stage`, `frameworks_dps`, or `other_regimes`. |
| `regime` | string | UK statutory procurement regime: `pa2023` (Procurement Act 2023), `pcr2015` (Public Contracts Regulations 2015 & Scottish equivalent), `ucr2016` (Utilities), or `dspcr2011` (Defence & Security). |
| `key` | string | Group code within the cut (2-digit Primary CPV division, ITL1 region code `UKC`-`UKN`, buyer type slug, value band slug, or `headline`/`repeat_placements`). |
| `bid_count_measure` | string | `received` = total bids received (published under both PA 2023 and PCR 2015); `final` = tenders evaluated at the final stage (PA 2023 notices only). |
| `lots` | integer | Number of completed competitive contract lots with a valid recorded bid count in this cut. |
| `procedures` | integer | Number of distinct Find a Tender procedures (`ocid`) containing those lots. |
| `single_bid_lots` | integer | Number of measured lots where exactly 1 bid/tender was recorded. |
| `single_bid_pct` | float | Observed single-bid percentage (`100 * single_bid_lots / lots`). |
| `ci95_low` | float | Lower bound of the 95% confidence interval for `single_bid_pct`. |
| `ci95_high` | float | Upper bound of the 95% confidence interval for `single_bid_pct`. |
| `median_bids` | float | Median number of bids recorded across the measured lots in this cut. |

## Split CSV Tables (`tables/*.csv`)

Each table in `tables/` mirrors the schema above and adds human-readable `regime_label` and `label` columns for direct import into spreadsheet or BI tools.

## Source & Licence

Derived from official UK Find a Tender Service (FTS) OCDS releases licensed under the Open Government Licence v3.0. Analytical tables and documentation are licensed under CC BY 4.0 by Vivid Analytics Ltd / Tenderline.uk.
