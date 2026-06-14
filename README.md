# ESG Risk Pricing with XGBoost and SHAP

Machine Learning and Explainable AI project for analyzing the impact of ESG (Environmental, Social and Governance) performance on corporate market value.

This study combines predictive analytics, explainable artificial intelligence and strategic management frameworks to investigate whether sustainability-related factors influence firm valuation and how their impact changes across industries, geographic regions and time.

---

## Project Overview

Sustainability has evolved from a corporate responsibility initiative into a strategic factor that can influence business performance and investor perception.

The objective of this project is to quantify the relationship between ESG performance and corporate market capitalization using a data-driven approach based on Machine Learning and Explainable AI.

The analysis goes beyond traditional ESG scoring by identifying which sustainability factors are actually valued by the market and under which conditions they become relevant.

---

## Research Questions

This project aims to answer the following questions:

- Do ESG indicators influence corporate market value?
- Which ESG dimensions contribute the most to valuation?
- Has the importance of ESG changed over time?
- Does ESG impact differ across industries and geographic regions?
- Can sustainability be interpreted as a measurable risk factor?

---

## Dataset

The analysis is based on a longitudinal corporate dataset containing:

- 1,000 companies
- 11 years of observations (2015–2025)
- 11,000 total records

The dataset combines:

### Financial Variables

- Revenue
- Profit Margin
- Market Capitalization (Target Variable)

### ESG Indicators

- ESG Environmental Score
- ESG Social Score
- ESG Governance Score
- ESG Overall Score

### Environmental Impact Metrics

- Carbon Emissions
- Energy Consumption
- Water Usage

### Contextual Variables

- Industry
- Region
- Year

---

## Methodology

### 1. Data Preparation

Raw environmental indicators were transformed into efficiency-based sustainability metrics through feature engineering:

- Carbon Intensity = Carbon Emissions / Revenue
- Energy Intensity = Energy Consumption / Revenue
- Water Intensity = Water Usage / Revenue

This approach allows meaningful comparisons between companies of different sizes.

---

### 2. Predictive Modeling

The prediction task consists of estimating corporate Market Capitalization using both financial and sustainability indicators.

#### Model

- XGBoost Regressor

#### Target Variable

- MarketCap

#### Evaluation

- Train/Test Split (80/20)
- Multiple random seed validation
- R² performance between 0.85 and 0.95 across segments

---

### 3. Explainable AI

To interpret model decisions, SHAP (Shapley Additive Explanations) was used.

SHAP makes it possible to:

- Measure the contribution of each feature
- Identify the most influential valuation drivers
- Compare ESG relevance across contexts
- Move from prediction to interpretation

---

### 4. Contextual Analysis

The study investigates ESG impact across:

#### Time

Comparison between:

- 2015–2019
- 2020–2025

#### Geography

Comparison between:

- Europe
- North America

#### Industry

Comparison between:

- Energy Sector
- Technology Sector

---

### 5. Strategic Interpretation

Quantitative results were integrated with strategic management frameworks:

- SWOT Analysis
- PESTEL Analysis

This allowed the translation of machine learning insights into managerial and investment implications.

---

## Key Findings

### Global Drivers of Corporate Value

The strongest predictors of Market Capitalization are:

1. Revenue
2. Profit Margin
3. Carbon Intensity
4. ESG Governance

Financial fundamentals remain dominant, but sustainability-related indicators emerge as significant valuation drivers.

---

### ESG Became More Important After 2020

The analysis shows a substantial increase in ESG relevance after 2020.

Environmental efficiency metrics, particularly Carbon Intensity, became significantly more influential in explaining corporate value.

This suggests that investors increasingly incorporate climate-related risks into valuation processes.

---

### Regional Differences

#### Europe

The market places stronger emphasis on:

- Environmental Performance
- Carbon Efficiency

This reflects a highly regulated sustainability environment.

#### North America

The market adopts a more balanced approach involving:

- ESG Overall Score
- Governance Quality
- Carbon Intensity

Governance emerges as a major risk-management factor.

---

### Industry Differences

#### Energy Sector

ESG indicators become strategic drivers of value.

Sustainability is strongly connected to long-term competitiveness and risk management.

#### Technology Sector

Financial fundamentals remain dominant.

Among ESG dimensions, Social factors are the most relevant due to:

- AI Ethics
- Data Privacy
- Human Capital Management
- Reputation Risk

---

## Technologies

### Programming

- Python

### Data Analysis

- Pandas
- NumPy

### Machine Learning

- XGBoost
- Scikit-Learn

### Explainable AI

- SHAP

### Visualization

- Matplotlib
- Seaborn

### Development Environment

- Jupyter Notebook

---

## Repository Structure

```text
.
├── ESG_Analysis.ipynb
├── ESG_Report.pdf
├── ESG_Presentation.pdf
├── README.md
└── figures/
```

---

## Results

The project demonstrates that ESG performance influences corporate valuation, but not in a universal way.

The market does not reward sustainability as a generic ethical principle.

Instead, ESG factors are interpreted as measurable indicators of risk and opportunity whose relevance depends on:

- Time
- Geographic Region
- Industry Context

These findings support the view that sustainability is becoming an increasingly important component of corporate value creation and strategic decision making.

---

## Author

**Giuseppe Rega**

M.Sc. Candidate in Data Science and Innovation Management

University of Salerno

GitHub: https://github.com/gregablu-ai