# 🌧️ Extreme Rainfall and Mortality in North Carolina (2015–2018)

This repository contains the analysis and materials for a **time-series study** investigating the association between **extreme rainfall events** and **cause-specific mortality** across counties in North Carolina between 2015 and 2018.

The study examines how rare and intense precipitation events influence total and cause-specific mortality outcomes, using epidemiological modeling and meta-analytic techniques to obtain state-wide estimates.
Please find the full paper here: https://iopscience.iop.org/article/10.1088/1748-9326/ad2dd2

---

## 🙏 Collaborators from CHEN Lab – Climate, Health, and Environment Nexus
- Professor Kai Chen, Dr. Jie Ban, Dr. Yiqun Ma

---

## 📌 Research Summary

Extreme rainfall events have the potential to adversely affect human health, yet their connection to mortality outcomes has rarely been explored. In this project, we quantify the relationship between extreme rainfall and mortality using county-level environmental and health datasets.

### **Definition of Extreme Rainfall**
An **extreme rainfall event** was defined as a day when a county’s total precipitation exceeded the **95th percentile** of all daily rainfall measurements from all North Carolina counties during the study period.

### **Methods**
We implemented a **two-stage analytical approach**:

1. **Stage 1:** Estimated associations between extreme rainfall and mortality for each county using time-series regression models.
2. **Stage 2:** Performed a **meta-analysis** of county-level estimates to obtain statewide pooled effect sizes.

### **Key Findings**
Exposure to an extreme rainfall event was significantly associated with increased mortality risk in multiple categories:

| Outcome Category | Percent Increase | 95% Confidence Interval |
|------------------|-----------------|-------------------------|
| Total mortality | **2.24%** | (0.67%, 3.83%) |
| Non-accidental mortality | **2.38%** | (0.76%, 4.03%) |
| Cardiovascular disease | **3.60%** | (0.69%, 6.60%) |
| Respiratory disease | **6.58%** | (1.59%, 11.82%) |
| External causes | **6.92%** | (1.28%, 12.86%) |

We observed **no statistically significant differences** in effect estimates across:
- Age groups
- Sex
- Race
- Seasonality

### **Conclusion**
Our findings indicate that **extreme rainfall events may trigger increased mortality**, especially from **non-accidental causes such as respiratory disease**. These results highlight the importance of strengthening climate-health early warning systems and emergency preparedness under climate change.

---

