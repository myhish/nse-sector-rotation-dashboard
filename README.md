# NSE Sector Rotation & Tactical Allocation Framework

## 📈 Project Overview
This repository hosts a quantitative investment framework built in Power BI to track cross-sectional sector momentum across the National Stock Exchange (NSE India). The dashboard serves as a tactical radar for fund managers to identify institutional capital flows and evaluate historical performance surrounding major macroeconomic catalysts.

## 🖼️ Dashboard Live View
https://github.com/myhish/nse-sector-rotation-dashboard/blob/main/Sector%20Rotation%20Dashboard.pbix

## 🧮 Core Analytics Architecture
* **Tactical Allocation Leaderboard:** A vertical clustered column podium layout that ranks sectors by an equal-weighted momentum, velocity, and trend-decay composite score (Scale 0-7).
* **Sector Rotation Matrix:** A conditional-formatted heatmap tracking trailing daily structural changes to identify institutional accumulation or distribution phases.
* **Macro Catalyst Overlay:** A lookup engine analyzing historical forward-returns (e.g., 30 days post-RBI Rate Decisions or Union Budgets) to blend daily momentum with macro playbooks.

## 📁 Repository Structure
* `/NSE Data`: Contains raw and processed CSV data structures (Wide-format composite scores and Long-format macro event tables).
* `Sector Rotation Dashboard.pbix`: The core Power BI data model, DAX measures, and frontend layouts.
