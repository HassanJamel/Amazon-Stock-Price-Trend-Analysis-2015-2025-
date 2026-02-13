<p align="center">
  <a href="https://www.kaggle.com/code/hassanjameelahmed/amazon-stock-price-trend-analysis-2015-2025" target="_blank">
    <img src="AMZN Price Trends.png" alt="Amazon Stock" width="500">
  </a>
</p>

# 📈 Amazon (AMZN) Stock Price Analysis: A Decade of Market Performance (2015–2025)

---

## 📊 Project Overview

This project provides a comprehensive analysis of **Amazon.com, Inc. (AMZN)** historical stock price data spanning over a decade — from **January 2, 2015** to **December 31, 2025**. The dataset captures daily trading activity including open, high, low, close prices and trading volume, enabling deep financial analysis, time-series forecasting, and investment strategy research. Amazon, one of the world's most valuable companies, has experienced dramatic growth, stock splits, and market fluctuations throughout this period, making this dataset an invaluable resource for financial analysts, data scientists, and machine learning practitioners.

---

## 🗂️ Dataset Information

| Property              | Details                             |
| --------------------- | ----------------------------------- |
| **File Name**         | `AMZN.csv`                          |
| **File Size**         | ~254 KB                             |
| **Number of Records** | 2,767 trading days                  |
| **Number of Columns** | 6                                   |
| **Date Range**        | January 2, 2015 – December 31, 2025 |
| **Ticker Symbol**     | AMZN                                |
| **Data Frequency**    | Daily (Business days only)          |
| **File Format**       | CSV (Comma-Separated Values)        |

---

## 📋 Column Details

| #   | Column Name | Data Type  | Description                                                                                                                                                                                                              |
| --- | ----------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1   | **Date**    | `datetime` | The trading date in `YYYY-MM-DD` format. Serves as the index/primary key. Only business days (Mon–Fri) are included; weekends and market holidays are excluded.                                                          |
| 2   | **Close**   | `float64`  | The **closing price** of AMZN stock at the end of the trading day (in USD). This is the most commonly used price for analysis and represents the final traded price before the market closes. Adjusted for stock splits. |
| 3   | **High**    | `float64`  | The **highest price** reached by AMZN stock during the trading day (in USD). Useful for identifying intraday volatility, resistance levels, and candlestick charting.                                                    |
| 4   | **Low**     | `float64`  | The **lowest price** reached by AMZN stock during the trading day (in USD). Useful for identifying intraday support levels, volatility measurement, and risk assessment.                                                 |
| 5   | **Open**    | `float64`  | The **opening price** of AMZN stock at the beginning of the trading day (in USD). Reflects pre-market sentiment and overnight news impact.                                                                               |
| 6   | **Volume**  | `int64`    | The **total number of shares** traded during the day. High volume indicates strong interest or significant news events. Volume is a key indicator for confirming price trends and breakouts.                             |

### Column Statistics Summary

| Column     | Min Value | Max Value | Description                           |
| ---------- | --------- | --------- | ------------------------------------- |
| **Close**  | ~$14.35   | ~$232.53  | Price range across the 11-year period |
| **High**   | ~$15.74   | ~$233.00  | Highest intraday prices               |
| **Low**    | ~$14.32   | ~$231.18  | Lowest intraday prices                |
| **Open**   | ~$14.31   | ~$232.91  | Opening prices                        |
| **Volume** | ~11.4M    | ~477.1M   | Daily trading volume range            |

> **Note:** Prices reflect post-split adjusted values. Amazon executed a **20-for-1 stock split on June 6, 2022**, which is reflected in the historically adjusted prices throughout the dataset.

---

## 🏷️ Top 5 Kaggle Tags

| #   | Tag                             | Rationale                                                                                                             |
| --- | ------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| 1   | **`stock-market`**              | Core subject matter — the dataset contains stock market trading data for a publicly listed company.                   |
| 2   | **`time-series-analysis`**      | The dataset is inherently a time series with daily frequency, ideal for temporal pattern recognition and forecasting. |
| 3   | **`finance`**                   | Falls under the financial domain, relevant to investment analysis, portfolio management, and economic research.       |
| 4   | **`exploratory-data-analysis`** | The dataset is well-suited for EDA including trend analysis, seasonality detection, and statistical summaries.        |
| 5   | **`regression`**                | Applicable for building predictive models (e.g., LSTM, ARIMA, XGBoost) to forecast future stock prices.               |

---

## 🔍 SEO-Optimized Project Name & Description

