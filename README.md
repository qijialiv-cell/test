# Income Inequality Analysis

This project analyzes income inequality trends across countries using data from 1990–2020.

## 🧾 Contents
- **data/**: raw and processed datasets
- **code/**: R, Python, and Stata scripts for cleaning, analysis, and regression
- **output/**: figures and tables for the paper

## 🧠 Methods
- Data cleaning in R
- Visualization in Python
- Regression in Stata

## ⚙️ How to Reproduce
```bash
Rscript code/01_clean_data.R
python code/02_analysis.py
stata -b do code/03_regression.do


```mermaid
flowchart TD
    A[Raw Data] --> B[Clean Data (R)]
    B --> C[Analysis & Visualization (Python)]
    C --> D[Regression & Tables (Stata)]
    D --> E[Figures & Tables for Paper]
    E --> F[GitHub Repository for Reproducibility]
```
