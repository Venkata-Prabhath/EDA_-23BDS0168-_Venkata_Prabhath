# Exploratory Data Analysis (EDA) - Credit Card Dataset

An end-to-end exploratory data analysis project performed on a Credit Card dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn.

## 📊 Dataset Overview
The dataset contains financial and account-related attributes extracted from a remote repository. It includes a mix of numerical features (such as limits, balances, or transaction details) and categorical features.

- **Source:** [CreditCard.csv](https://raw.githubusercontent.com/salemprakash/EDA/main/Data/CreditCard.csv) [click here] 
- **Libraries Used:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🛠️ Project Pipeline Steps

1. **Data Loading & Inspection:**
   - Imported data directly from GitHub into Google Colab.
   - Inspected dataset shape, data types, and structural info (`df.info()`, `df.describe()`).

2. **Data Cleaning:**
   - Identified and handled missing values using statistical strategies (mean imputation for numerical features, mode imputation for categorical features).
   - Checked and dropped duplicate records.

3. **Data Transformation:**
   - **Binning:** Segmented continuous numerical metrics into discrete ordinal categories (`Low`, `Medium`, `High`).
   - **Encoding:** Applied Label Encoding to translate categorical text columns into machine-readable numeric formats.

4. **Exploratory Data Analysis (EDA):**
   - **Univariate Analysis:** Analyzed distributions, frequencies, and spreads using count plots, histograms, and box plots.
   - **Bivariate & Multivariate Analysis:** Explored interactions between variables utilizing correlation heatmaps and matrix charts to detect underlying patterns and multicollinearity.

---

## 📈 Key Insights & Visualizations
- *Missing value heatmaps* revealed structural gaps which were successfully cleaned prior to modeling/analysis.
- *Correlation matrices* highlight linear dependencies between primary account parameters.

---
