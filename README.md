# NIFTY 50 Portfolio Analysis using Modern Portfolio Theory

## 📌 Project Overview

This project analyzes selected NIFTY 50 stocks using financial analytics and portfolio management techniques. The analysis applies **Modern Portfolio Theory (MPT)** to evaluate portfolio performance under different weighting strategies and examines stock risk, returns, market sensitivity, trading volume, and bond characteristics.

The project also includes **CAPM analysis**, **price-volume relationship analysis**, and a comparison of **Government Securities and Corporate Bonds** based on coupon rates, yields, prices, and maturity.

---

## 🎯 Objective

The objective of this project was to:

- Analyze selected NIFTY 50 stocks using Modern Portfolio Theory (MPT)
- Calculate stock returns and risk measures
- Evaluate portfolio performance using different weighting methods
- Construct a Minimum Variance Portfolio
- Analyze the relationship between stock prices and trading volume
- Estimate the required rate of return using the Capital Asset Pricing Model (CAPM)
- Analyze Government Securities and Corporate Bonds based on price, yield, coupon rate, and maturity characteristics

---

## 📊 Stocks Selected

The following six NIFTY 50 stocks were analyzed:

- Reliance Industries
- Tata Consultancy Services (TCS)
- Infosys (INFY)
- HDFC Bank
- ICICI Bank
- ITC

The analysis was performed using approximately **two years of daily market data**.

---

# 📈 Analysis Performed

## 1️⃣ Return and Risk Analysis

The project calculates and analyzes:

- Daily Returns
- Mean Returns
- Standard Deviation
- Stock Risk
- Beta Values
- Covariance between stock returns

These metrics help evaluate the risk-return characteristics of individual stocks.

---

## 2️⃣ Modern Portfolio Theory (MPT)

Modern Portfolio Theory was applied to construct and evaluate different portfolios.

The following portfolio construction methods were analyzed:

### 🔹 Minimum Variance Portfolio

The Minimum Variance Portfolio focuses on reducing overall portfolio risk by considering the covariance between asset returns.

### 🔹 Value-Weighted Portfolio

Portfolio weights are assigned based on the relative value of the selected stocks.

### 🔹 Price-Weighted Portfolio

Portfolio weights are determined based on stock prices.

---

## 3️⃣ Portfolio Performance Analysis

The portfolios were compared based on risk and return characteristics.

Key performance metrics include:

- Portfolio Return
- Portfolio Risk
- Risk-Adjusted Performance
- Sharpe Ratio

The comparison helps identify the portfolio strategy that provides a better balance between return and risk.

---

## 4️⃣ Covariance Matrix

A covariance matrix was constructed to analyze how the returns of the selected stocks move relative to one another.

Covariance analysis is important in portfolio construction because diversification depends on the relationship between asset returns.

---

## 5️⃣ Price and Volume Analysis

The project analyzes the relationship between:

- Stock Prices
- Trading Volume
- Market Activity
- Price Volatility

The analysis indicated a **moderate positive relationship between trading activity and price volatility**.

---

## 6️⃣ CAPM Analysis

The **Capital Asset Pricing Model (CAPM)** was used to estimate the required rate of return for each selected stock.

The analysis considers:

- Risk-Free Rate
- Market Return
- Beta

### CAPM Formula

Required Return = Risk-Free Rate + Beta × (Market Return − Risk-Free Rate)

The analysis demonstrates how **systematic risk, represented by Beta, influences the required rate of return**.

Stocks with higher Beta values show greater sensitivity to market movements.

---

## 7️⃣ Bond Analysis

The project also analyzes fixed-income securities, including:

- Short-Term Government Security
- Long-Term Government Security
- Corporate Non-Convertible Debenture (NCD)

The following characteristics were compared:

- Coupon Rate
- Yield
- Last Traded Price
- Maturity

### Securities Analyzed

| Security | Coupon Rate | Yield | Maturity |
|---|---:|---:|---:|
| 07.06 GS 2028 | 7.06% | 6.01% | 2028 |
| 06.94 GS 2036 | 6.94% | 6.82% | 2036 |
| Muthoot Finance 8.65 NCD | 8.65% | 8.63% | 2031 |

### Key Bond Insights

- The **Corporate NCD** had the highest coupon rate and yield.
- The **07.06 GS 2028** had the lowest yield among the selected securities.
- The **06.94 GS 2036** had the longest maturity.
- Government Securities generally offered lower yields compared to the Corporate NCD due to lower credit risk.
- The long-term Government Security is generally more sensitive to interest rate changes than the short-term security.

---

# 📊 Key Findings

- Six NIFTY 50 stocks were analyzed using historical market data.
- Modern Portfolio Theory was applied to compare different portfolio construction strategies.
- Minimum Variance, Value-Weighted, and Price-Weighted portfolios were evaluated.
- Risk-return metrics and Sharpe Ratio were used to assess portfolio performance.
- CAPM was used to estimate required returns based on systematic risk.
- Trading activity showed a moderate positive relationship with price volatility.
- Bond analysis demonstrated differences in risk, yield, coupon rates, and maturity between Government Securities and Corporate Bonds.

---

# 🛠️ Tools and Technologies

- Microsoft Excel
- Financial Data Analysis
- Modern Portfolio Theory (MPT)
- Capital Asset Pricing Model (CAPM)
- Portfolio Risk Analysis
- Covariance Analysis
- Sharpe Ratio
- Bond Yield Analysis

---

# 📁 Project Structure

```text
NIFTY50-Portfolio-Analysis-MPT/
│
├── 2025EM1100010_FINANCE.xlsx
│
└── README.md
