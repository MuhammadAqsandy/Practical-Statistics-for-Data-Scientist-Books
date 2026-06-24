# Practical Statistics for Data Scientists (O'Reilly)

> **Code Reproduction + Theoretical Deep-Dive**  
> Individual Task – Machine Learning & Deep Learning Class

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 📚 About This Repository

This repository contains **code reproductions and theoretical explanations** of all 7 chapters from the book:

> *Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python*  
> — Peter Bruce, Andrew Bruce, Peter Gedeck (O'Reilly, 2020)

Each notebook includes:
- ✅ **Code reproduction** of core concepts from the chapter
- 📖 **Theoretical explanations** using LaTeX-rendered math and markdown
- 📊 **Visualizations** to build intuition
- 🗒️ **Chapter summaries** with comparison tables

---

## 📂 Repository Structure

```
.
├── PracticalStatisticsChapter1.ipynb   # Exploratory Data Analysis
├── PracticalStatisticsChapter2.ipynb   # Data & Sampling Distributions
├── PracticalStatisticsChapter3.ipynb   # Statistical Experiments & Significance Testing
├── PracticalStatisticsChapter4.ipynb   # Regression & Prediction
├── PracticalStatisticsChapter5.ipynb   # Classification
├── PracticalStatisticsChapter6.ipynb   # Statistical Machine Learning
├── PracticalStatisticsChapter7.ipynb   # Unsupervised Learning
├── requirements.txt
└── README.md
```

---

## 📋 Chapter Summaries

### Chapter 1 – Exploratory Data Analysis (EDA)
Covers the foundational techniques for understanding raw data before modeling. Topics include estimates of **location** (mean, median, trimmed mean), estimates of **variability** (std deviation, IQR, MAD), distribution visualization (histograms, boxplots, violin plots), **correlation** matrices, and multi-variable exploration via scatter plots. Key insight: robust statistics like the median and IQR are preferred when outliers are present.

---

### Chapter 2 – Data & Sampling Distributions
Explains how samples relate to populations through **sampling distributions** and the **Central Limit Theorem (CLT)**. Covers the **Bootstrap** resampling method for estimating uncertainty without distributional assumptions, **Confidence Intervals**, and key probability distributions: Normal, Binomial, Poisson, and Exponential. Key formula: Standard Error = σ/√n.

---

### Chapter 3 – Statistical Experiments & Significance Testing
Introduces the design and analysis of **A/B tests** and **hypothesis tests**. Covers **permutation tests** (distribution-free alternative to parametric tests), **t-tests**, **ANOVA** for multiple groups, **chi-square tests** for categorical data, and the **multiple testing problem** (Bonferroni correction). Key insight: statistical significance ≠ practical significance — always consider effect size.

---

### Chapter 4 – Regression & Prediction
Covers **linear regression** from simple OLS to multiple regression, **polynomial features**, **model evaluation** (R², RMSE, residual plots), and **cross-validation**. Introduces **regularization** with Ridge (L2) and Lasso (L1) to combat overfitting. Key takeaway: residual plots are essential for diagnosing model violations (heteroskedasticity, non-linearity).

---

### Chapter 5 – Classification
Introduces **classification algorithms**: Naive Bayes (Bayes' theorem + independence assumption), **Logistic Regression** (sigmoid function, log-odds), **LDA**, and **KNN**. Covers **evaluation metrics**: confusion matrix, precision, recall, F1, **ROC-AUC**. Key insight: for imbalanced datasets, AUC-ROC is more informative than accuracy.

---

### Chapter 6 – Statistical Machine Learning
Covers powerful ensemble methods: **Decision Trees** (Gini impurity, entropy), **Random Forest** (bagging + random feature selection), **Gradient Boosting** (sequential residual correction). Explains the **Bias-Variance Tradeoff** and demonstrates hyperparameter tuning. Key insight: Random Forests reduce variance through decorrelated trees; Gradient Boosting reduces bias iteratively.

---

### Chapter 7 – Unsupervised Learning
Explores structure discovery without labels. **PCA** for dimensionality reduction (scree plot, explained variance), **K-Means** clustering (WCSS minimization, elbow method, silhouette score), **Hierarchical Clustering** (dendrograms, Ward linkage), and **Gaussian Mixture Models** (soft assignments, EM algorithm). Key insight: always standardize features before applying distance-based methods.

---

## 🛠️ Requirements

```bash
pip install -r requirements.txt
```

**Core libraries used:**
- `numpy`, `pandas` — data manipulation
- `matplotlib`, `seaborn` — visualization
- `scikit-learn` — ML algorithms and evaluation
- `scipy` — statistical tests and distributions

---

## 📖 Reference

Bruce, P., Bruce, A., & Gedeck, P. (2020). *Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python* (2nd ed.). O'Reilly Media.

---

*All code is original work for academic purposes. Theoretical explanations are written by the author with assistance from LLMs as permitted by the course guidelines.*
