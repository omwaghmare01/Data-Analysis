# Week 3: Statistical Analysis and Hypothesis Testing

## 📌 Project Overview

This project is part of the **Virtual Data Science with Python Apprentice Internship**.  
The objective of Week 3 is to perform statistical analysis and hypothesis testing using Python on the cleaned Titanic passenger dataset.

The analysis focuses on validating observed patterns through statistical tests rather than relying only on descriptive statistics and visualizations.

---

## 🎯 Objectives

- Formulate clear and testable hypotheses.
- Perform statistical analysis using Python.
- Apply appropriate hypothesis testing techniques.
- Interpret p-values and statistical significance.
- Calculate and interpret a 95% confidence interval.
- Support statistical findings with visualizations.
- Communicate analytical results in a clear and structured manner.

---

## 📊 Dataset

The project uses the **Titanic passenger dataset**, which contains information about passengers including:

- Passenger survival status
- Gender
- Age
- Passenger class
- Fare
- Number of siblings/spouses
- Number of parents/children
- Embarkation information

The cleaned dataset prepared during Week 1 is used for the statistical analysis.

---

## 🔬 Research Questions

### 1. Gender and Survival

**Research Question:**  
Does passenger gender have a statistically significant relationship with survival on the Titanic?

**Null Hypothesis (H₀):**  
Gender and survival are independent.

**Alternative Hypothesis (H₁):**  
Gender and survival are not independent.

**Statistical Test:**  
Chi-Square Test of Independence

---

### 2. Age and Survival

**Research Question:**  
Is the average age significantly different between passengers who survived and passengers who did not survive?

**Null Hypothesis (H₀):**  
The mean age of survivors and non-survivors is equal.

**Alternative Hypothesis (H₁):**  
The mean age of survivors and non-survivors is different.

**Statistical Test:**  
Independent Two-Sample Welch's T-Test

---

## 🧪 Statistical Methodology

A significance level of **α = 0.05** was used.

The following statistical techniques were applied:

1. **Chi-Square Test of Independence**
   - Used to examine the relationship between two categorical variables.
   - Variables: `sex` and `survived`

2. **Welch's Independent Two-Sample T-Test**
   - Used to compare the mean age of two independent groups.
   - Groups: survivors and non-survivors

3. **95% Confidence Interval**
   - Used to estimate the plausible range for the difference in mean age between the two groups.

### P-Value Decision Rule

- If **p-value < 0.05**, reject H₀.
- If **p-value ≥ 0.05**, fail to reject H₀.

---

## 📈 Visualizations

The project includes visualizations to support the statistical analysis:

- Survival distribution by gender
- Observed survival counts by gender
- Age distribution by survival status
- Age distribution using histogram and density visualization

These visualizations provide an intuitive understanding of the data before interpreting the statistical test results.

---

## 🛠️ Technologies Used

- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **SciPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📂 Project Structure

```text
Week 3/
│
├── Week_3_Statistical_Analysis_Hypothesis_Testing.ipynb
├── Week_3_Statistical_Analysis_and_Hypothesis_Testing_Report.docx
└── README.md
