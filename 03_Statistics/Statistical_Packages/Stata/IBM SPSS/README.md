<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:052FAD,100:1565C0&height=180&section=header&text=IBM%20SPSS&fontSize=50&fontColor=ffffff&fontAlignY=40&desc=Statistical%20Package%20for%20the%20Social%20Sciences&descAlignY=60&descSize=16&descColor=d0e4ff&animation=fadeIn" />

[![IBM](https://img.shields.io/badge/Publisher-IBM-052FAD?style=for-the-badge&logo=ibm&logoColor=white)]()
[![Use Case](https://img.shields.io/badge/Use%20Case-Surveys%20%7C%20Research%20%7C%20Clinical-1565C0?style=for-the-badge)]()
[![Tutor](https://img.shields.io/badge/Tutor-Trevor%20Jimu-052FAD?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TrevorTJ-Jimu)

</div>

---

## 📌 Overview

**SPSS (Statistical Package for the Social Sciences)** is one of the most widely used statistical software platforms in academia, healthcare, and market research. This folder provides practical guides and exercises for using SPSS effectively.

---

## 🗂️ Contents

| File/Folder | Description |
|-------------|-------------|
| `notes/` | Step-by-step SPSS guides with screenshots |
| `exercises/` | Data files and task sheets |
| `solutions/` | Output files with interpretation |

---

## 🧭 Topics Covered

- [ ] Navigating SPSS: Data View vs Variable View
- [ ] Entering & Importing Data
- [ ] Descriptive Statistics (Frequencies, Means, Crosstabs)
- [ ] Creating Charts & Graphs
- [ ] t-Tests (One-sample, Independent, Paired)
- [ ] One-Way & Two-Way ANOVA
- [ ] Pearson & Spearman Correlation
- [ ] Simple & Multiple Linear Regression
- [ ] Logistic Regression
- [ ] Chi-Square Tests
- [ ] Reliability Analysis (Cronbach's Alpha)
- [ ] Factor Analysis (Introduction)

---

## 💡 Quick Reference Syntax

```spss
* Descriptive statistics
DESCRIPTIVES VARIABLES=age income score
  /STATISTICS=MEAN STDDEV MIN MAX.

* Independent t-test
T-TEST GROUPS=gender(1 2)
  /VARIABLES=score.

* One-Way ANOVA
ONEWAY score BY group
  /POSTHOC=TUKEY ALPHA(0.05).

* Linear Regression
REGRESSION
  /DEPENDENT score
  /METHOD=ENTER age gender income.
```

---

<div align="center">

[![Back](https://img.shields.io/badge/←%20Statistical%20Packages-4b6cb7?style=for-the-badge)](../README.md)

</div>
