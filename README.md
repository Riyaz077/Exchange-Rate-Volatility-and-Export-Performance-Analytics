# Impact of Exchange Rate Volatility on Export Performance

### Project Overview

An econometric time-series analysis examining the impact of INR/USD exchange rate fluctuations on India's export performance using annual data from 2000 to 2023. The project investigates exchange rate behaviour, estimates volatility, and evaluates its relationship with export performance using statistical and econometric techniques.

### Project Objectives

- Analyse the relationship between exchange rate movements and export performance.
- Measure INR/USD exchange rate volatility.
- Evaluate the impact of exchange rate fluctuations on India's exports.
- Investigate the predictive relationship between exchange rates and export performance.

### Dataset

The study uses annual time-series data covering **2000–2023**.

| Variable | Description |
|---|---|
| Exchange Rate (INR/USD) | Annual average INR/USD exchange rate. |
| Export Value | India's annual export value, measured in USD. |
| Time Period | 2000–2023 |

The dataset is chronologically organised to support time-series analysis and econometric modelling.

### Methodology

The project follows a structured econometric analysis workflow:

1. **Descriptive Statistics** – Examine the statistical characteristics of the variables.
2. **Trend Analysis** – Analyse exchange rate and export value trends.
3. **ADF Stationarity Test** – Test the stationarity of time-series data.
4. **Correlation Analysis** – Examine the relationship between exchange rates and exports.
5. **ARCH-LM Test** – Identify conditional heteroskedasticity.
6. **GARCH (1,1) Model** – Estimate exchange rate volatility and its persistence.
7. **Regression Analysis** – Evaluate the relationship between exchange rate volatility and export performance.
8. **Granger Causality Test** – Examine predictive relationships between the variables.

### Technologies & Libraries

**Programming Languages & Environment**
- Python
- Google Colab

**Libraries & Frameworks**
- Pandas – Data manipulation and preprocessing.
- NumPy – Numerical computations.
- Matplotlib – Data visualization.
- Seaborn – Statistical visualization.
- Statsmodels – Statistical and econometric modelling.
- ARCH – ARCH and GARCH volatility estimation.

### System Architecture

The project follows a structured econometric analysis workflow, transforming historical exchange rate and export data into meaningful statistical insights.

```text
       Historical Data Collection
                   |
                   v
           Data Preprocessing
                   |
                   v
       Exploratory Data Analysis
                   |
                   v
       Stationarity Analysis (ADF)
                   |
                   v
        Volatility Diagnostics
              (ARCH-LM)
                   |
                   v
          GARCH (1,1) Model
                   |
                   v
          Regression Analysis
                   |
                   v
        Granger Causality Test
                   |
                   v
        Results & Interpretation
                   |
                   v
         Economic Insights
```

The workflow integrates descriptive analysis, stationarity testing, volatility estimation, and econometric modelling to investigate the relationship between exchange rate fluctuations and India's export performance.

### Key Findings

- Exchange rate movements exhibit variations throughout the study period.
- The GARCH (1,1) model captures the persistence of exchange rate volatility.
- Regression analysis provides insights into the relationship between exchange rate volatility and export performance.
- Granger causality analysis examines the predictive relationship between exchange rates and exports.

### Conclusion

This study highlights the relevance of exchange rate fluctuations in understanding India's export performance. By integrating statistical analysis, time-series techniques, and econometric modelling, the project provides insights into the relationship between currency volatility and international trade.

### Author

**Mohamed Riyaz S.**  
Integrated M.Tech – Computer Science and Engineering (Business Analytics)  
Vellore Institute of Technology (VIT), Chennai
