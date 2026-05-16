# 😴 Sleep Health & Cardiovascular Risk: A Sex-Specific Epidemiological Analysis

## 📌 1. Project Title
**Sex-Specific Disparities in Sleep Architecture and their Interaction with Cardiovascular Workloads using Medical Machine Learning.**

---

## 🔍 2. Background & Objectives
Sleep hygiene and disorders severely intermediate chronic cardiometabolic conditions. 
The core objectives of this research project are:
- To determine if **sleep duration** variations inherently possess **sex-specific differences**.
- To examine how clinical sleep disorders (Insomnia, Sleep Apnea) act as determinants for cardiovascular stress (**resting heart rate**).
- To evaluate if biological sex interacts with sleep pathologies to create compound interaction effects on cardiac load.
- To deploy a translation algorithm (**Decision Tree Modeling**) for clinical disease classification.

---

## 📂 3. Dataset Specifications & Source
- **Dataset Name:** Kaggle — Sleep Health and Lifestyle Dataset
- **Sample Size:** 374 clinical case files, 13 features.
- **Direct Dataset Link:** [Sleep Health and Lifestyle Dataset via Kaggle](https://kaggle.com)

---

## 🛠️ 4. Methods & Statistical Approaches Used
1. **Descriptive Analytics:** Formulated exploratory metrics using demographic stratification via `tidyverse`.
2. **Parametric Statistical Inference:** Deployed an **Independent Two-Sample t-test** to calculate differential sleep spans between male and female strata.
3. **Advanced Factorial Modeling:** Executed **One-Way ANOVA** followed by **Tukey's Honest Significant Difference (Tukey HSD)** for strict pairwise post-hoc controls.
4. **Epidemiological Interaction Testing:** Formulated a **Two-Way ANOVA with Interaction terms** ($Gender \times Sleep Disorder$) to fulfill the evaluation of mediated cardiac risk factors.
5. **Machine Learning Layout:** Constructed a **Decision Tree Classifier** using `rpart` and visualized clinical decision boundaries using `rpart.plot` with cross-validation confusion matrices.

---

## 🏆 5. Key Research Findings
- **Statistically Significant Gender Disparity:** The independent t-test verified that female subjects possess a significantly higher mean sleep duration (7.23 hours) compared to male counterparts (7.03 hours) ($p = 0.018$).
- **Severe Cardiac Stress Correlates:** One-Way ANOVA confirmed that chronic sleep pathologies strongly determine resting heart rates ($p = 6.74 \times 10^{-14}$).
- **Confirmed Factor Interactions:** The Two-Way ANOVA verified a highly significant **interaction effect between Gender and Sleep Disorders** ($p = 0.0002$). This proves that sleep disorders mutate resting cardiovascular burdens differently across men and women.
- **Robust Machine Learning Screening:** The clinical decision tree achieved robust predictive power, successfully tracing disorder status utilizing cardiac and demographic parameters.

---

## 🔗 6. Live Interactive Report
[👉 CLICK HERE TO VIEW THE FULL INTERACTIVE SLEEP REPORT](https://phyonyeinchan.github.io/sleep-health-sex-specific-analysis/)
