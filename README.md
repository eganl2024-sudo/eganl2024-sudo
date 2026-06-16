<div align="center">

# Liam Egan
**Finance professional focused on energy markets, valuation, and data-driven investment analysis**

**B.S. Chemical Engineering + M.S. Business Analytics, University of Notre Dame ('26)**

[LinkedIn](https://www.linkedin.com/in/liam-egan-) • [Email](mailto:ljegan01@gmail.com) • [GitHub Projects](https://github.com/eganl2024-sudo?tab=repositories)

</div>

---

## Profile

I am a University of Notre Dame student combining **chemical engineering, business analytics, and financial modeling** to evaluate energy markets and capital-intensive businesses.

My work is centered on understanding how **physical operating fundamentals translate into equity performance, valuation, and capital allocation outcomes**. I am particularly interested in the energy sector because it sits at the intersection of commodity markets, industrial operations, and financial decision-making.

Across my projects, I build analytical tools that connect:
- **reservoir physics and well-level economics**
- **commodity price movements and margin dynamics**
- **corporate financial performance and capital allocation**
- **market sentiment and information flow**

---

## Areas of Focus

- Energy finance and investment banking
- Upstream E&P economics and reserve valuation
- Capital allocation and shareholder returns
- Market-based decision tools and financial analytics
- Operating-driver analysis for industrial and energy companies

---

## Selected Energy Finance Work

### Permian Basin Well Economics Engine
**Production decline modeling and investment economics platform for upstream E&P**
[![Live Dashboard](https://img.shields.io/badge/Live_Dashboard-Streamlit-FF4B4B?style=flat&logo=streamlit)](https://permian-well-economics.streamlit.app) [![Tests](https://img.shields.io/badge/Tests-51_passing-2ECC71?style=flat)](https://github.com/eganl2024-sudo/permian-well-economics/tree/main/tests)
[Repository](https://github.com/eganl2024-sudo/permian-well-economics) | [Live Dashboard](https://permian-well-economics.streamlit.app)

> *"I don't have an upstream internship on my resume. So I built the analytics tools upstream analysts use and learned the reservoir physics behind them."*

- Implemented **Arps decline curve models** (exponential, hyperbolic, harmonic, modified hyperbolic) with AIC-based model selection and **P10/P50/P90 EUR confidence intervals** from fitted parameter covariance matrices
- Built a full **monthly cash flow engine** producing PV10, IRR, payback period, breakeven WTI, F&D cost, and NPV per lateral foot — with a 5×7 WTI × D&C cost sensitivity heatmap and Excel export
- Modeled **sub-basin type curves** for Midland Basin, Delaware Basin, and Central Platform, with operator profiles for Diamondback, EOG, Pioneer, and Devon normalized across five capital efficiency dimensions
- Documented methodology to **SPE technical paper standards** with full equation disclosure; 51 passing unit tests across the decline curve and economics engines

**Focus:** Upstream E&P analytics, reserve engineering, well economics, capital efficiency, PV10/IRR

---

### Energy Sector NLP Sentiment Pipeline
**Real-time FinBERT sentiment scoring paired with live commodity market data**
[![Live Dashboard](https://img.shields.io/badge/Live_Dashboard-Streamlit-FF4B4B?style=flat&logo=streamlit)](https://energy-sentiment-pipeline.streamlit.app/)
[Repository](https://github.com/eganl2024-sudo/energy-sentiment-pipeline) | [Live Dashboard](https://energy-sentiment-pipeline.streamlit.app/)

- Built a live NLP pipeline collecting real-time financial news headlines across six major energy equities (VLO, PSX, MPC, XOM, CVX, COP), filtered with an energy-domain keyword list to isolate refining-relevant signal from general market noise
- Replaced VADER with **FinBERT** (`ProsusAI/finbert`) — a BERT-based transformer trained on 10,000 Financial PhraseBank sentences — accessed via the HuggingFace Inference API to avoid PyTorch deployment overhead
- Paired FinBERT sentiment scoring with a **live 3:2:1 crack spread monitor** (5-minute refresh) to enable direct comparison between market narrative and physical margin conditions
- Addressed the core research question of whether unstructured news flow leads or lags structured commodity price data — a setup for lagged-correlation and Granger causality extensions

**Focus:** Financial NLP, unstructured data, market sentiment, commodity market intelligence

---

### Energy Capital Discipline Monitor
**Capital allocation and balance-sheet resilience dashboard for Oil & Gas majors**
[![Live Dashboard](https://img.shields.io/badge/Live_Dashboard-Streamlit-FF4B4B?style=flat&logo=streamlit)](https://eganl2024-sudo-post-covid-recovery-in-oil-and-gas-app-lrw3ax.streamlit.app/)
[Repository](https://github.com/eganl2024-sudo/Post-COVID-recovery-in-Oil-and-Gas) | [Live Dashboard](https://eganl2024-sudo-post-covid-recovery-in-oil-and-gas-app-lrw3ax.streamlit.app/)

- Built a comparative monitoring platform tracking **shareholder yield, solvency, dividend durability, and FCF quality** across XOM, CVX, SHEL, TTE, BP, and EQNR
- Normalized IFRS and GAAP accounting differences across firms to improve cross-company comparability; separated cash earnings from accrual-based net income using **FCF conversion ratios**
- Implemented an interactive **Dividend Sustainability Ratio (DSR) stress test** — users simulate OCF downturns of 0–50% and observe real-time recalculation of each firm's ability to cover commitments
- Identified Shell (SHEL) as structurally more resilient to a commodity price shock than its peers under current capital structures

**Focus:** Capital discipline, balance-sheet quality, dividend sustainability, comparative company analysis

---

### Refinery Arbitrage Engine
**Commodity margin modeling and equity sensitivity platform for downstream energy**
[![Live Dashboard](https://img.shields.io/badge/Live_Dashboard-Streamlit-FF4B4B?style=flat&logo=streamlit)](https://refinery-arbitrage-engine-uturqbhqngbykahhfonr6k.streamlit.app/)
[Repository](https://github.com/eganl2024-sudo/Refinery-Arbitrage-Engine) | [Live Dashboard](https://refinery-arbitrage-engine-uturqbhqngbykahhfonr6k.streamlit.app/)

- Modeled the industry-standard **3:2:1 crack spread** with variable OpEx integration (natural gas intensity × throughput) and a fixed cost layer to approximate net refining margin
- Built a **cycle-aware valuation model** for Valero (VLO): EV/EBITDA multiples compress at peak spreads (4.5x) and expand at trough (8.5x), with an economic run-cut floor that reduces throughput when margins fall below breakeven
- Scraped and analyzed **87 EIA institutional reports** (2022–2026) using VADER sentiment and LDA topic modeling; tested bidirectional Granger causality at lags of 1–4 weeks — found no significant relationship (p > 0.05), consistent with semi-strong market efficiency
- Structured DuckDB data layer with absolute-path resolution and a cold-start bootstrap module so the deployed app generates all market data automatically on first run

**Focus:** Refining economics, equity sensitivity, NLP/causality research, commodity market structure

---

## Additional Work

| Project | Description |
| :-- | :-- |
| [Energy Valuation Analysis](https://github.com/eganl2024-sudo/Energy-Valuation-Analysis) | DCF framework stress-testing managed decline assumptions for integrated energy companies across $60/$85/$110 oil price scenarios |
| [Grow Irish](https://mdp-app.streamlit.app/) | GPS-based athlete workload and session-intensity analytics platform built for Notre Dame athletics |

---

## Analytical Toolkit

| Area | Tools / Experience |
| :-- | :-- |
| **Financial Analysis** | DCF valuation, PV10/IRR, WACC/CAPM, scenario analysis, sensitivity analysis, dividend sustainability, capital allocation |
| **Market & Operating Analysis** | Crack spread modeling, decline curve fitting, refining economics, commodity-linked earnings, upstream E&P metrics |
| **Data & Modeling** | Python, SQL, Pandas, NumPy, SciPy, statsmodels, regression, time series, NLP (FinBERT, VADER, LDA) |
| **Visualization & Communication** | Streamlit, Plotly, Tableau, Excel, dashboard design, executive-style presentation |
| **Engineering Foundation** | Process simulation, mass & energy balances, reservoir physics, CAPEX/OPEX thinking, industrial systems analysis |

---

## Leadership

**President, Student-Athlete Advisory Council — University of Notre Dame**

Representing more than **700 Division I student-athletes** while leading across athletics, communication, and institutional collaboration.

---

## Career Interests

I am especially interested in opportunities in:
- **Energy investment banking**
- **Equity research**
- **Upstream or downstream financial analysis**
- **Analytics roles tied to markets and operating performance**

If you work in those areas, I'd be glad to connect.

---

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat&logo=python)](https://python.org)
[![Focus](https://img.shields.io/badge/Focus-Energy%20Finance-red?style=flat)](https://github.com/eganl2024-sudo?tab=repositories)
[![Sector](https://img.shields.io/badge/Sector-Energy%20IB-green?style=flat)](https://www.linkedin.com/in/liam-egan-)

</div>
