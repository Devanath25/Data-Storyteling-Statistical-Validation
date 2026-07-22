# Data-Storyteling-Statistical-Validation

# 📊 Statistical Validation & Hypothesis Testing
## ApexPlanet Data Analytics Internship – Task 4

---

## 📌 Project Overview

This project was completed as part of **Task 4 – Data Storytelling & Statistical Validation** of the **ApexPlanet Data Analytics Internship**.

The objective was to validate a business insight using **statistical hypothesis testing** and support business decisions with data-driven evidence.

An **Independent Two-Sample T-Test** was performed to determine whether there is a statistically significant difference in the average spending of male and female customers.

---

# 🎯 Objective

- Formulate a business hypothesis
- Perform statistical validation
- Apply an Independent Two-Sample T-Test
- Interpret p-value and statistical significance
- Draw business conclusions
- Support decision-making using data

---

# 📂 Dataset

The analysis was performed using the **Cleaned Sales Dataset** developed in previous internship tasks.

### Dataset Features

- Order ID
- Order Date
- Customer ID
- Customer Name
- Age
- Gender
- City
- Product
- Category
- Quantity
- Unit Price
- Total Sales

---

# ❓ Business Question

**Do male and female customers spend the same amount on average?**

---

# 📈 Hypothesis

### Null Hypothesis (H₀)

There is **no statistically significant difference** in the average sales between male and female customers.

### Alternative Hypothesis (H₁)

There **is a statistically significant difference** in the average sales between male and female customers.

---

# 📊 Statistical Test

The following statistical method was used:

- **Independent Two-Sample T-Test**

### Significance Level

- **α = 0.05**

### Decision Rule

- If **p-value < 0.05**, reject the Null Hypothesis (H₀).
- If **p-value ≥ 0.05**, fail to reject the Null Hypothesis (H₀).

---

# 🛠️ Tools & Technologies

- Python
- Pandas
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab
- Microsoft Excel
- GitHub

---

# 📊 Methodology

The statistical validation followed these steps:

1. Import the cleaned sales dataset.
2. Separate customer records based on gender.
3. Calculate descriptive statistics.
4. Perform an Independent Two-Sample T-Test.
5. Compare the p-value with the significance level.
6. Interpret the statistical results.
7. Draw business conclusions.

---

# 📈 Visualization

The project includes visualizations to support statistical analysis:

- Box Plot of Total Sales by Gender
- Sales Distribution Histogram
- Descriptive Statistics Summary

These visualizations provide a better understanding of customer spending patterns.

---

# 💡 Business Interpretation

The hypothesis test helps determine whether customer spending differs significantly based on gender.

Depending on the calculated p-value:

- **p-value < 0.05** → Evidence suggests a significant difference in average spending.
- **p-value ≥ 0.05** → No sufficient evidence of a significant difference in average spending.

This statistical validation supports informed business decisions rather than assumptions.

---

# 📂 Repository Structure

```
Task4_Hypothesis_Testing/

│
├── README.md
├── Cleaned_Sales_Dataset.xlsx
├── Python_Output/
│   ├── Boxplot.png
│   └── Histogram.png
└── Presentation/
    └── Task4_Presentation.pptx
```

---

# 🔄 Workflow

```
Cleaned Sales Dataset
        │
        ▼
Data Preparation
        │
        ▼
Group Customers by Gender
        │
        ▼
Descriptive Statistics
        │
        ▼
Independent Two-Sample T-Test
        │
        ▼
P-Value Calculation
        │
        ▼
Business Interpretation
        │
        ▼
Decision Making
```

---

# 🚀 Skills Demonstrated

- Statistical Validation
- Hypothesis Testing
- Independent Two-Sample T-Test
- Data Analysis
- Business Analytics
- Python Programming
- Pandas
- SciPy
- Data Visualization
- Business Intelligence
- Data-Driven Decision Making

---

# 📌 Future Improvements

Potential enhancements for this project include:

- One-Way ANOVA for multiple customer groups
- Correlation Analysis
- Customer Segmentation
- Predictive Analytics
- Machine Learning Models
- Advanced Statistical Modeling

---

# 👨‍💻 Author

R Devanath

E mail : devanathravi25@gmail.com

linked In : https://www.linkedin.com/in/devanathr

# 🙏 Acknowledgement

This project was completed as part of the **ApexPlanet Software Pvt. Ltd. Data Analytics Internship Program**. It demonstrates the application of **Statistical Validation**, **Hypothesis Testing**, and **Business Intelligence** techniques to validate business insights and support evidence-based decision-making.
