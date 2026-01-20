<div align="center">

# Liam Egan
**Chemical Engineering (BS) | MS Business Analytics | University of Notre Dame ('26)**

[LinkedIn](https://www.linkedin.com/in/liam-egan-) | [Email](mailto:ljegan01@gmail.com) | [Portfolio](https://github.com/eganl2024-sudo?tab=repositories)

</div>

---

### 🏛️ Professional Summary

**Engineering-driven analyst building financial intelligence platforms for energy markets.**

I leverage a background in **Chemical Process Engineering** to connect physical commodity flows with equity valuations. My work focuses on quantifying operational reality—building models that bridge refinery unit economics, reservoir physics, and capital markets to answer questions standard accounting can't address.

Currently serving as President of the **Student-Athlete Advisory Council** at Notre Dame, representing 700+ Division I athletes while completing my MSBA.

---

### 🚀 Flagship Projects

#### 1. [Refinery Arbitrage Engine (Live Analytics Platform)](https://github.com/eganl2024-sudo/Refinery-Arbitrage-Engine)
*Real-time commodity margin & equity valuation monitor for downstream energy.*

**[🚀 Launch Live Dashboard](https://refinery-arbitrage-engine-uturqbhqngbykahhfonr6k.streamlit.app/)**

* **The Challenge:** Refinery equities should correlate with physical crack spreads, but the relationship is complex and regime-dependent.
* **The Solution:** Built a production-grade analytics engine modeling the industry-standard 3:2:1 crack spread with Natural Gas OpEx integration to calculate net refining margins. Implemented dual-methodology correlation analysis (price levels vs. returns) to identify when physical margins decouple from equity performance.
* **Key Findings:** 
  - Testing both methodologies revealed Valero (VLO) responds to short-term margin volatility (0.26 daily correlation) but decouples long-term (0.11 level correlation)
  - Valero's $10B+ in share buybacks dominated returns more than spot spreads over 2020-2025 period
  - Valuation model quantifies $9B EBITDA impact from $10/bbl margin expansion at current throughput
* **Stack:** Python, Streamlit, Plotly Interactive, yfinance API, Statsmodels (OLS), Auto-generated Executive Summaries.

#### 2. [Energy Capital Discipline Monitor (Live Risk Engine)](https://github.com/eganl2024-sudo/Post-COVID-recovery-in-Oil-and-Gas)
*Real-time platform tracking shareholder yield, solvency, and capital allocation across Energy Majors.*

**[🚀 Launch Live Dashboard](https://energy-capital-monitor.streamlit.app)**

* **The Challenge:** Post-2020, energy investors shifted from rewarding production growth to rewarding capital discipline and cash returns.
* **The Solution:** Engineered a live diagnostic engine normalizing global accounting data (US GAAP vs. IFRS) to calculate Dividend Sustainability Ratios (DSR) and cash breakevens in real-time. Built interactive "Oil Price Shock" simulator testing 0-50% operating cash flow downturn scenarios across 7 energy majors.
* **Key Findings:**
  - Shell (SHEL) displays higher solvency resilience than Chevron (CVX) under 40% downturn scenarios
  - FCF conversion ratios reveal companies funding dividends with cash generation vs. debt
  - Real-time monitoring identifies sector leaders in capital discipline
* **Stack:** Python, Streamlit, yfinance API, LRU Caching, Custom Bloomberg-style UI, Plotly Charts.

#### 3. [Energy Valuation Engine: "Managed Decline" Model](https://github.com/eganl2024-sudo/Energy-Valuation-Analysis)
*Scenario-based valuation platform stress-testing Energy Majors against energy transition.*

* **The Challenge:** Standard DCF models assume perpetual +2% growth, ignoring physical reality of reservoir depletion and secular demand shifts.
* **The Solution:** Architected "Managed Decline" valuation framework with -1.5% terminal growth rate for fossil assets to quantify floor value. Implemented WACC/CAPM stratification differentiating upstream risk (β=1.25) from utility risk (β=0.95). Built modular architecture separating assumptions, logic, and data for model governance.
* **Key Findings:**
  - ExxonMobil (XOM) model implies ~13% upside at $85/bbl oil, suggesting market pricing in faster transition than fundamentals support
  - Bear case ($60 oil) yields $64/share, highlighting massive commodity beta in integrated majors
  - Near-term cash flows justify current valuations despite long-term terminal value uncertainty
* **Stack:** Python (Pandas, NumPy), DCF/WACC Models, Sensitivity Analysis (Football Fields), Jupyter, yfinance API.

---

### 🛠️ Technical Competencies

| Domain | Toolkit |
| :--- | :--- |
| **Financial Modeling** | DCF Valuation, LBO Fundamentals, Dividend Stress Testing, WACC/CAPM, Crack Spread Modeling, OpEx Analysis, Sensitivity Analysis |
| **Data Engineering** | Python (Pandas, NumPy, SciPy), SQL, R, Live API Integration (yfinance), Real-time Futures Data, Data Normalization (IFRS/GAAP) |
| **Statistical Analysis** | Correlation Analysis (Levels vs Returns), Z-Score/Percentile Signals, Regression, Rolling Window Analysis, Time Series, OLS |
| **Process Engineering** | Aspen Plus, Process Simulation, Mass & Energy Balance, Capital Cost Estimation (CAPEX/OPEX), Unit Operations, Refinery Economics |
| **Visualization & Deployment** | Streamlit, Plotly Interactive, Tableau, Advanced Excel, Bloomberg-style Dashboards, Git/GitHub |

---

### 📂 Selected Project Portfolio

**[Grow Irish: Performance Analytics Platform](https://github.com/eganl2024-sudo/MDP_APP)**
* **Scope:** GPS-based session intensity and metabolic power demand (MDP) analysis application for Division I soccer athletes.
* **Impact:** Transforms raw GPS tracking data into actionable coaching insights, analyzing peak power output across 10s/20s/30s windows to optimize workload distribution and reduce soft-tissue injury risk. Features dual "Coach vs. Analyst" views for different stakeholder needs.
* **Stack:** Streamlit, Python (Pandas, NumPy, SciPy), GPS Data Processing, Z-score Normalization, Multi-page Application Architecture.

---

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-Live-red)
![Focus](https://img.shields.io/badge/Focus-Energy%20Finance-green)

<sub>© 2026 Liam Egan | Built for Energy Finance</sub>

</div>
