# Discounted Cash Flow (DCF) Valuation Model

📊 **An institutional-grade, intrinsic valuation model designed to calculate the enterprise and equity value of a target corporation through multi-scenario Free Cash Flow to Firm (FCFF) projections.**

---

## 🎯 Executive Overview
This corporate finance project implements an advanced Discounted Cash Flow (DCF) framework built under institutional Wall Street standards (CFI/WSO methodology). The valuation layout bypasses raw theory by incorporating a fully dynamic forecasting mechanics that bridges operational cash generation with rigorous capital structure discount theory.

The model is structured to determine the target company's intrinsic per-share value by projecting future operational cash flows, discounting them via an explicitly calculated WACC, and conducting multi-variable sensitivity analysis.

---

## ⚙️ Core Architecture & Features

*   **Dynamic Unlevered Free Cash Flow (FCFF) Engine:** Built an institutional module deriving historical and projected FCFF from operating profitability, factoring in net capital expenditures (Capex), depreciation (D&A), and net working capital changes (NWC).
*   **Weighted Average Cost of Capital (WACC) Schedule:** Implemented a full cost of capital grid factoring in the Capital Asset Pricing Model (CAPM) for Cost of Equity (Risk-Free Rate, Beta, Equity Risk Premium) and after-tax Cost of Debt based on the firm's capital structure.
*   **Dual Terminal Value Methodologies:** Built terminal value calculators running both the **Perpetual Growth Method (Gordon Growth Model)** and the **EBITDA Exit Multiple Method** to cross-examine intrinsic assumptions.
*   **Two-Dimensional Sensitivity Analysis Grid:** Integrated data tables evaluating the sensitivity of the target share price against simultaneous shifts in the Weighted Average Cost of Capital (WACC) and the Perpetual Growth Rate (g).
*   **Institutional Layout & Color-Coding:** Followed explicit Wall Street presentation rules (Blue for historical hardcoded inputs, Black for live formulas) with gridlines removed on core evaluation dashboards.

---

## 🗺️ Valuation Model & File Structure

*   📂 `Cover / Read Me` — Metadata section outlining project scope, structural index, and presentation parameters.
*   📂 `Valuation Dashboard` — Core visual output containing target implied enterprise value, equity value, and target price calculations.
*   📂 `FCFF Forecasting Schedule` — 5-year operational cash flow pro-forma statements under Base, Upside, and Downside scenarios.
*   📂 `WACC & Capital Structure` — Detailed breakdowns of cost of debt, cost of equity, asset/equity beta unlevering formulas, and capital weights.
*   📂 `Sensitivity Matrices` — Output grids testing valuation volatility against changes in discount rates and growth terminal targets.

---

## 🛠️ Tech Stack & Standards Applied
*   **Software:** Microsoft Excel (Advanced Valuation & Data Tables).
*   **Methodology:** Corporate Finance Institute (CFI) & Wall Street Oasis (WSO) Valuation Standards.
*   **Core Concepts Applied:** Intrinsic Valuation, FCFF, WACC (CAPM), Terminal Value, Sensitivity Analyses.

---
*Developed by an Aspiring Finance Professional dedicated to building data-driven, practical corporate finance applications.*
