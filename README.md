# Exchange Rate Volatility & Trade Balance  
### An Econometric Test of the Marshall–Lerner Condition (Canada, 2017–2023)

## Executive Summary

This project empirically examines whether depreciation of the Canadian Dollar (CAD)
improves Canada’s trade balance, testing the Marshall–Lerner condition using
econometric methods.

Using annual data (2017–2023), we estimate export and import elasticities via
log–log regression models. Results indicate that the Marshall–Lerner condition
does not hold for Canada during this period, largely due to commodity dependence,
US supply-chain integration, and pandemic-related shocks.


## Why This Matters

Can central banks use currency depreciation to improve trade balance?

This question is critical for:
- Central banks
- Trade policy makers
- International firms managing FX exposure
## Exchange Rate Overview

![CAD/USD Exchange Rate Trend (2017–2023)](Pic/Screenshot 2026-02-01 004805.png))

*Figure: Annual average CAD/USD exchange rate. Higher values indicate CAD depreciation.*


## Economic Theory

According to the Marshall–Lerner condition, a currency depreciation improves
the trade balance if the sum of export and import demand elasticities exceeds one.

## Data

- Exchange Rate: Bank of Canada
- Exports & Imports: Statistics Canada
- Period: 2017–2023 (annual)

All variables are transformed into natural logarithms.
## Trade Flow Overview

![Canada Exports and Imports (2017–2023)](figures/exports_imports_trend.png)

*Figure: Trends in Canadian exports and imports during the study period.*



## Econometric Methodology

The objective of this analysis is to quantify how movements in the Canadian Dollar
(CAD) affect Canada’s export and import behavior, and to evaluate whether exchange
rate depreciation can be an effective policy or business lever for improving the
trade balance.


### Model Specification

To estimate trade responsiveness, we use two log–log regression models:

ln(Exportsₜ) = α + β₁ ln(Exchange Rateₜ) + εₜ  
ln(Importsₜ) = α + β₂ ln(Exchange Rateₜ) + εₜ  

Where:
- Exchange Rate is measured as CAD per USD (higher values indicate CAD depreciation)
- β₁ represents export elasticity with respect to the exchange rate
- β₂ represents import elasticity with respect to the exchange rate

- ### Export Response to Exchange Rate

![ln(Exports) vs ln(Exchange Rate)](figures/ln_exports_vs_ln_er.png)

*Figure: Log–log relationship between exports and exchange rate.*

### Import Response to Exchange Rate

![ln(Imports) vs ln(Exchange Rate)](figures/ln_imports_vs_ln_er.png)

*Figure: Log–log relationship between imports and exchange rate.*


### Why Log–Log Regression?

Logarithmic transformation provides three advantages:

- Coefficients are directly interpretable as elasticities
- Percentage-based interpretation aligns with business and policy decision-making
- Log transformation reduces scale effects and improves comparability over time

### Decision Interpretation

- A positive export elasticity would imply that currency depreciation improves export competitiveness
- A negative import elasticity would imply reduced import demand due to higher domestic prices
- If |β₁| + |β₂| > 1, exchange rate depreciation can improve the trade balance
- If not, structural factors dominate currency effects

