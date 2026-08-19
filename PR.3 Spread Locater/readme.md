# 📊 PR-3 | Spread Locator

<p align="center">
  <strong>Mathematics & Advanced Statistics</strong><br>
  Statistical Distribution Analysis Model
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Analysis-013243?logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/SciPy-Statistics-8CAAE6?logo=scipy&logoColor=white">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white">
</p>

---

## 👨‍💻 Author

**Prince Vaghasiya**

**Subject:** Mathematics & Advanced Statistics  
**Practical:** PR-3 – Spread Locator

---

## 🧭 Quick Navigation

- [📌 Overview](#-overview)
- [🎯 Objective](#-objective)
- [🗃️ Dataset](#️-dataset)
- [📖 Part A — Theory](#-part-a--theory)
- [🧪 Part B — Practical](#-part-b--practical)
- [📐 Statistical Concepts Used](#-statistical-concepts-used)
- [🔄 Analysis Workflow](#-analysis-workflow)
- [🛠️ Technologies](#️-technologies)
- [🚀 How to Run](#-how-to-run)
- [📁 Project Structure](#-project-structure)
- [🎓 Learning Outcomes](#-learning-outcomes)
- [🏁 Conclusion](#-conclusion)

---

# 📌 Overview

**Spread Locator: A Statistical Distribution Analysis Model** is a Mathematics & Advanced Statistics project based on probability distributions and spread analysis.

The project uses customer transaction data from an e-commerce scenario to study transaction occurrence, transaction counts, daily transaction amounts, skewed data, probability behaviour, and suitable statistical distributions.

---

# 🎯 Objective

The main objective is to understand and apply statistical distribution concepts to transaction data.

The project focuses on:

- Understanding probability distributions.
- Fitting transaction data to suitable distributions.
- Comparing discrete and continuous distributions.
- Studying skewed transaction amounts.
- Using Q-Q plots for normality analysis.
- Applying the Box-Cox transformation.
- Calculating Z-scores and probabilities.
- Understanding PDF and CDF.
- Selecting a suitable distribution based on the analysis.

---

# 🗃️ Dataset

The project scenario is based on an e-commerce platform analyzing customer purchase behaviour and daily transaction amounts.

| Field | Description |
|---|---|
| `transaction_id` | Unique identifier for each transaction |
| `customer_id` | Unique identifier for each customer |
| `transaction_amount` | Total amount of the transaction |
| `transaction_date` | Date of the transaction |
| `transaction_count` | Number of transactions made by a customer in a given week |
| `region` | Customer's geographic region |
| `transaction_status` | Whether the transaction was successful or failed |

---

# 📖 Part A — Theory

The theory section covers:

| No. | Topic |
|---:|---|
| 1 | Statistical Distribution |
| 2 | Q-Q Plot |
| 3 | Discrete and Continuous Distributions |
| 4 | Bernoulli Distribution |
| 5 | Binomial Distribution |
| 6 | Log-Normal Distribution |
| 7 | Power Law Distribution |
| 8 | Box-Cox Transform |
| 9 | Poisson Distribution |
| 10 | Z-score Probability |
| 11 | PDF and CDF |

---

# 🧪 Part B — Practical

The notebook implements the required statistical analysis.

### Bernoulli Distribution
Used for binary transaction occurrence or success/failure outcomes.

### Binomial Distribution
Used to analyze weekly transaction counts over a fixed number of trials.

### Poisson Distribution
Used to model the number of transactions occurring per day.

### Log-Normal Distribution
Used to model positive and potentially right-skewed transaction amounts.

### Power Law Distribution
Used to examine possible heavy-tailed behaviour in transaction amounts.

### Q-Q Plot
Used to compare transaction amounts with a theoretical normal distribution and inspect normality.

### Box-Cox Transformation
Applied to transaction amounts to reduce skewness and stabilize variance.

### Z-score and ₹5,000 Probability
Z-scores are calculated and the probability of transactions exceeding **₹5,000** is analyzed.

### PDF and CDF
Both probability density and cumulative probability are plotted for transaction amounts.

### Final Distribution Judgement
The final judgement is based on the statistical calculations, plots and observed transaction behaviour.

---

# 📐 Statistical Concepts Used

| Concept | Application |
|---|---|
| **Bernoulli** | Transaction occurrence |
| **Binomial** | Weekly transaction count |
| **Poisson** | Transactions per day |
| **Log-Normal** | Transaction amounts |
| **Power Law** | Heavy-tailed behaviour |
| **Q-Q Plot** | Normality checking |
| **Box-Cox** | Data transformation |
| **Z-score** | Standardized values |
| **PDF** | Probability density |
| **CDF** | Cumulative probability |

---

# 🔄 Analysis Workflow

```text
Transaction Dataset
        ↓
Data Inspection
        ↓
Bernoulli / Binomial
        ↓
Poisson
        ↓
Transaction Amount Analysis
        ↓
Log-Normal / Power Law
        ↓
Q-Q Plot
        ↓
Box-Cox Transformation
        ↓
Z-score & ₹5,000 Probability
        ↓
PDF & CDF
        ↓
Final Distribution Judgement
```

---

# 🛠️ Technologies

- **Python** — main programming language
- **NumPy** — numerical calculations
- **Pandas** — data handling and analysis
- **SciPy** — statistical distributions and calculations
- **Matplotlib** — charts and visualizations
- **Jupyter Notebook** — practical implementation

---

# 🚀 How to Run

### Install dependencies

```bash
pip install numpy pandas scipy matplotlib seaborn statsmodels jupyter
```

### Start Jupyter

```bash
jupyter notebook
```

Open:

```text
PR3_Spread_Locator.ipynb
```

Run the notebook cells from top to bottom.

---

# 📁 Project Structure

```text
PR-3-Spread-Locator/
│
├── README.md
├── PR3_Spread_Locator.ipynb
├── spread_locator_dataset.csv
│
└── Theory/
    └── Part-A-Theory.pdf
```

---

# 🎓 Learning Outcomes

Through this project, I practiced:

- Understanding statistical distributions.
- Differentiating discrete and continuous distributions.
- Applying Bernoulli, Binomial and Poisson models.
- Understanding Log-Normal and Power Law behaviour.
- Interpreting Q-Q plots.
- Applying Box-Cox transformation.
- Calculating Z-scores and probabilities.
- Understanding PDF and CDF.
- Comparing theoretical distributions with observed data.
- Using Python for statistical analysis.
- Making a distribution-based judgement.

---

# 🏁 Conclusion

**PR-3 – Spread Locator** demonstrates how probability distributions can be applied to transaction data.

The project combines theory with Python-based practical analysis. Distribution fitting, normality checking, transformation, probability calculations and PDF/CDF analysis are used to understand the behaviour of transaction amounts.

The final judgement is based on the statistical results and visual evidence produced by the analysis.

---

<p align="center">
  <strong>📊 PR-3 | SPREAD LOCATOR</strong><br>
  <em>Probability • Distributions • Data Analysis • Statistics</em>
</p>
