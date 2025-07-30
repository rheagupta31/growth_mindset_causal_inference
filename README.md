# 🎓 Estimating the Causal Impact of a Growth Mindset Intervention on Student Achievement

This project explores the effectiveness of a **growth mindset intervention** using synthetic student data inspired by the **National Study of Learning Mindsets (NSLM)**. It applies robust **causal inference techniques** including:

- Ordinary Least Squares (OLS)
- Propensity Score Matching (PSM)
- Inverse Probability Weighting (IPW)

These methods help estimate the **Average Treatment Effect (ATE)** of the intervention on academic performance.

---

## 📊 Methods Overview

- **OLS Regression**: Controls for covariates directly.
- **1:1 Propensity Score Matching**: Pairs treated and untreated units with similar characteristics.
- **Inverse Probability Weighting**: Reweights samples to simulate a randomized trial.
- **Causal Validity Checks**: Covariate balance (via SMD plots), propensity score overlap, ignorability assumption.

---

## 🧠 Key Findings

- The intervention yields a **positive, significant ATE (~+0.41)** across all methods.
- Covariate balance and positivity assumptions are satisfied.
- The intervention appears **robust and scalable**, though contextual factors amplify its effectiveness across schools.

---

## 📁 Repository Contents

- `growth_mindset_causal_inference.ipynb`: Full notebook with code, visualizations, and results.
- `poster.pdf`: Research poster summarizing the project.
- `requirements.txt`: Python environment dependencies.
- `LICENSE`: MIT license for reuse and adaptation.

---

## ▶️ How to Run

1. Clone this repo or download the notebook.
2. Open it in **Google Colab** or JupyterLab.
3. Run all cells.

[![Open In Colab]([https://colab.research.google.com/assets/colab-badge.svg](https://colab.research.google.com/drive/1TdXUyzljrLXKgmtXbkQw8oPg7vRVC5wt#scrollTo=9uvB4GlHRKjC))](https://colab.research.google.com/)

---

## 🧾 References

- Austin, P. C., & Stuart, E. A. (2015). *Moving towards best practice when using inverse probability of treatment weighting (IPTW)*.
- Rosenbaum, P. R., & Rubin, D. B. (1983). *The central role of the propensity score in observational studies for causal effects*.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
