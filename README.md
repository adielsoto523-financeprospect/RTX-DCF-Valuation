# RTX Corporation: Financial Forecast & DCF Valuation

Excel model that forecasts RTX Corporation's financial statements through 2030 and values the stock with a discounted cash flow (DCF). This is my individual company analysis from a Financial Statement Analysis course project, where our team studied an industry and developed a 12-month stock recommendation, and each member valued one firm.

## Question
What is one share of RTX worth, and how does that compare to its market price of $206.52 (3/3/2026)?

## Result
| | |
|---|---|
| Estimated value per share | ~$144 |
| Market price (3/3/2026) | $206.52 |
| Implied upside / (downside) | (30%) |
| Sensitivity range (WACC 7–9%, terminal growth 2–4%) | ~$98 – $252 |
| Recommendation | Sell |

[Insert screenshot of the DCF and sensitivity tables]

## Method
1. **Forecast** the income statement and balance sheet for 2026–2030.
2. **Free cash flow** = NOPAT (EBIT less 21% tax) minus the change in net operating assets (NOA).
3. **Discount** cash flows at an 8% WACC, with a terminal value at 3% growth.
4. **Equity value** = firm value + cash − debt − noncontrolling interest − stock compensation claims, divided by diluted shares.
5. **Sensitivity**: live tables of value per share and upside/downside across WACC and terminal growth.
6. **Ratio analysis** of 2023–2025 profitability, leverage, and working capital (DuPont, turnover, cash cycle).

## Support for key assumptions
| Assumption | Forecast | Why |
| Revenue growth | 8% → 4% | [e.g., 2025 growth of 9.7%, backlog, segment outlook; fading toward industry growth] |
| Operating margin | 11% → 13% | [e.g., 2025 margin of 10.5%, mix shift, cost trends] |
| Goodwill | Held flat | No acquisitions assumed; goodwill does not scale with sales |
| WACC / terminal growth | 8% / 3% |

## Limitations
- Terminal value is about 88% of operating value, so long-term assumptions drive the result.
- WACC is an assumption and has not been built up from CAPM inputs.
- Balance sheet equity is a plug, so the three statements are not fully integrated.
- The model's implied P/E (~29x) is well below the market's (~42x); I treat that gap as something to investigate, not proof of mispricing.

## Workbook tabs
Income Statement · Balance Sheet · Cash Flow Statement · Ratios · NOA · DCF Valuation · Forecast Assumptions · Charts

## Data
RTX financial statements, FY2022–2025 https://www.sec.gov/ix?doc=/Archives/edgar/data/0000101829/000010182926000006/rtx-20251231.htm. Stock price as of 3/3/2026.h sensitivity. Built in Excel.
