# Quantitative Deep-Tech Investment Screening Framework

A quantitative investment decision framework developed to evaluate and rank leading deep-tech companies for a hypothetical **$1,000,000 venture capital investment**.

The project combines **multi-criteria decision analysis (MCDA)** techniques with quantitative validation to identify the strongest long-term investment opportunity across **49 companies** spanning Artificial Intelligence, Robotics, Defence Technology, Space Technology, and Quantum Computing.

---

## Project Overview

Selecting investments in the deep-tech sector is challenging because companies differ significantly in:

- Business maturity
- Financial transparency
- Commercialization stage
- Technology readiness
- Risk profile

Traditional financial metrics alone are insufficient to compare private and public companies within the same investment universe.

To address this challenge, this project develops a **Quantitative Deep-Tech Investment Screening Framework** that integrates financial, technological, strategic, and qualitative indicators into a unified investment evaluation methodology.

---

## Objectives

- Evaluate **49 leading deep-tech companies**
- Compare companies using **31 evaluation criteria**
- Rank investments using multiple decision-making techniques
- Validate recommendation robustness using simulation
- Recommend the strongest candidate for a hypothetical **$1 million investment**

---

## Methodology

The investment framework follows the pipeline below:

```
49 Deep-Tech Companies
        │
        ▼
Data Collection
        │
        ▼
Feature Engineering
        │
        ▼
31 Evaluation Criteria
        │
        ▼
Data Normalization
        │
        ▼
Weighted Scoring
        │
        ▼
Analytic Hierarchy Process (AHP)
        │
        ▼
TOPSIS Ranking
        │
        ▼
Monte Carlo Simulation
        │
        ▼
Sensitivity Analysis
        │
        ▼
Investment Committee Review
        │
        ▼
Final Investment Recommendation
```

---

## Evaluation Criteria

The framework evaluates companies across multiple investment dimensions, including:

- Financial Strength
- Technology Leadership
- Commercialization
- Execution Capability
- Competitive Positioning
- Scalability
- Investment Risk

A total of **31 quantitative and qualitative features** were used to generate the final rankings.

---

## Decision-Making Techniques

This project combines multiple quantitative methods:

- Weighted Scoring Model
- Analytic Hierarchy Process (AHP)
- Technique for Order Preference by Similarity to Ideal Solution (TOPSIS)
- Monte Carlo Simulation
- Sensitivity Analysis

Using multiple approaches reduces dependence on a single ranking methodology and improves confidence in the final recommendation.

---

## Key Results

### Investment Universe

- 49 Deep-Tech Companies
- 5 Strategic Sectors
- 31 Evaluation Criteria

### Top Ranked Investment

| Rank | Company | Weighted Score | TOPSIS |
|------:|---------|---------------:|--------:|
| 1 | **SpaceX** | **85.85** | **0.703** |
| 2 | Anduril Industries | 84.91 | 0.691 |
| 3 | OpenAI | 84.36 | 0.684 |
| 4 | Anthropic | 83.92 | 0.678 |
| 5 | Figure AI | 83.51 | 0.671 |

---

## Robustness Validation

The recommendation was validated using Monte Carlo simulation.

| Metric | Result |
|---------|--------|
| Probability of Rank #1 | **64.9%** |
| Probability of Top 3 | **91.5%** |
| Probability of Top 5 | **96.5%** |

Sensitivity analysis further showed that **SpaceX remained Rank 1 across all weighting strategies**, indicating that the recommendation is robust to reasonable changes in evaluation assumptions.

---

## Repository Structure

```
DeepTech-Investment-Framework/
│
├── deeptech_investment_framework.ipynb
├── Investment_Memorandum.pdf
├── README.md
├── requirements.txt
│
└── outputs/
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- SciPy
- Scikit-learn
- StatsModels
- MissingNo
- Yahoo Finance

---

## Installation

Clone the repository:

```bash
git clone https://github.com/DebadattaLiku/DeepTech-Investment-Framework.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
deeptech_investment_framework.ipynb
```

---

## Report

The complete investment memorandum is available in:

```
Investment_Memorandum.pdf
```

---

## Future Improvements

Potential extensions include:

- Automated real-time market data integration
- ESG scoring
- Reinforcement Learning for portfolio optimization
- Bayesian weight estimation
- Explainable AI for investment recommendations
- Interactive Streamlit dashboard

---

## Author

**Debadatta Panda**

M.Tech – Industrial Mathematics and Scientific Computing

Indian Institute of Technology Madras

GitHub:
https://github.com/DebadattaLiku

---

