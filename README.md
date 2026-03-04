# Feature Engineering for Machine Learning

<p align="center"> <img src="https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white" /> <img src="https://img.shields.io/badge/NumPy-1.24+-013243?style=for-the-badge&logo=numpy&logoColor=white" /> <img src="https://img.shields.io/badge/Scikit--Learn-1.3+-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" /> <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" /> <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" /></p>

## About The Repo 

A comprehensive, hands-on repository covering essential feature engineering techniques used in real-world machine learning pipelines. Each module provides clean notebooks, clear explanations, and production-ready code patterns designed to bridge the gap between theory and industry practice.

---

## Purpose

| Goal | Description |
| --- | --- |
| **Learn** | Understand *why* and *when* each technique is applied |
| **Practice** | Work through real examples with structured notebooks |
| **Reference** | Quick lookup for interview prep and project work |
| **Build** | Develop reusable feature engineering pipelines |

---

## Techniques Covered

### 1. Missing Value Handling

* **Mean/Median Imputation:** Numerical features with few missing values.
* **Arbitrary Value Imputation:** When missingness itself carries information.
* **End of Distribution Imputation:** Preserving outlier signal.
* **Missing Indicator:** Flagging missingness as a feature.
* **KNN Imputation:** Features with local structure.
* **Iterative (MICE) Imputation:** Complex feature interdependencies.

### 2. Binning & Binarization

* **Equal Width Binning:** Fixed-range intervals.
* **Equal Frequency Binning:** Same number of observations per bin.
* **K-Means Binning:** Cluster-based boundaries.
* **Binarization:** Threshold-based binary conversion.

### 3. Power Transformations

* **Log/Reciprocal/Square Root:** Handling right-skewed data.
* **Box-Cox:** Automated optimal transform for positive data.
* **Yeo-Johnson:** Automated optimal transform for any data (including zeros/negatives).

### 4. Categorical Encoding

* **One-Hot Encoding:** Low cardinality, no ordering.
* **Ordinal/Label Encoding:** Handling meaningful or arbitrary order.
* **Target/Frequency/Binary Encoding:** Strategies for high-cardinality features.

### 5. Feature Scaling

* **Standardization (Z-Score):** Unbounded, mean 0, std 1.
* **Min-Max Scaling:** Fixed [0, 1] range.
* **Robust Scaling:** Resistant to outliers using IQR.
* **MaxAbs Scaling:** Preserves sparsity, range [-1, 1].

### 6. Datetime & Mixed Variables

* **Datetime Decomposition:** Extracting year, month, day, weekday.
* **Cyclical Encoding:** Sine and cosine transforms for periodic data.
* **Mixed Variable Handling:** Separating numeric and categorical components in strings.

---

##  Tech Stack

| Category | Tools |
| --- | --- |
| **Language** | Python 3.9+ |
| **Data Manipulation** | Pandas, NumPy |
| **Machine Learning** | Scikit-Learn |
| **Visualization** | Matplotlib, Seaborn |
| **Feature Engineering** | Feature-Engine, Category Encoders |

---

## How to Use This Repository

1. **Follow the Path:** Missing Values → Encoding → Scaling → Transformations → Binning → Datetime → Mixed Variables.
2. **Review Concepts:** Each topic includes a `README.md` and sequential notebooks.
3. **Experiment:** Modify parameters and apply these patterns to your own datasets.
---
## 🤝 Contributing

Contributions are welcome! Please fork the repo, create a feature branch, and submit a Pull Request.
