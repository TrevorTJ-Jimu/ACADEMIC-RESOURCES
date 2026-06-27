<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:75AADB,100:2E86AB&height=180&section=header&text=RStudio%20%26%20R&fontSize=50&fontColor=ffffff&fontAlignY=40&desc=Open-Source%20Statistical%20Computing%20%26%20Data%20Visualisation&descAlignY=60&descSize=16&descColor=daf0ff&animation=fadeIn" />

[![R](https://img.shields.io/badge/Language-R-276DC3?style=for-the-badge&logo=r&logoColor=white)]()
[![RStudio](https://img.shields.io/badge/IDE-RStudio-75AADB?style=for-the-badge&logo=rstudio&logoColor=white)]()
[![License](https://img.shields.io/badge/License-Open%20Source-38ef7d?style=for-the-badge)]()
[![Tutor](https://img.shields.io/badge/Tutor-Trevor%20Jimu-2E86AB?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TrevorTJ-Jimu)

<img src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" width="260" alt="R programming"/>

</div>

---

## 📌 Overview

**R** is the leading open-source language for statistical computing and data science. **RStudio** provides a professional IDE for writing R code, creating reports, and building reproducible analyses. This folder covers R from fundamentals to advanced statistical modelling.

---

## 🗂️ Contents

| Folder | Description |
|--------|-------------|
| `notes/` | R scripts, tutorials and R Markdown guides |
| `exercises/` | Datasets and analysis tasks |
| `solutions/` | Full R scripts with annotated output |

---

## 🧭 Topics Covered

- [ ] R Basics: Vectors, Data Frames, Functions, Loops
- [ ] Data Import/Export: `read.csv`, `readxl`, `haven`
- [ ] Data Wrangling with `dplyr` & `tidyr`
- [ ] Descriptive Statistics
- [ ] Data Visualisation with `ggplot2`
- [ ] Hypothesis Testing: `t.test`, `chisq.test`, `aov`
- [ ] Correlation: `cor`, `cor.test`
- [ ] Linear Regression: `lm`, `summary`, `plot`
- [ ] Logistic Regression: `glm`
- [ ] Multiple Regression & Model Selection
- [ ] R Markdown for Reproducible Reports
- [ ] Introduction to `tidymodels`

---

## 💡 Quick Reference Code

```r
# Load libraries
library(tidyverse)
library(ggplot2)

# Summary statistics
summary(data)
data %>% group_by(group) %>% summarise(mean=mean(score), sd=sd(score))

# t-test
t.test(score ~ gender, data = data)

# Linear regression
model <- lm(score ~ age + gender + income, data = data)
summary(model)

# ggplot visualization
ggplot(data, aes(x = income, y = score, color = gender)) +
  geom_point(alpha = 0.6) +
  geom_smooth(method = "lm") +
  theme_minimal() +
  labs(title = "Score vs Income by Gender")

# Chi-square test
chisq.test(table(data$gender, data$category))
```

---

<div align="center">

[![Back](https://img.shields.io/badge/←%20Statistical%20Packages-4b6cb7?style=for-the-badge)](../README.md)

</div>
