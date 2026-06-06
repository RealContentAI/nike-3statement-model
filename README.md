# Nike Inc — 3-Statement Financial Model
**Built by:** Matthieu Coignet  
**Program:** MS Finance candidate, UIC (Aug 2026)  
**Date:** June 2025  

---

## Overview
A fully integrated 3-statement financial model (Income Statement, 
Cash Flow Statement, Balance Sheet) built from scratch on Nike Inc 
(NKE) using public SEC filings. Includes 3 years of historical data 
(FY2023-2025) and 2 years of projections (FY2026E-2027E).

---

## File Structure
| Tab | Content |
|---|---|
| 01-Assumption | Revenue, margin, CapEx, and capital allocation drivers |
| 02-IS | Income Statement with segment breakdown and projections |
| 03-CFS | Cash Flow Statement — Operating, Investing, Financing |
| 04-BS | Balance Sheet with integrity check (must = 0) |
| 05-DASH | KPI Dashboard with 10 metrics and 5 charts |

---

## Data Sources
- Nike Inc. 10-K FY2023, FY2024, FY2025 — SEC EDGAR
- Nike Q4 FY2025 Earnings Call (July 2025)
- Segment data: Note 15 Segment Information (each 10-K)

---

## Key Findings — Historical (FY2023-2025)
- **Revenue** declined -9.8% in FY2025 to $46.3bn — broad-based 
  weakness across all segments
- **Gross Margin** compressed to 42.7% in FY2025 from 44.6% in FY2024 
  driven by higher promotions and DTC mix shift
- **Net Income** fell -43.5% to $3.2bn — worst performance in 10 years
- **FCF** declined -50.6% to $3.3bn — despite CapEx cuts to $430mm
- **Debt/EBITDA** deteriorated to 1.8x from 1.1x — EBITDA compression, 
  not leverage increase

---

## Projection Assumptions (FY2026E-2027E)
- Revenue growth +5%/+7% — recovery driven by product cycle refresh 
  and channel normalization
- Gross Margin recovery to 44.5%/45.0% — input cost normalization 
  and reduced promotional activity
- CapEx 3.5%/3.4% of revenue — asset-light strategy continuation
- Buybacks reduced to $2bn/year — conservative given FCF compression
- Full assumption documentation in 01-Assumption tab

---

## Model Architecture
- All projections driven by 01-Assumption — change one input, 
  entire model updates
- Cross-sheet links: IS → CFS (Net Income) → BS (Cash, Retained Earnings)
- Balance Sheet integrity check = 0 for all 3 historical years
- Color convention: Blue = hardcoded input | Black = formula | 
  Green = cross-sheet link

---

## Skills Demonstrated
- 3-statement model integration from scratch (no template)
- SEC 10-K data extraction and analysis
- Revenue segmentation (6 geographic/brand segments)
- Working capital and FCF analysis
- Scenario-ready assumption architecture
- Financial KPI benchmarking vs sector

---

## Next Steps
- DCF valuation with WACC/CAPM and sensitivity analysis
- Comparable company analysis (Adidas, Puma, Under Armour)
- Monte Carlo scenario analysis on key assumptions
