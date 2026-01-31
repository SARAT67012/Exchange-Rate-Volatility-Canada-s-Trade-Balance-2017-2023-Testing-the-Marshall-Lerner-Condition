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

<img width="549" height="403" alt="Image" src="https://github.com/user-attachments/assets/c6ec8f4b-9827-4090-bd9c-29b325f31087" />


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

<img width="587" height="370" alt="Image" src="https://github.com/user-attachments/assets/79e354b9-0ab2-4d6d-8c51-01288b4fa95f" />

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

<img width="460" height="386" alt="Image" src="https://github.com/user-attachments/assets/2a6e1787-6aad-4676-9a8a-f6601396ca87" />
*Figure: Log–log relationship between exports and exchange rate.*

### Import Response to Exchange Rate

<img width="423" height="356" alt="Image" src="https://github.com/user-attachments/assets/fa30218c-1899-47f5-ba9c-1d0f7e8377f9" />
*Figure: Log–log relationship between imports and exchange rate.*


### Why Log–Log Regression?

Logarithmic transformation provides three advantages:

- Coefficients are directly interpretable as elasticities
- Percentage-based interpretation aligns with business and policy decision-making
- Log transformation reduces scale effects and improves comparability over time

<img width="777" height="530" alt="Image" src="https://github.com/user-attachments/assets/7e90b24a-b5d2-444d-af2c-f0fefb225cc9" />

### Decision Interpretation

- A positive export elasticity would imply that currency depreciation improves export competitiveness
- A negative import elasticity would imply reduced import demand due to higher domestic prices
- If |β₁| + |β₂| > 1, exchange rate depreciation can improve the trade balance
- If not, structural factors dominate currency effects

