# Larsen & Toubro Ltd. — Financial Analysis & Equity Valuation

## Project Overview

A comprehensive Excel-based financial analysis and equity valuation of **Larsen & Toubro Ltd. (L&T)**.

The project combines historical financial analysis, profitability analysis, capital structure and WACC estimation, beta analysis, discounted cash flow valuation, comparable-company valuation, football field analysis, and financial risk assessment.

The objective is to evaluate L&T's financial performance and estimate its potential value per share using multiple valuation methodologies.

---

## Project Screenshots

### WACC
![WACC Analysis](Screenshots/WACC.jpg)

### DCF Valuation
![DCF Valuation](Screenshots/DCF-Valuation-Detail.jpg)

### Relative Valuation
![Relative Valuation](Screenshots/Relative-Valuation.jpg)

### Football Field
![Football Field Analysis](Screenshots/Football-Field.jpg)

### Altman Z-Score
![Altman Z-Score](Screenshots/Altman-Z-Score.jpg)

---

## Key Highlights

| Area | Key Output |
|---|---:|
| Current Market Price | ₹3,785.60 |
| DCF Base-Case Value/Share | ₹3,203.24 |
| DCF Premium/(Discount) | ~18% premium |
| Relative Valuation — EV/Revenue | ₹4,277.70 |
| Relative Valuation — EV/EBITDA | ₹3,996.30 |
| Relative Valuation — P/E | ₹4,543.50 |
| WACC | 12.20% |
| Cost of Equity | 13.36% |
| After-Tax Cost of Debt | 5.70% |
| Forecast Growth | 20.75% |
| Terminal Growth | 4.50% |
| Latest Altman Z-Score | 3.54 — Strong |

---

## Valuation Summary

### 1. Discounted Cash Flow (DCF)

The DCF model uses a Free Cash Flow to Firm (FCFF) approach.

**Base-case assumptions:**

- Forecast growth: **20.75%**
- WACC: **12.20%**
- Terminal growth: **4.50%**
- Tax rate: **25%**

The resulting enterprise value is approximately **₹5.22 lakh crore**, leading to an estimated equity value per share of **₹3,203.24**.

Against the model's market price of **₹3,785.60**, the DCF indicates a premium of approximately **18%**, suggesting that the stock is **overvalued under the base-case DCF assumptions**.

### 2. Relative Valuation

Comparable-company valuation was performed using:

- EV/Revenue
- EV/EBITDA
- P/E

The implied values per share are:

- **EV/Revenue:** ₹4,277.70
- **EV/EBITDA:** ₹3,996.30
- **P/E:** ₹4,543.50

All three implied values are above the reference market price of ₹3,785.60, resulting in an **undervalued** indication under the selected comparable-company multiples.

### 3. Football Field Analysis

The football field combines the DCF scenarios, relative valuation range, and 52-week market range to provide a visual comparison of valuation ranges.

Key ranges include:

- Relative Valuation: **₹3,996.35–₹4,543.49**
- DCF Bear: **₹2,312.05–₹3,501.48**
- DCF Base: **₹2,719.30–₹4,633.72**
- DCF Bull: **₹2,774.60–₹4,809.85**
- 52-Week Range: **₹3,288–₹4,440**

The divergence between DCF and relative valuation demonstrates how valuation conclusions can change depending on assumptions and methodology.

---

## Financial Analysis

The model includes historical analysis of:

- Revenue
- EBITDA
- Net income
- EPS
- Margins
- Working capital
- Balance sheet items
- Cash flows
- Return on Equity (ROE)
- Return on Assets (ROA)
- DuPont analysis
- Return on Invested Capital (ROIC)

Latest model figures include approximately:

- Revenue: **₹2,85,874 crore**
- EBITDA: **₹37,321 crore**
- Net Income: **₹16,084 crore**
- ROE: **~15.54%**

---

## WACC & Beta Analysis

The WACC model incorporates:

