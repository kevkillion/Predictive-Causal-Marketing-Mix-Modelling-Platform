# 📈 Predictive & Causal Marketing Mix Modelling Platform  
**Powered by:** PyMC | Python | MLflow | Power BI | Meridian (Google) | Robyn (Meta) | PMG Analytics  

![MMM Causal Framework Diagram](docs/Marketing_Mix_Modelling_Causal_Framework.png)

> **From Data to Decisions — Powered by Bayesian Intelligence.**  
> A scalable MMM platform combining predictive modelling, causal inference, and multi-model validation to reveal true cross-channel performance, optimise budgets, and quantify ROI with scientific rigour.

---

## 🧩 Overview  
This repository showcases a **next-generation Bayesian Marketing Mix Modelling (MMM) framework** designed for **predictive, causal, and comparative analysis** across multiple media channels — including **SEM, Social, TV, Radio, OOH, and Digital Video**.  

Developed using **PyMC** for Bayesian inference, **MLflow** for version tracking, and **Power BI** for interactive analysis, the platform allows **multi-model testing and cross-validation** against alternative modelling frameworks such as **Meridian (Google)** and **Robyn (Meta)** to benchmark and confirm results consistency.  

It empowers marketing and data science teams to move beyond single-model dependency, using **frequentist and Bayesian triangulation** to identify the most reliable media ROI estimates and inform optimal budget reallocation.

---

## 💡 Key Features  

| Category | Description |
|-----------|-------------|
| 🔮 **Bayesian MMM Engine** | Built in **PyMC**, the platform estimates both immediate and delayed media effects using Adstock and Hill transformations — capturing saturation, diminishing returns, and carryover with full posterior distributions. |
| 🧠 **Causal Inference & Halo Modelling** | Quantifies **indirect effects** and **cross-channel synergies** using structural causal models and interaction terms to measure true incremental value. |
| 🧩 **Multi-Model Selection & Testing** | Integrates **multiple MMM frameworks** (PyMC Bayesian, Meridian Frequentist, Robyn Lasso) within the same workflow for side-by-side comparison, ensuring cross-validated, stable outcomes. |
| 🧪 **Rigorous Cross-Validation Framework** | Performs **train-test splits, k-fold validation, and baseline model confirmation** to test reliability, predictive accuracy, and out-of-sample generalisation. |
| ⚙️ **MLflow Tracking & Version Control** | Logs every model run, hyperparameter, and posterior trace, enabling transparent replication, comparison, and tuning. |
| 📊 **Power BI Multi-Model Dashboard** | Enables **filterable model selection** — compare Bayesian vs. frequentist outputs, view elasticity curves, ROI matrices, and channel prioritisation dashboards interactively. |
| ☁️ **Partitioned Cloud Data Architecture** | Uses BigQuery or Delta Lake with partitioned datasets for efficient retraining, scalability, and time-based analysis. |

---

## 🧠 Architecture Overview  

| Layer | Tools | Purpose |
|-------|--------|----------|
| **Data Layer** | BigQuery, Python, Pandas | Aggregates multi-channel spend, sales, and contextual data across time and markets. |
| **Transformation Layer** | PySpark, Python | Applies Adstock, Hill, lag optimisations, and seasonal controls to produce model-ready data. |
| **Model Layer** | PyMC, Robyn (Meta), Meridian (Google) | Fits multiple MMMs — Bayesian (PyMC), Frequentist Ridge/Lasso (Robyn/Meridian) — for triangulated benchmarking. |
| **Validation Layer** | Cross-Validation, MAPE/R² | Executes **multi-fold validation** to assess model stability, predictive reliability, and consistency across time and channels. |
| **Tracking Layer** | MLflow | Centralised run logging and version comparison for transparent model lifecycle management. |
| **Analytics Layer** | Power BI | Visualises model results, ROI by channel, and multi-model comparisons through interactive filters and scenario selectors. |

---

## ⚙️ Modelling & Validation Capabilities  

- 📈 **Predictive Component**  
  Uses Bayesian regression to estimate ROI curves and contribution shares with uncertainty intervals.  

- 🔄 **Causal Component**  
  Identifies indirect effects and channel synergies using causal graphs and structural equations.  

- 🧩 **Multi-Model Filterability & Testing**  
  Power BI dashboards allow stakeholders to **filter, compare, and validate** results across multiple model frameworks (PyMC Bayesian, Meridian, Robyn).  

- 🧪 **Rigorous Cross-Validation**  
  Implements **time-series rolling validation** and **k-fold splits**, verifying model consistency and predictive accuracy relative to Google Meridian and Meta Robyn baselines.  

- 🎯 **Channel Prioritisation & Benchmarking**  
  Channel ROI rankings are dynamically benchmarked against multiple model outcomes, revealing stability, sensitivity, and confidence across modelling approaches.  

- 🧮 **Elasticity & Saturation Curves**  
  Generates marginal ROI and elasticity curves per channel for decision-based spend optimisation.  

- 🧠 **Scenario Simulation**  
  Power BI integrates scenario sliders — simulate *“Shift 10% TV to Digital”* and view predicted impact and confidence ranges.  

---

## 📊 Power BI Multi-Model Dashboard  

![Power BI MMM Dashboard](docs/PowerBI_MMM_Insights_Dashboard.png)

**Dashboard Highlights:**  
- Bayesian vs Frequentist model comparison  
- Channel contribution & synergy decomposition  
- Marginal ROI and elasticity curves  
- Adstock and Hill parameter visualisation  
- Model-confidence benchmarking via cross-validation metrics  
- Interactive scenario testing and spend optimisation tools  

---

## 🚀 Success & Impact  

> **AUD 2.5M+ annual savings** | **$12M ROI uplift** | **15% media efficiency gain**

**Results:**  
- Validated and optimised media allocation across **SEM, Social, TV, OOH, and Radio**.  
- **Triangulated results across Meridian, Robyn, and PyMC** for model confirmation and governance rigour.  
- Reduced modelling uncertainty and improved confidence in investment decisions.  
- Enabled **live Power BI dashboards** with multi-model selection and real-time reallocation insights.  
- Delivered measurable financial outcomes: **AUD 2.5M+ savings**, **$12M ROI uplift**, and **15% greater media efficiency**.  

---

## 🧩 Workflow  

1. **Data Aggregation:** Ingests multi-channel spend and performance data into BigQuery.  
2. **Pre-Processing:** Applies lag optimisation, Adstock, Hill, and multicollinearity adjustments.  
3. **Model Execution:** Runs Bayesian MMM (PyMC) + Frequentist (Robyn/Meridian) in parallel.  
4. **Validation:** Cross-validates results and confirms predictive consistency.  
5. **Tracking:** Logs all versions in MLflow for comparison and reproducibility.  
6. **Visualisation:** Publishes ROI curves, contributions, and scenario models to Power BI dashboards.  

---
