<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1A4480,100:1565C0&height=180&section=header&text=Stata&fontSize=54&fontColor=ffffff&fontAlignY=40&desc=Statistical%20Software%20for%20Econometrics%20%26%20Research&descAlignY=60&descSize=16&descColor=d0e4ff&animation=fadeIn" />

[![Publisher](https://img.shields.io/badge/Publisher-StataCorp-1A4480?style=for-the-badge)]()
[![Use Case](https://img.shields.io/badge/Use%20Case-Econometrics%20%7C%20Epidemiology%20%7C%20Panel%20Data-1565C0?style=for-the-badge)]()
[![Tutor](https://img.shields.io/badge/Tutor-Trevor%20Jimu-1A4480?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TrevorTJ-Jimu)

</div>

---

## 📌 Overview

**Stata** is a powerful statistical package favoured in **economics, epidemiology, and social policy research**. It combines a clean do-file scripting language with excellent panel data, survival analysis, and regression capabilities.

---

## 🗂️ Contents

| Folder | Description |
|--------|-------------|
| `notes/` | Stata do-file guides and output explanations |
| `exercises/` | Datasets and task sheets |
| `solutions/` | Annotated do-files with results |

---

## 🧭 Topics Covered

- [ ] Stata Interface: Command Window, Do-file Editor, Viewer
- [ ] Data Management: `import`, `merge`, `reshape`, `generate`
- [ ] Descriptive Statistics: `summarize`, `tabulate`
- [ ] t-Tests: `ttest`
- [ ] ANOVA: `anova`, `oneway`
- [ ] Regression: `regress`, `margins`, `predict`
- [ ] Logistic Regression: `logit`, `logistic`
- [ ] Panel Data: `xtset`, `xtreg`, `xtlogit`
- [ ] Survival Analysis: `stset`, `sts graph`, `cox`
- [ ] Graphs: `histogram`, `scatter`, `twoway`
- [ ] Do-files & Log Files for Reproducibility

---

## 💡 Quick Reference Syntax

```stata
* Load and describe data
use "dataset.dta", clear
describe
summarize age income score

* t-test
ttest score, by(gender)

* OLS Regression
regress score age gender income
margins gender

* Panel regression
xtset id year
xtreg score income, fe

* Export results
outreg2 using results.doc, replace
```

---

<div align="center">

[![Back](https://img.shields.io/badge/←%20Statistical%20Packages-4b6cb7?style=for-the-badge)](../README.md)

</div>