### Project Name

**Amazon (AMZN) Stock Price Dataset: 11-Year Historical Analysis (2015–2025)**

### SEO Description

> Explore 11 years of Amazon (AMZN) daily stock market data from 2015 to 2025, including Open, High, Low, Close prices and trading Volume. This comprehensive dataset covers 2,767 trading days of one of the world's most valuable tech companies, providing a rich foundation for time-series forecasting, technical analysis, machine learning modeling, and investment strategy research. Ideal for EDA, LSTM/ARIMA price prediction, volatility analysis, and financial data science projects on Kaggle.

### SEO Keywords

`Amazon stock data`, `AMZN historical prices`, `stock market dataset`, `time series forecasting`, `financial analysis`, `stock price prediction`, `AMZN 2015-2025`, `daily stock prices`, `trading volume analysis`, `machine learning finance`, `Kaggle stock dataset`

---

## 🌍 Coverage

### Data Coverage Summary

| Dimension               | Details                                                                  |
| ----------------------- | ------------------------------------------------------------------------ |
| **Temporal Coverage**   | 11 years (2015–2025)                                                     |
| **Trading Days**        | 2,767 business days                                                      |
| **Market**              | NASDAQ (National Association of Securities Dealers Automated Quotations) |
| **Sector**              | Technology / Consumer Discretionary / E-Commerce                         |
| **Company**             | Amazon.com, Inc.                                                         |
| **Ticker**              | AMZN                                                                     |
| **Geographical Market** | United States (NYSE/NASDAQ)                                              |

### Key Events Covered in This Dataset

| Period              | Event                                       | Impact                                                          |
| ------------------- | ------------------------------------------- | --------------------------------------------------------------- |
| **2015–2019**       | Rapid e-commerce growth, AWS dominance      | Consistent upward price trajectory                              |
| **2020 (COVID-19)** | Pandemic-driven e-commerce surge            | Sharp price increase due to accelerated online shopping         |
| **2021**            | Post-pandemic boom, peak valuations         | Historic highs before market correction                         |
| **2022 (June 6)**   | **20-for-1 Stock Split**                    | Prices adjusted retroactively; increased retail investor access |
| **2022–2023**       | Tech sector correction, inflation fears     | Significant price decline from highs                            |
| **2024–2025**       | AI-driven growth, cloud computing expansion | Recovery and new growth phase                                   |

---

## 📅 Temporal and Geospatial Scope

### Temporal Scope

| Property       | Value                                                                   |
| -------------- | ----------------------------------------------------------------------- |
| **Start Date** | 01/02/2015                                                              |
| **End Date**   | 12/31/2025                                                              |
| **Duration**   | ~11 years                                                               |
| **Frequency**  | Daily (Business days only — excludes weekends and U.S. market holidays) |
| **Time Zone**  | Eastern Time (ET) — NYSE/NASDAQ trading hours                           |

### Geospatial Scope

| Property             | Value                                                                                    |
| -------------------- | ---------------------------------------------------------------------------------------- |
| **Country**          | United States of America 🇺🇸                                                              |
| **City**             | New York, NY (NASDAQ Exchange)                                                           |
| **Market Exchange**  | NASDAQ                                                                                   |
| **Headquarters**     | Seattle, WA → Arlington, VA (Amazon relocated HQ in 2023)                                |
| **Global Relevance** | Amazon operates in 200+ countries; stock performance reflects global economic conditions |

---

## 📜 Provenance (Data Source & Transformations)

### Source of the Data

The dataset was sourced from **Yahoo Finance (yfinance)**, one of the most widely used and trusted platforms for retrieving historical financial market data. Yahoo Finance aggregates data from major stock exchanges and financial data providers.

### Data Pipeline

```
Yahoo Finance API (yfinance) → Raw Data Extraction → CSV Export → AMZN.csv
```

### Transformations Applied

| Step                          | Description                                                                                                                                          |
| ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1. **Data Extraction**        | Historical daily OHLCV data was retrieved using the `yfinance` Python library for ticker symbol `AMZN`.                                              |
| 2. **Split Adjustment**       | All historical prices are adjusted for Amazon's **20-for-1 stock split** (June 6, 2022). Pre-split prices are divided by 20 to maintain consistency. |
| 3. **Column Standardization** | Columns are labeled as `Price`, `Close`, `High`, `Low`, `Open`, `Volume` with the ticker name `AMZN` in the header row.                              |
| 4. **Date Indexing**          | The `Date` column serves as the primary index in `YYYY-MM-DD` format.                                                                                |
| 5. **Missing Data Handling**  | Non-trading days (weekends, holidays) are naturally excluded. No imputation was performed.                                                           |
| 6. **Export**                 | Data was exported to CSV format for portability and ease of use.                                                                                     |

