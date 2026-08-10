# 📊 PR. 2 – Derivable Judgement

> **Mathematics & Advanced Statistics**  
> Statistical analysis and hypothesis testing using Python.

**Author:** Prince Vaghasiya

---

## 📌 About the Project

This project applies **inferential statistics** to a synthetic health-record dataset. It combines the theoretical concepts from Part A with practical statistical analysis in Python.

The main focus is on using sample data to make statistical decisions through **confidence intervals, hypothesis testing, p-values, critical values, t-test, chi-square test, ANOVA, covariance and correlation**.

---

## 🎯 Objectives

- Understand inferential statistics and hypothesis testing.
- Formulate null and alternative hypotheses.
- Calculate a confidence interval.
- Use p-values and critical values for statistical decisions.
- Perform t-test, chi-square test and ANOVA.
- Calculate covariance and correlation.
- Visualize and interpret the results.

---

## 📖 Part A – Theoretical Foundation

The theory section covers the eight topics required in the assignment:

1. **Inferential Statistics**
2. **Hypothesis Testing and its Components**
3. **Confidence Interval and Critical Value**
4. **p-value**
5. **Type I and Type II Errors**
6. **z-test, t-test, Chi-square Test and ANOVA**
7. **Covariance**
8. **Correlation**

The handwritten theory pages are included in the repository under `screenshots/`.

<details>
<summary>📖 View Theory Screenshots</summary>

### Theory – Page 1

![Theory Page 1](<img width="1200" height="1600" alt="Image 1" src="https://github.com/user-attachments/assets/42e956f5-2a36-4094-b38e-5e81a22e05ff" />)

### Theory – Page 2

![Theory Page 2](screenshots/theory-page-2.jpeg)

</details>

---

## 🧪 Part B – Practical Analysis

The practical uses a **synthetically generated dataset of 1,000 health records**.

### Dataset Variables

| Variable | Description |
|---|---|
| `record_id` | Unique record ID |
| `age_group` | Age category |
| `age` | Age |
| `weight` | Weight |
| `gender` | Gender |
| `region` | Region |
| `smoking_status` | Smoking category |
| `exercise_frequency` | Exercise frequency |
| `bmi` | Body Mass Index |
| `blood_pressure` | Blood pressure |
| `diabetes` | Diabetes indicator |
| `hypertension` | Hypertension indicator |
| `cholesterol_level` | Cholesterol level |
| `glucose_level` | Glucose level |
| `visit_date` | Visit date |

---

## 🧠 Hypotheses

### 1. Smoking Status vs Diabetes

**H₀:** Smoking status has no significant association with diabetes.

**H₁:** Smoking status has a significant association with diabetes.

**Test:** Chi-square test of independence.

### 2. Age Groups vs Diabetes

**H₀:** There is no significant difference in diabetes rate among age groups.

**H₁:** At least one age group has a different diabetes rate.

**Test:** One-way ANOVA.

### 3. BMI of Smokers vs Non-Smokers

**H₀:** Mean BMI is equal for smokers and non-smokers.

**H₁:** Mean BMI is different for smokers and non-smokers.

**Test:** Independent two-sample Welch t-test.

---

## 📐 Statistical Methods

| Method | Purpose |
|---|---|
| **95% Confidence Interval** | Estimate mean age |
| **Welch t-test** | Compare BMI between two groups |
| **Chi-square Test** | Test smoking status and diabetes association |
| **ANOVA** | Compare diabetes rates across age groups |
| **Covariance** | Study direction of co-movement |
| **Correlation** | Measure strength and direction of linear relationship |

---

## ⚖️ Decision Rule

The practical uses a **5% significance level**:

```text
α = 0.05
```

The main rule is:

```text
p-value < 0.05  →  Reject H₀
p-value ≥ 0.05  →  Fail to reject H₀
```

Critical values are also calculated where applicable and compared with the test statistic.

---

## 📊 Visualizations

The practical contains three main graphs.

### Diabetes Rate by Age Group

This graph compares the diabetes rate across different age groups.

![Diabetes Rate by Age Group](screenshots/practical-page-1.png)

### Smoking Status vs Diabetes

This graph shows the number of diabetes and non-diabetes records for each smoking-status group.

![Smoking Status vs Diabetes](screenshots/practical-page-2.png)

### Age vs BMI

This scatter plot shows the relationship between age and BMI.

![Age vs BMI](screenshots/practical-page-3.png)

---

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **NumPy**
- **Pandas**
- **SciPy**
- **Matplotlib**

### Libraries

```python
import numpy as np
import pandas as pd
from scipy import stats
import matplotlib.pyplot as plt
```

---

## ▶️ How to Run

### 1. Install Python

Make sure Python 3.x is installed.

### 2. Install the required libraries

```bash
pip install numpy pandas scipy matplotlib jupyter
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the notebook

```text
PR2_PartB_Derivable_Judgement_Humanized.ipynb
```

Run the cells from top to bottom.

The notebook generates the health dataset and performs all the statistical calculations.

---

## 📂 Project Structure

```text
PR-2-Derivable-Judgement/
│
├── README.md
├── PR2_PartB_Derivable_Judgement_Humanized.ipynb
├── health_records_dataset.csv
│
└── screenshots/
    ├── theory-page-1.jpeg
    ├── theory-page-2.jpeg
    ├── practical-page-1.png
    ├── practical-page-2.png
    └── practical-page-3.png
```

---

## 📈 Analysis Flow

```text
Health Dataset
      ↓
Data Generation
      ↓
Hypothesis Formulation
      ↓
Confidence Interval
      ↓
t-test / Chi-square / ANOVA
      ↓
Covariance & Correlation
      ↓
p-value & Critical Value
      ↓
Statistical Decision
      ↓
Interpretation
```

---

## 🎓 Learning Outcomes

Through this project, I practiced:

- Working with statistical data in Python.
- Formulating hypotheses.
- Understanding p-values and significance levels.
- Calculating confidence intervals.
- Performing common statistical tests.
- Interpreting statistical results.
- Using graphs to understand data.
- Applying mathematics and statistics concepts to a practical dataset.

---

## ⚠️ Note

The health dataset used in this project is **synthetically generated for educational purposes**. The results are specific to this dataset and should not be treated as medical conclusions about a real population.

---

## 🏁 Conclusion

This project demonstrates how inferential statistics can be applied to sample data to make structured statistical judgements.

The practical connects the theoretical concepts from Part A with Python-based analysis in Part B and shows how statistical tests, probability values and visualizations can be used to understand data and support decisions.

---

## 👨‍💻 Author

**Prince Vaghasiya**

**PR. 2 – Derivable Judgement**  
**Mathematics & Advanced Statistics**

---

<p align="center">
  <b>Data → Analysis → Evidence → Statistical Judgement</b>
</p>
