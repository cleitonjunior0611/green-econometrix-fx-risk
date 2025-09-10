# 📊 Environmental Degradation & Exchange Rate Volatility

An econometric study analyzing the impact of environmental factors and interest rates on currency stability using advanced regression techniques.

![R](https://img.shields.io/badge/R-4.x-blue.svg)
![Econometrics](https://img.shields.io/badge/Econometrics-Panel%20Data-green.svg)
![Analysis](https://img.shields.io/badge/Analysis-Quantile%20Regression-yellow.svg)
![Finance](https://img.shields.io/badge/Finance-Risk%20Analysis-red.svg)
![Environment](https://img.shields.io/badge/Environmental-Economics-brightgreen.svg)

## 🧮 Methodology

### Data & Descriptive Analysis
- **Panel data**: 10 countries (2000-2019)
- **Variables**: 
  - `exchange_rate_change` (dependent variable)
  - `loss_of_nature` (environmental degradation index)
  - `interest_rate` (monetary policy indicator)
- **Tools**: Histograms, summary statistics, time-series visualization

### Regression Techniques
- **Ordinary Least Squares (OLS)**: Baseline mean-effect estimation
- **Quantile Regression**: Analysis across distribution quantiles (τ = 0.1, 0.25, 0.5, 0.75, 0.9)
- **Implementation**: `lm()` and `rq()` functions in R with bootstrapped standard errors

## 📈 Key Insights

Environmental degradation shows significantly stronger effects during currency crises (lower quantiles), diminishing during stable periods. Interest rates demonstrate more consistent effects across distribution quantiles.

## 🛠️ Technical Stack

![tidyverse](https://img.shields.io/badge/tidyverse-Data%20Wrangling-blue.svg)
![quantreg](https://img.shields.io/badge/quantreg-Quantile%20Analysis-green.svg)
![ggplot2](https://img.shields.io/badge/ggplot2-Visualization-orange.svg)
![Econometrics](https://img.shields.io/badge/Methods-Panel%20Analysis-lightgrey.svg)