### Data Reliability

- **Source Trustworthiness**: Yahoo Finance is a widely recognized and trusted financial data provider used globally by analysts, researchers, and developers.
- **Data Accuracy**: Prices are directly sourced from NASDAQ exchange records.
- **Reproducibility**: The dataset can be independently reproduced using the `yfinance` Python library.

---

## 🔬 Dataset Collection Methodology

### Method: Automated API-Based Extraction

| Aspect                | Details                                 |
| --------------------- | --------------------------------------- |
| **Tool**              | `yfinance` Python library (open-source) |
| **API**               | Yahoo Finance API                       |
| **Extraction Method** | Programmatic download using Python      |
| **Ticker**            | `AMZN`                                  |
| **Period**            | January 1, 2015 – December 31, 2025     |
| **Interval**          | `1d` (Daily)                            |
| **Data Fields**       | Open, High, Low, Close, Volume          |

### Reproducibility Code

```python
import yfinance as yf

# Download Amazon stock data
amzn = yf.download("AMZN", start="2015-01-01", end="2025-12-31", interval="1d")

# Save to CSV
amzn.to_csv("AMZN.csv")
```

### Quality Assurance

- ✅ No synthetic or fabricated data points
- ✅ All values represent actual market trades on NASDAQ
- ✅ Prices are split-adjusted for historical consistency
- ✅ Volume figures represent actual shares traded
- ✅ Date continuity verified (business days only, no gaps beyond holidays)

---

## ⚠️ Biggest Problems & Challenges

### 1. Stock Split Adjustment Complexity

Amazon's **20-for-1 stock split on June 6, 2022** means historical prices must be adjusted retroactively. Pre-split prices appear significantly lower (e.g., ~$15 in 2015 vs. ~$2,500 unadjusted). If not properly accounted for, this can lead to misleading analysis and incorrect percentage returns.

### 2. Non-Stationarity of Time Series

Stock prices are inherently **non-stationary** — the mean and variance change over time. This violates assumptions of many statistical models (e.g., linear regression, ARIMA without differencing). Transformation techniques like log returns, differencing, or normalization are necessary.

### 3. External Event Sensitivity

Major events not captured in the dataset significantly influence prices:

- **COVID-19 pandemic (2020)**: Caused extreme volatility
- **Federal Reserve interest rate changes**: Impacted tech valuations
- **Antitrust investigations**: Affected investor sentiment
- **Earnings surprise events**: Caused intraday spikes not fully reflected in daily OHLCV

### 4. Missing Contextual Data

The dataset only includes price and volume. It lacks:

- Fundamental data (earnings, revenue, P/E ratio)
- Sentiment data (news, social media)
- Macroeconomic indicators (GDP, inflation, interest rates)
- Sector-level comparisons

### 5. Survivorship Bias

As one of the most successful companies in history, analyzing only Amazon's data introduces **survivorship bias** — the dataset does not account for companies that failed or underperformed during the same period.

### 6. Look-Ahead Bias Risk

When building predictive models, there's a risk of **look-ahead bias** — inadvertently using future data to predict past events. Proper train/test splits with temporal ordering are critical.

### 7. High Volatility Periods

Certain periods (e.g., early 2020, late 2022) exhibit extreme volatility that can skew statistical measures and challenge model robustness. Outlier detection and robust modeling techniques are essential.

### 8. Volume Interpretation Challenges

Raw volume numbers can be misleading without context:

- Higher volumes may indicate institutional activity or index rebalancing
- Stock splits artificially change share count, affecting volume comparisons across periods

---

## 🔗 Data Source

### Primary Source

