# Hypothesis Testing with T‑Test & ANOVA

This repository demonstrates how to perform hypothesis testing using **T‑tests** and **ANOVA** in Python, leveraging popular libraries like **SciPy**, **Statsmodels**, and **Pingouin**.

---

## 📘 Table of Contents

1. [Overview](#overview)  
2. [Key Concepts](#key-concepts)  
3. [Tools & Installation](#tools--installation)  
4. [Usage Examples](#usage-examples)  
   - Independent T‑Test  
   - Paired T‑Test  
   - One‑way ANOVA  
5. [Interpretation of Results](#interpretation-of-results)  
6. [Common Use Cases](#common-use-cases)  
7. [Contributing](#contributing)  
8. [References & Further Reading](#references--further-reading)  
9. [License](#license)

---

## Overview

Hypothesis testing helps us determine whether observed differences in sample data are statistically significant.  
This repo shows how to conduct:

- **T‑tests** for comparing means between two groups  
- **ANOVA** for comparing means across three or more groups

---

## Key Concepts

- **Null Hypothesis (H₀)**: No difference between group means  
- **Alternative Hypothesis (H₁)**: A difference exists  
- **P‑value**: Probability of observing your data if H₀ were true  
- **Alpha (α)**: Significance level (commonly 0.05)  
- **Statistically significant**: p-value < α

---

## Tools & Installation

Make sure you have:

- Python 3.7+  
- pip

Install dependencies:

```bash
pip install scipy statsmodels pingouin pandas numpy
