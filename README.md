# DEVINE-GROUPS-QUANT-RESEARCH-INTERNSHIP-
# DG05 Quant Strategy — Production Fact Sheet Project

![Project Stage](https://img.shields.io/badge/Stage-In_Progress-yellow)
![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![Last Updated](https://img.shields.io/badge/Updated-May_2025-orange)

![Strategy Type](https://img.shields.io/badge/Strategy-HFT_Momentum-purple)
![Deployment](https://img.shields.io/badge/Deployed-Yes-green)
![Outputs](https://img.shields.io/badge/Outputs-PDF_&_Plots-success)
![Benchmark](https://img.shields.io/badge/Benchmark-BTC-black)

> 🧠 Developed during Quant Research Internship @ Devine Group


# DG05 Quant Strategy — Production Fact Sheet Project

This repository contains the full quantitative analysis and production-grade fact sheet development for **DG05**, an HFT Opportunistic Momentum Strategy under Devine Group's Digital Assets portfolio.

## 🧠 Strategy Overview

- **Name:** DG05  
- **Type:** High-Frequency Opportunistic Momentum  
- **Benchmark:** BTC  
- **Returns:** Gross Daily Returns (Unadjusted for Fees)

## 🔧 Project Structure

This project is executed in an agile, modular format inspired by professional quant research workflows at top hedge funds. It includes:

### 🔹 Phase 1 — Data Ingestion & Validation
- Parsing daily return data from PDFs
- Structuring time-series in pandas

### 🔹 Phase 2 — Core Quant Analysis
- CAGR, Annualized Volatility, Sharpe Ratio (gross), Calmar Ratio
- Max Drawdown, Win Rate, Skewness, Kurtosis

### 🔹 Phase 3 — Visualizations
- Equity Curve
- Drawdown Plot
- Monthly Return Heatmap
- BTC Benchmark Comparison (Coming soon)

### 🔹 Phase 4 — Fact Sheet Design
- Clean 1-page PDF layout with:
  - Key stats table
  - Professional charts
  - Strategy description and highlights

## 📁 Key Outputs
- `DG05_Quant_FactSheet_Structure.pdf`: Structural planning document (for internal and public documentation)
- `DG05_EquityCurve.png`: Strategy equity curve
- `DG05_FactSheet.pdf`: Final one-page institutional-grade strategy fact sheet

## 📌 Notes
- All returns used are gross (pre-cost, pre-fee)
- Sharpe is calculated without risk-free adjustment
- Drawdowns and volatility annualized using 252 trading days

---

👨‍💻 Developed as part of my **Quant Research Internship at Devine Group**.