| Property              | Details                                                                                        |
| --------------------- | ---------------------------------------------------------------------------------------------- |
| **Source**            | Yahoo Finance                                                                                  |
| **URL**               | [https://finance.yahoo.com/quote/AMZN/history/](https://finance.yahoo.com/quote/AMZN/history/) |
| **Python Library**    | `yfinance` — [https://pypi.org/project/yfinance/](https://pypi.org/project/yfinance/)          |
| **GitHub Repository** | [https://github.com/ranaroussi/yfinance](https://github.com/ranaroussi/yfinance)               |

### Alternative Verification Sources

| Source                | URL                                                                                                                            |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **NASDAQ Official**   | [https://www.nasdaq.com/market-activity/stocks/amzn/historical](https://www.nasdaq.com/market-activity/stocks/amzn/historical) |
| **Google Finance**    | [https://www.google.com/finance/quote/AMZN:NASDAQ](https://www.google.com/finance/quote/AMZN:NASDAQ)                           |
| **Alpha Vantage API** | [https://www.alphavantage.co/](https://www.alphavantage.co/)                                                                   |

---

## 📖 How the Problem Developed: Step-by-Step

### Step 1: The Rise of E-Commerce (2015–2017)

Amazon began this period as a rapidly growing e-commerce company with an emerging cloud computing division (AWS). Stock prices ranged from ~$15 to ~$60 (split-adjusted). The core challenge was **understanding the dual business model** — retail (low margins) vs. AWS (high margins). Analysts struggled to value the company using traditional metrics, as Amazon consistently reinvested profits into growth.

### Step 2: Market Dominance & AWS Explosion (2017–2019)

AWS became the world's leading cloud platform, driving profitability. Amazon expanded into physical retail (Whole Foods acquisition, 2017), advertising, and healthcare. Stock price surged past $90 (split-adjusted). The challenge evolved: **how to forecast a company that continuously disrupted new industries.** Traditional valuation models were inadequate for a company with such diverse revenue streams.

### Step 3: The COVID-19 Catalyst (2020)

The pandemic accelerated digital transformation worldwide. Amazon's e-commerce and cloud services experienced unprecedented demand. Stock price nearly doubled within the year ($80 → $160+ split-adjusted). **The challenge**: distinguishing between temporary pandemic-driven demand and permanent behavioral shifts. Models trained on pre-pandemic data became unreliable.

### Step 4: Peak Valuation & Market Euphoria (2021)

Amazon reached peak valuations driven by:

- Record e-commerce volume
- AWS growth acceleration
- Speculative market exuberance
- Low interest rates fueling tech stocks

The stock reached over $180 (split-adjusted). **Challenge**: Identifying the sustainability of elevated valuations and the growing disconnect between price and fundamentals.

### Step 5: The 20-for-1 Stock Split (June 2022)

Amazon executed a 20-for-1 stock split to make shares more accessible to retail investors. This created a **data engineering challenge**: all historical data needed retroactive adjustment. Models needed to handle the discontinuity, and analysis spanning the split date required careful price normalization.

### Step 6: Tech Correction & Inflation Crisis (2022–2023)

Rising interest rates, inflation, and recession fears triggered a broad tech selloff. Amazon's stock declined significantly (from ~$170 to ~$85). **Key challenges**:

- Adapting forecasting models to a new macroeconomic regime
- Separating Amazon-specific performance from broader market trends
- Accounting for layoffs (18,000+ employees) and cost-cutting measures

### Step 7: AI-Driven Recovery (2024–2025)

Amazon's stock recovered strongly, driven by:

- AWS integration of generative AI services
- Amazon Bedrock and AI infrastructure investments
- Improved operational efficiency post-restructuring
- Strong advertising revenue growth

Prices reached ~$230 by end of 2025. **Current challenge**: Forecasting the impact of AI adoption on Amazon's long-term valuation and differentiating between hype-driven and fundamentals-driven price appreciation.

### Summary of Problem Evolution

```
2015 ──→ Valuation Puzzle (E-commerce vs. AWS)
  │
2017 ──→ Multi-Industry Disruption Modeling
  │
2020 ──→ Pandemic Demand Shock & Regime Change
  │
2021 ──→ Bubble Detection & Sustainability Analysis
  │
2022 ──→ Stock Split Data Engineering + Tech Correction
  │
2023 ──→ Macroeconomic Regime Adaptation
  │
2025 ──→ AI-Driven Growth Forecasting
```

---

## 📝 Conclusion

The **Amazon (AMZN) Stock Price Dataset (2015–2025)** is a rich, real-world financial time-series dataset that captures one of the most transformative periods in modern corporate history. With 2,767 trading days of clean, split-adjusted OHLCV data, it serves as an excellent foundation for exploratory data analysis, statistical modeling, machine learning forecasting, and financial research. The dataset's challenges — non-stationarity, regime changes, external event sensitivity, and split-adjustment complexity — make it particularly valuable for developing robust analytical and predictive methodologies in computational finance.

---

_Dataset prepared for Kaggle publication. Last updated: February 2026._
