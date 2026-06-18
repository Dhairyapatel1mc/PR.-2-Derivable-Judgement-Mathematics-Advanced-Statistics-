<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=220&section=header&text=Derivable%20Judgement&fontSize=52&fontAlignY=38&desc=A%20Statistical%20Decision-Making%20Model&descAlignY=58&descSize=20&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-4DABCF?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-2D7D7D?style=flat-square"/>
  <img src="https://img.shields.io/badge/Course-Mathematics%20%26%20Advanced%20Statistics-C9A84C?style=flat-square"/>
  <img src="https://img.shields.io/badge/Institute-Red%20%26%20White%20Skill%20Education-A0394A?style=flat-square"/>
</p>

<p align="center">
  <a href="https://github.com/Dhairyapatel1mc"><img src="https://skillicons.dev/icons?i=github" height="40"/></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/ghost-patel-0267663b7/"><img src="https://skillicons.dev/icons?i=linkedin" height="40"/></a>
  &nbsp;
  <a href="https://www.instagram.com/ghost_6927/?hl=en"><img src="https://skillicons.dev/icons?i=instagram" height="40"/></a>
</p>

---

## 📑 Table of Contents

<table>
<tr>
<td valign="top" width="65%">

- [📌 Project Overview](#-project-overview)
- [🎯 Project Objectives](#-project-objectives)
- [✨ Features](#-features)
- [🗂️ Dataset Structure](#️-dataset-structure)
- [📁 Project Structure](#-project-structure)
- [📖 Part A — Theory and Concepts](#-part-a--theory-and-concepts)
- [🔬 Part B — Analysis Tasks](#-part-b--analysis-tasks)
- [📊 Key Results](#-key-results)
- [🛠️ Technologies Used](#️-technologies-used)
- [⚙️ Installation](#️-installation)
- [▶️ How to Run](#️-how-to-run)
- [🏆 Learning Outcomes](#-learning-outcomes)
- [🚀 Future Improvements](#-future-improvements)
- [👤 Author](#-author)
- [⭐ Support](#-support)

</td>
<td valign="top" align="center" width="35%">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="280"/>

</td>
</tr>
</table>

---

## 📌 Project Overview

> 💬 You are a **data analyst at a public health research organization**. Given health records of 500 individuals categorized by gender, age groups, lifestyle habits, and diagnosed diseases — your task is to use **pure classical statistics** (no Machine Learning) to derive judgements about factors affecting disease occurrence.

- 🏥 **Domain** — Public Health and Epidemiology
- 👥 **Dataset Size** — 500 synthetic health records · 15 fields
- 🚫 **No Machine Learning** — 100% classical inferential statistics
- 🧪 **Tests Performed** — Z-Test · T-Test · Chi-Square · ANOVA · Correlation
- 🏫 **Institute** — Red and White Skill Education
- ⏱️ **Duration** — 6 Hours (Theory + Practical)

---

## 🎯 Project Objectives

- 📌 Apply **inferential statistics** to evaluate multiple hypotheses on a health dataset
- 📌 Demonstrate **theoretical understanding** through short notes with infographic visuals
- 📌 Perform **hypothesis testing** using z-test, t-test, chi-square, and ANOVA
- 📌 Compute and interpret **confidence intervals** and critical values
- 📌 Analyse **covariance and correlation** between continuous health variables
- 📌 Make clear **Accept / Reject H₀ decisions** with written interpretation for every test

---

## ✨ Features

| ✅ Feature | 📝 Description |
|-----------|---------------|
| 🤖 **AI-Generated Dataset** | 500-row synthetic dataset with realistic distributions via NumPy |
| 📖 **Theory + Practical Split** | Part A (notes + diagrams) and Part B (Python analysis) as separate notebooks |
| 🖼️ **Infographic Visuals** | 8 custom classic-styled diagrams for all Part A concepts |
| 🧪 **5 Statistical Tests** | Z-Test, T-Test, Chi-Square, One-Way ANOVA, Pearson Correlation |
| 📊 **Confidence Intervals** | 95% CI for Age, Weight, BMI, Blood Pressure, Cholesterol, Glucose |
| 📋 **Summary Table** | Final Accept/Reject H₀ decision table covering all tests |
| 📦 **CSV Export** | Dataset available as `health_data.csv` for independent use |

---

## 🗂️ Dataset Structure

| 🏷️ Field | 🔢 Type | 📝 Description |
|---------|--------|---------------|
| 🆔 `record_id` | String | Unique UUID identifier |
| 👶 `age` | Int | Age of the individual |
| 🗂️ `age_group` | String | 18-25 · 26-35 · 36-45 · 46-60 · 60+ |
| ⚖️ `weight` | Float | Weight in kg |
| 🚻 `gender` | String | Male / Female / Other |
| 🗺️ `region` | String | North / South / East / West |
| 🚬 `smoking_status` | String | Smoker / Non-Smoker / Former Smoker |
| 🏃 `exercise_frequency` | String | Daily / Weekly / Rarely / Never |
| 📐 `bmi` | Float | Body Mass Index |
| 💉 `blood_pressure` | Float | Systolic blood pressure (mmHg) |
| 🩸 `diabetes` | Boolean | True / False |
| 🫀 `hypertension` | Boolean | True / False |
| 🧪 `cholesterol_level` | Float | Total cholesterol (mg/dL) |
| 🍬 `glucose_level` | Float | Fasting glucose (mg/dL) |
| 📅 `visit_date` | Date | Date of health check-up |

---

## 📁 Project Structure

```
📦 Derivable-Judgement/
│
├── 📓 derivable_judgement_Part_A.ipynb   ← Theory notes + infographic diagrams
├── 📓 derivable_judgement_Part_B.ipynb   ← Data analysis + statistical tests
├── 📊 health_data.csv                    ← Synthetic health dataset (500 rows)
└── 📄 README.md                          ← Project documentation
```

---

## 📖 Part A — Theory and Concepts

> 💬 All 8 concepts include a plain-language explanation, mathematical formula, and custom infographic diagram. Zero code in Part A — pure theory only.

---

### 1️⃣ Inferential Statistics

> 💬 Instead of surveying every person in a country, we survey 500 people and use mathematics to draw conclusions about everyone. That is inferential statistics — making big conclusions from small samples.

$$\bar{x} \xrightarrow{\text{inference}} \mu \qquad s \xrightarrow{\text{inference}} \sigma$$

| 📊 Descriptive | 🔬 Inferential |
|---------------|---------------|
| Summarizes observed data | Makes predictions about population |
| Mean, median, std dev | Hypothesis tests, confidence intervals |
| No uncertainty | Uses probability and confidence levels |

---

### 2️⃣ Hypothesis Testing

> 💬 Before doing an experiment, you make a claim like "smoking has no effect on diabetes." Then you collect data and use math to check — is your claim believable, or should you reject it?

$$\text{Reject } H_0 \iff p\text{-value} < \alpha$$

| 🧩 Component | 📝 Meaning | 💡 Example |
|-------------|-----------|-----------|
| 🎯 **H₀ (Null)** | Default claim — no effect | Smoking has NO effect on diabetes |
| 🔍 **H₁ (Alternative)** | What we want to prove | Smoking DOES affect diabetes |
| 📐 **Test Statistic** | Computed value from sample | z = 2.45 |
| ⚖️ **Alpha (α)** | Threshold for rejection | 0.05 (5%) |
| 📉 **P-value** | Prob of result under H₀ | p = 0.01 |
| ✅ **Decision** | Reject H₀ if p < α | 0.01 < 0.05 → Reject H₀ |

---

### 3️⃣ Confidence Interval and Critical Value

> 💬 A 95% CI means: if you repeated this experiment 100 times, 95 of your intervals would contain the true population value.

$$CI = \bar{x} \pm z^* \times \frac{\sigma}{\sqrt{n}}$$

| 🎯 Confidence Level | 🔢 Critical Value z* |
|--------------------|---------------------|
| 90% | ±1.645 |
| **95%** | **±1.96** |
| 99% | ±2.576 |

---

### 4️⃣ P-Value

> 💬 The p-value asks — if H₀ were really true, how surprising would my data be? A tiny p-value (like 0.002) means your data is very surprising under H₀, so you reject it.

| 📉 P-value | ✅ Decision |
|-----------|-----------|
| p < 0.05 | **Reject H₀** — Statistically significant |
| p ≥ 0.05 | **Fail to Reject H₀** — Not enough evidence |

---

### 5️⃣ Type I and Type II Errors

> 💬 Type I = fire alarm going off when there is no fire. Type II = alarm staying silent during a real fire. Both are bad — you reduce both by increasing sample size.

$$P(\text{Type I}) = \alpha \qquad P(\text{Type II}) = \beta \qquad \text{Power} = 1 - \beta$$

| | H₀ TRUE | H₀ FALSE |
|---|---|---|
| **Reject H₀** | ❌ Type I Error (α) | ✅ Correct — Power (1−β) |
| **Fail to Reject** | ✅ Correct (1−α) | ❌ Type II Error (β) |

---

### 6️⃣ Statistical Tests

> 💬 Different situations need different tools. Z-test for big samples, T-test for small samples, Chi-Square for category links, ANOVA to compare multiple groups.

| 🧪 Test | 📋 When | 📐 Formula | 🔍 Used For |
|--------|---------|-----------|-----------|
| **Z-Test** | n > 30, σ known | $z = \frac{\bar{x} - \mu}{\sigma/\sqrt{n}}$ | BMI: Diabetic vs Non-Diabetic |
| **T-Test** | n < 30 or σ unknown | $t = \frac{\bar{x}_1 - \bar{x}_2}{s_p\sqrt{1/n_1+1/n_2}}$ | BMI: Diabetic vs Non-Diabetic |
| **Chi-Square** | Categorical data | $\chi^2 = \sum \frac{(O-E)^2}{E}$ | Smoking vs Diabetes |
| **ANOVA** | 3+ group means | $F = \frac{\text{Between}}{\text{Within}}$ | BP across Age Groups |

---

### 7️⃣ Covariance

> 💬 Covariance asks: when one variable goes up, does the other go up too? If you exercise more and weight goes down — that is negative covariance.

$$Cov(X,Y) = \frac{\sum_{i=1}^{n}(X_i - \bar{X})(Y_i - \bar{Y})}{n-1}$$

| 📈 Value | 💡 Meaning |
|---------|-----------|
| Cov > 0 | Both variables increase together |
| Cov < 0 | One increases, other decreases |
| Cov ≈ 0 | No consistent linear relationship |

---

### 8️⃣ Correlation

> 💬 Correlation is covariance with the units removed. It always stays between -1 and +1, making it easy to compare across any two variables.

$$r = \frac{Cov(X,Y)}{\sigma_X \times \sigma_Y} \qquad -1 \leq r \leq +1$$

| 📊 r Value | 🔍 Interpretation |
|-----------|-----------------|
| r = ±1.0 | Perfect linear relationship |
| ±0.7 to ±1.0 | Strong |
| ±0.3 to ±0.7 | Moderate |
| −0.3 to +0.3 | Weak or none |

---

## 🔬 Part B — Analysis Tasks

| # | 🧪 Task | 🛠️ Method | 📋 Hypothesis Tested |
|---|--------|----------|---------------------|
| 1️⃣ | Hypothesis Formulation | Manual statement | 3 hypotheses defined |
| 2️⃣ | Confidence Intervals | `scipy.stats.norm.ppf` | 95% CI for 5 variables |
| 3️⃣ | Critical Values | `scipy.stats` | Z · T · Chi² · F |
| 4️⃣ | Z-Test and T-Test | Manual + `ttest_ind` | BMI: Diabetic vs Non-Diabetic |
| 5️⃣ | Chi-Square Test | `chi2_contingency` | Smoking vs Diabetes |
| 6️⃣ | One-Way ANOVA | `f_oneway` | Blood Pressure across Age Groups |
| 7️⃣ | Covariance and Correlation | Manual + `pearsonr` | Age vs BMI |
| 8️⃣ | Summary Table | Print formatting | Accept / Reject H₀ for all tests |

---

## 📊 Key Results

| 🧪 Test | 📐 Statistic | 📉 P-Value | ✅ Decision |
|--------|------------|-----------|-----------|
| 🔬 Z-Test — BMI (Diabetic vs Non-Diabetic) | ~3.80 | < 0.001 | ✅ **REJECT H₀** |
| 🔬 T-Test — BMI (Diabetic vs Non-Diabetic) | ~3.80 | < 0.001 | ✅ **REJECT H₀** |
| 📊 Chi-Square — Smoking vs Diabetes | ~18.4 | < 0.001 | ✅ **REJECT H₀** |
| 📈 ANOVA — Blood Pressure across Age Groups | ~22.1 | < 0.001 | ✅ **REJECT H₀** |
| 🔗 Pearson r — Age vs BMI | ~0.15 | < 0.05 | ✅ **Significant** |

> 💬 **Key Findings:**
> - 🩸 Diabetic individuals have **significantly higher BMI** than non-diabetic ones
> - 🚬 Smoking status is **statistically associated** with Diabetes prevalence
> - 💓 Blood pressure **increases significantly** with age across all 5 groups
> - 📐 Age and BMI have a **weak positive correlation**

---

## 🛠️ Technologies Used

| 🔧 Tool | 📝 Purpose |
|--------|-----------|
| 🐍 **Python 3.x** | Core programming language |
| 📓 **Jupyter Notebook** | Interactive development and presentation |
| 🔢 **NumPy** | Dataset generation and mathematical operations |
| 🐼 **Pandas** | Data manipulation, crosstab, groupby |
| 🔬 **SciPy** | Z-test, T-test, Chi-Square, ANOVA, Pearson r |
| 📊 **Matplotlib** | Charts and infographic diagrams |

---

## ⚙️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/Dhairyapatel1mc/Derivable-Judgement.git
cd Derivable-Judgement

# 2. Install required libraries
pip install numpy pandas scipy matplotlib jupyter
```

---

## ▶️ How to Run

```bash
# Open Part A — Theory
jupyter notebook derivable_judgement_Part_A.ipynb

# Open Part B — Analysis
jupyter notebook derivable_judgement_Part_B.ipynb
```

> 💬 The dataset is generated automatically in the first code cell. The `health_data.csv` file is also included for independent use.

---

## 🏆 Learning Outcomes

- 🎯 Understood the difference between **descriptive and inferential statistics**
- 📐 Learned to compute and interpret **confidence intervals** and **critical values**
- 🧪 Applied **four different statistical tests** to real-world-style health data
- 📊 Performed **chi-square analysis** using a contingency table
- 🔗 Computed **covariance and Pearson correlation** both manually and via SciPy
- 🖼️ Designed **professional infographic diagrams** using Matplotlib
- 📋 Made clear **Accept / Reject H₀ decisions** with written interpretation

---

## 🚀 Future Improvements

- 🔮 Add **logistic regression** to predict diabetes probability from health features
- 🗺️ Include **region-wise analysis** with grouped chi-square tests
- 📡 Connect to a **real public health dataset** (WHO, CDC)
- 📱 Build a **Streamlit dashboard** for interactive hypothesis testing
- 🔁 Add **post-hoc Tukey HSD tests** after ANOVA for pairwise comparisons
- 📦 Package as a **reusable statistical analysis module**

---

## 👤 Author

<table>
<tr>
<td>

**Ghost (Patel Dhairya)**
- 🎓 B.Tech Artificial Intelligence — Gandhinagar University
- 🏫 Red and White Skill Education (RWSkill)
- 🔢 Roll No. — **250101030119**
- 💻 GitHub — [@Dhairyapatel1mc](https://github.com/Dhairyapatel1mc)
- 💼 LinkedIn — [ghost-patel](https://www.linkedin.com/in/ghost-patel-0267663b7/)
- 📸 Instagram — [@ghost_6927](https://www.instagram.com/ghost_6927/?hl=en)

</td>
<td>

<p align="center">
  <a href="https://github.com/Dhairyapatel1mc"><img src="https://skillicons.dev/icons?i=github" height="45"/></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/ghost-patel-0267663b7/"><img src="https://skillicons.dev/icons?i=linkedin" height="45"/></a>
  &nbsp;
  <a href="https://www.instagram.com/ghost_6927/?hl=en"><img src="https://skillicons.dev/icons?i=instagram" height="45"/></a>
</p>

</td>
</tr>
</table>

---

## ⭐ Support

If this project helped you:

- ⭐ **Star** this repository
- 🍴 **Fork** it and adapt it for your own dataset
- 📤 **Share** it with your classmates
- 💬 **Open an Issue** for suggestions or bugs

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=120&section=footer" width="100%"/>
</p>

<p align="center">
  <b>Red and White Skill Education — "Quality is our Motto."</b><br/>
  <i>Shaping skills for scaling higher...!!!</i><br/><br/>
  Made with ❤️ by <a href="https://github.com/Dhairyapatel1mc">Ghost (Patel Dhairya)</a>
</p>
