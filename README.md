# Homework 3: Survival Analysis

This repository contains my Marketing Analytics homework on survival analysis using a telecom churn dataset.

The goal of the project is to model customer churn with parametric Accelerated Failure Time models, compare survival distributions, choose a final model, estimate customer lifetime value, analyze CLV across customer segments, and recommend a retention budget.

## Files

- `Survival_Analysis_HW3.ipynb` — main notebook with code, outputs, and report
- `telco.csv` — telecom churn dataset
- `aft_model_comparison.csv` — saved model comparison results
- `segment_clv_summary.csv` — saved CLV segment summary
- `telco_survival_clv_results.csv` — customer-level survival and CLV results
- `retention_budget_summary.csv` — retention budget summary
- `requirements.txt` — Python packages needed to run the notebook

## Methods

The analysis includes:

- Data loading and preprocessing
- Churn event encoding
- Parametric AFT model fitting
- Model comparison using AIC, BIC, log-likelihood, and concordance index
- Survival curve visualization
- Significant feature selection
- Final model fitting
- Customer-level CLV estimation
- Segment-level CLV analysis
- Annual retention budget recommendation

## How to Run

Install the required packages:

```bash
pip install -r requirements.txt
