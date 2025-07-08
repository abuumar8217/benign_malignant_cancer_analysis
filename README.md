# # 🧪 Hypothesis Testing with Real-World Datasets

This project performs statistical hypothesis testing on two real-world datasets to determine the significance of group differences and relationships. The lab demonstrates how to choose and execute statistical tests based on the normality of the data.

## 📂 Datasets Used

1. **Breast Cancer Data (cancer_data.csv)**
   - Focus: Relationship between tumor radius and cancer diagnosis (benign vs malignant).
   - Source: UCI ML Repository – Breast Cancer Wisconsin Dataset.

## 🧪 Methods Applied

### ✅ Normality Testing
- Shapiro-Wilk Test
- Q-Q Plot
- Histogram with KDE
- Skewness and Kurtosis

### ✅ Data Transformation
- Logarithmic transformation to normalize right-skewed data.

### ✅ Hypothesis Tests
- **T-Test (Independent Samples)**: Comparing means between groups (e.g., neighborhoods).
- **Welch’s T-Test**: Used when variances are unequal.
- **Chi-Square Test**: Assessing association between categorical variables.
- **Z-Test for Proportions**: Comparing proportions of malignancy across tumor size groups.

### ✅ Visualizations
- Histograms & KDE
- Q-Q Plots
- Boxplots and Violin plots
- Confidence Interval Error Bars
- Chi-Square and Z-distribution curves

## 📊 Key Findings

- The original `SalePrice` was not normally distributed; a log transformation improved normality.
- There was a statistically significant difference in mean sale prices between neighborhoods.
- Tumor radius was strongly associated with cancer diagnosis.
- Patients with high tumor radius had a significantly higher proportion of malignancy.

## 🛠️ Requirements

- Python 3.x
- Libraries:
  - numpy
  - pandas
  - scipy
  - seaborn
  - matplotlib
  - statsmodels

Install with:

```bash
pip install numpy pandas scipy matplotlib seaborn statsmodels