- CAPM
- Risk-free rate
- Equity risk premium
- Levered beta
- Unlevered beta
- Cost of debt
- Tax rate
- Target capital structure

Key outputs:

- Cost of Equity: **13.36%**
- After-Tax Cost of Debt: **5.70%**
- Equity Weight: **84.90%**
- Debt Weight: **15.10%**
- WACC: **12.20%**

The comparable-company analysis also includes five-year monthly beta information and unlevered beta calculations.

---

## Altman Z-Score

The project tracks L&T's Altman Z-Score over multiple years.

| Year | Z-Score | Classification |
|---|---:|---|
| 2020 | 1.77 | Distressed |
| 2021 | 2.03 | Grey Zone |
| 2022 | 2.39 | Grey Zone |
| 2023 | 2.77 | Grey Zone |
| 2024 | 3.98 | Strong |
| 2025 | 3.56 | Strong |
| 2026 | 3.54 | Strong |

The trend indicates a substantial improvement in the model's financial-stability assessment from the earlier years to the latest periods.

---

## Risk Analysis

The workbook also incorporates:

- Historical Value at Risk (VaR)
- Monte Carlo simulation
- Altman Z-Score
- Sensitivity analysis

These components complement the valuation work by examining downside risk and financial stability alongside intrinsic value.

---

## Methodology

The project follows a multi-stage equity-analysis framework:

1. Collect historical financial and market data.
2. Analyse financial performance and profitability.
3. Estimate beta and cost of equity.
4. Calculate WACC.
5. Forecast operating performance and FCFF.
6. Perform DCF valuation.
7. Perform comparable-company valuation.
8. Build a football field valuation summary.
9. Evaluate financial stability using Altman Z-Score.
10. Analyse market risk using VaR and Monte Carlo simulation.
11. Compare valuation outputs and interpret the results.

Detailed methodology is available in [`Documentation/Methodology.md`](Documentation/Methodology.md).

---

## Data Sources

Financial and market data used in the analysis were sourced primarily from:

- **Screener.in**
- Publicly available company and market information
- The Valuation School material referenced in the workbook

The financial modelling, calculations, forecasts, valuation framework, and analysis were constructed in Excel.

---

## Tools & Skills

**Tools**

- Microsoft Excel
- Financial modelling
- Spreadsheet analysis

**Skills Demonstrated**

- Financial Statement Analysis
- Equity Research
- Financial Modelling
- DCF Valuation
- Comparable Company Analysis
- WACC
- CAPM
- Beta Analysis
- FCFF Forecasting
- Sensitivity Analysis
- DuPont Analysis
- ROIC / ROE / ROA Analysis
- Risk Analysis
- Altman Z-Score
- Value at Risk
- Monte Carlo Simulation

---

## Repository Structure

```text
Larsen-Toubro-Equity-Valuation/
│
├── README.md
│
├── Excel/
│   └── Larsen-Toubro-Equity-Valuation.xlsx
│
├── Screenshots/
│   ├── WACC.jpg
│   ├── DCF-Valuation-Detail.jpg
│   ├── DCF-Valuation-Detail-2.jpg
│   ├── Football-Field.jpg
│   ├── Relative-Valuation.jpg
│   ├── Altman-Z-Score.jpg
│   └── Altman-Z-Score-Calculation.jpg
│
└── Documentation/
    └── Methodology.md
```

---

## Important Note

The DCF and relative valuation approaches produce different conclusions. This is not treated as an error: the DCF is sensitive to forecast growth, reinvestment, WACC and terminal growth, while relative valuation depends on the trading multiples of the selected comparable companies.

The valuation conclusions therefore represent the output of the assumptions and methodologies used in this model and should not be interpreted as definitive investment recommendations.

---

## Disclaimer

This project is intended for **educational and portfolio purposes only**. It does not constitute investment advice, a recommendation to buy or sell securities, or a guarantee of future performance.

Users should conduct their own research and consult a qualified financial professional before making investment decisions.
