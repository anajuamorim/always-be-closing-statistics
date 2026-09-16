<div align="center">

# Always Be Closing — Statistical Analysis

### From hypothesis testing to data-driven lead segmentation

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistics-Hypothesis%20Testing-6A5ACD?style=for-the-badge)

</div>

## About the project

**Always Be Closing** is a statistics and hypothesis-testing case developed in the context of Data Science studies at FIAP.

The challenge connects statistical reasoning with a commercial decision: instead of selecting leads only by intuition, the analysis explores historical data to build reproducible segmentation rules and support prospecting decisions with evidence.

The central lesson is that **statistical significance alone is not enough**. A segment may show an interesting statistical pattern and still be too small, economically weak, or highly contested to be useful in practice.

## Business problem

The scenario simulates teams competing for leads in a shared market. Prospecting decisions therefore need to consider more than a single metric.

A useful segment should combine:

- statistical evidence;
- sufficient lead volume;
- reproducible filtering rules;
- economic relevance;
- awareness of competition and possible lead overlap.

This turns hypothesis testing into a decision-support tool rather than an isolated academic exercise.

## Statistical toolkit

The activity supports the use of:

| Technique | Purpose |
|---|---|
| Descriptive statistics | Understand distributions, central tendency and variability |
| Exploratory visualization | Identify patterns and differences between groups |
| Independent t-test | Compare means when its assumptions are appropriate |
| Mann–Whitney U test | Compare independent groups when a non-parametric approach is more appropriate |
| Segmentation with Pandas | Translate analytical findings into reproducible business rules |

## Analytical workflow

```text
Historical Lead Data
        ↓
Data Exploration
        ↓
Descriptive Statistics
        ↓
Business Hypothesis
        ↓
Statistical Comparison
        ↓
Interpretation of Evidence
        ↓
Lead Segmentation Rule
        ↓
Volume & Economic Validation
        ↓
Prospecting Decision
```

## Decision logic

The project follows an important distinction:

> **Statistically significant ≠ automatically valuable for the business.**

After a statistical comparison, the result still needs to be evaluated in context. A narrow segment can have a strong observed difference but contain too few leads to generate meaningful commercial impact.

The final decision therefore combines **statistics + market volume + business constraints**.

## Repository structure

```text
always-be-closing-statistics/
├── README.md
├── data/
├── notebooks/
├── src/
└── docs/
```

The repository will be expanded progressively with the analytical materials used in the case. Results will only be documented when they can be reproduced from the corresponding data and analysis.

## Tools

- **Python** — analytical programming
- **Pandas** — data manipulation, filtering and grouping
- **SciPy** — statistical hypothesis testing
- **Matplotlib** — exploratory visualization
- **Jupyter Notebook** — documented analytical workflow
- **Git & GitHub** — version control and project documentation

## What this project demonstrates

This case is designed to demonstrate the ability to:

- translate a business question into a statistical hypothesis;
- explore and segment tabular data with Python;
- choose an appropriate statistical comparison;
- interpret statistical evidence without reducing the decision to a p-value;
- transform analytical findings into reproducible filtering rules;
- communicate the limitations between statistical and economic relevance.

## Project status

**In development.**

The project structure and methodology are documented. Analytical code, datasets and numerical results will be added only when they are available and reproducible.

---

<div align="center">

Developed by **Ana Julia Amorim**  
Data Science Student @ FIAP

[GitHub](https://github.com/anajuamorim) · [LinkedIn](https://www.linkedin.com/in/ana-julia-amorim-4808a12a5)

</div>
