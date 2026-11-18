# Single-Bid Contracts in UK Public Procurement (2024-2026): Open Dataset & Methodology

Open dataset and lot-level statistical tables for **[Single-bid contracts in UK public procurement, October 2024 to September 2026](https://tenderline.uk/research/single-bid-contracts-2024-2026)**, published by **[Tenderline.uk](https://tenderline.uk/)** and operated by **[Vivid Analytics Ltd](https://vividanalytics.uk/)** (UK Companies House `#16555468`).

## Quick Links

- **Interactive study & charts:** https://tenderline.uk/research/single-bid-contracts-2024-2026
- **Live CSV endpoint on Tenderline.uk:** https://tenderline.uk/research/single-bid-contracts-2024-2026/data.csv
- **Plain Markdown edition (.md):** https://tenderline.uk/research/single-bid-contracts-2024-2026.md
- **Companion study (UK Procurement Portals Ranking 2026):** https://tenderline.uk/research/uk-procurement-platforms-ranking-2026 (Dataset repo: https://github.com/vividanalyticsuk/uk-procurement-portals-2026)
- **Tenderline.uk platform & methodology:** https://tenderline.uk/ | https://tenderline.uk/methodology
- **Corporate operator profile:** https://vividanalytics.uk/tenderline

---

## Scope & Headline Findings

- **Source feed:** Official UK Find a Tender Service (FTS) Open Contracting Data Standard (OCDS) releases under the Open Government Licence v3.0.
- **Observation window:** 1 October 2024 to 1 October 2026 (snapshot frozen 14 October 2026; latest catalogue release `2026-10-10 10:24:06+00`).
- **Commercial unit:** Individual competitive contract **lots** (multi-lot procedures are never collapsed into a single row; procedure-clustered confidence intervals account for within-procedure correlation).
- **Headline single-bid rates (non-repeat competitive lots):**
  - **Procurement Act 2023 (bids received):** **12.5%** (95% CI 11.8% to 13.2%) across **9,256 lots** (7,104 procedures; 1,155 single-bid lots; median 4 bids).
  - **Procurement Act 2023 (tenders at final evaluation stage):** **19.9%** (95% CI 19.1% to 20.8%) across **9,275 lots** (7,105 procedures; 1,849 single-tender lots; median 3 bids).
  - **Stage attrition under PA 2023:** Across 9,247 lots reporting both received and final-stage counts, **2,538 lots** saw fewer tenders at the final stage than received, and **686 multi-bid lots** narrowed down to a single bidder by the final stage.
  - **Public Contracts Regulations 2015 & Scottish equivalent (bids received):** **16.5%** (95% CI 15.7% to 17.3%) across **8,271 lots** (6,070 procedures; 1,367 single-bid lots; median 4 bids).

---

## Procurement Act 2023: Single-Bid Share by Primary CPV Sector (Bids Received)

| Primary CPV | Sector | Lots Measured | Procedures | Single-Bid Lots | Single-Bid % | 95% CI | Median Bids |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `66` | Financial and insurance services | 359 | 143 | 88 | **24.5%** | 20.3%–29.2% | 3 |
| `34` | Transport equipment | 164 | 137 | 37 | **22.6%** | 16.8%–29.5% | 3 |
| `98` | Other community, social and personal services | 199 | 162 | 44 | **22.1%** | 16.9%–28.4% | 3 |
| `60` | Transport services | 316 | 118 | 66 | **20.9%** | 16.8%–25.7% | 3 |
| `80` | Education and training services | 419 | 327 | 73 | **17.4%** | 14.1%–21.3% | 4 |
| `85` | Health and social work services | 1,124 | 867 | 162 | **14.4%** | 12.5%–16.6% | 4 |
| `50` | Repair and maintenance services | 521 | 403 | 72 | **13.8%** | 11.1%–17.0% | 4 |
| `90` | Sewage, refuse, cleaning and environmental | 757 | 544 | 104 | **13.7%** | 11.5%–16.4% | 4 |
| `73` | Research and development services | 160 | 126 | 17 | **10.6%** | 6.7%–16.4% | 4 |
| `55` | Hotel, restaurant and catering services | 265 | 199 | 25 | **9.4%** | 6.5%–13.6% | 4 |
| `77` | Agricultural, forestry and horticultural services | 195 | 108 | 18 | **9.2%** | 5.9%–14.1% | 5 |
| `79` | Business services: law, marketing, consulting | 925 | 776 | 81 | **8.8%** | 7.1%–10.8% | 5 |
| `48` | Software packages and information systems | 182 | 167 | 15 | **8.2%** | 5.1%–13.2% | 5 |
| `71` | Architectural, engineering and inspection | 571 | 467 | 42 | **7.4%** | 5.5%–9.8% | 6 |
| `72` | IT services: consulting, software and support | 329 | 313 | 24 | **7.3%** | 5.0%–10.6% | 5 |
| `45` | Construction work | 1,190 | 984 | 73 | **6.1%** | 4.9%–7.6% | 6 |

---

## Procurement Act 2023: Single-Bid Share by UK ITL1 Region (Bids Received)

| Region Code | Region | Lots Measured | Procedures | Single-Bid Lots | Single-Bid % | 95% CI | Median Bids |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `UKN` | Northern Ireland | 687 | 449 | 196 | **28.5%** | 25.3%–32.0% | 2 |
| `UKL` | Wales | 774 | 612 | 115 | **14.9%** | 12.5%–17.5% | 3 |
| `UKE` | Yorkshire and The Humber | 1,093 | 887 | 120 | **11.0%** | 9.3%–13.0% | 5 |
| `UKJ` | South East | 1,402 | 1,151 | 152 | **10.8%** | 9.3%–12.6% | 5 |
| `UKF` | East Midlands | 1,093 | 915 | 116 | **10.6%** | 8.9%–12.6% | 5 |
| `UKI` | London | 1,331 | 1,074 | 135 | **10.1%** | 8.6%–11.9% | 5 |
| `UKC` | North East | 1,020 | 756 | 101 | **9.9%** | 8.2%–11.9% | 4 |
| `UKK` | South West | 1,165 | 957 | 113 | **9.7%** | 8.1%–11.5% | 5 |
| `UKH` | East of England | 1,185 | 981 | 114 | **9.6%** | 8.1%–11.4% | 5 |
| `UKG` | West Midlands | 1,082 | 870 | 102 | **9.4%** | 7.8%–11.3% | 5 |
| `UKD` | North West | 1,288 | 1,082 | 116 | **9.0%** | 7.6%–10.7% | 5 |

---

## Procurement Act 2023: Single-Bid Share by Contracting Authority Type (Bids Received)

| Buyer Type | Lots Measured | Procedures | Single-Bid Lots | Single-Bid % | 95% CI | Median Bids |
| --- | --- | --- | --- | --- | --- | --- |
| Central government | 1,870 | 1,437 | 313 | **16.7%** | 15.1%–18.5% | 3 |
| Local authority | 3,985 | 3,177 | 559 | **14.0%** | 13.0%–15.1% | 4 |
| Police & fire | 229 | 174 | 30 | **13.1%** | 9.3%–18.1% | 3 |
| other_public | 1,891 | 1,272 | 156 | **8.2%** | 7.1%–9.6% | 5 |
| Charity / third sector | 151 | 130 | 12 | **7.9%** | 4.6%–13.4% | 6 |
| Housing association | 213 | 122 | 15 | **7.0%** | 4.3%–11.3% | 4 |
| Education | 763 | 656 | 52 | **6.8%** | 5.2%–8.8% | 5 |

---

## Repository Contents

- [`single-bid-contracts-2024-2026.csv`](single-bid-contracts-2024-2026.csv): Canonical combined CSV covering every aggregate cut published on the study page (headline regimes, CPV divisions, ITL1 regions, buyer types, lot value bands, final-stage cuts, frameworks/DPS, and utilities/defence regimes).
- [`tables/`](tables/): Five clean standalone CSV tables with human-readable labels (`headline_regimes.csv`, `sectors_cpv.csv`, `regions_uk.csv`, `buyer_types.csv`, `value_bands.csv`).
- [`single-bid-contracts-2024-2026.json`](single-bid-contracts-2024-2026.json): Frozen study JSON snapshot including coverage and attrition totals.
- [`DATA-DICTIONARY.md`](DATA-DICTIONARY.md): Column-by-column definitions and regime/measure notes.
- [`CITATION.cff`](CITATION.cff) & [`LICENSE`](LICENSE): Attribution metadata and dual OGL v3.0 / CC BY 4.0 licence.

## Citation & Attribution

> Tenderline.uk (Vivid Analytics Ltd). (2026). *Single-bid contracts in UK public procurement, October 2024 to September 2026*. https://tenderline.uk/research/single-bid-contracts-2024-2026
