# Statistical Results Summary

This file summarizes the Python-based statistical analysis performed for the sales performance and demand pattern analysis project.

## 1. Correlation Analysis

Correlation analysis was used to understand the relationship between quantity sold and sales value.

### Result

- Correlation value: 0.0749
- P-value: 3.14e-169

### Interpretation

There is a very weak positive relationship between quantity sold and sales value. Since the p-value is very small, the relationship is statistically significant. However, the strength of the relationship is weak, meaning sales value is not strongly dependent only on quantity sold. Product price, category, variant, and dealer type may also influence sales value.

## 2. One-Way ANOVA

One-way ANOVA was used to check whether there is a significant difference in sales value across different product categories.

### Result

- F-value: 1195.6489
- P-value: 0.0

### Interpretation

The result shows that there is a statistically significant difference in sales value across product categories. This means all product categories do not contribute equally to revenue.

## 3. Linear Regression

Linear regression was used to understand how quantity sold affects sales value.

### Result

- Intercept: 17628.0732
- Coefficient: 18.5585
- R-squared: 0.0056

### Interpretation

The R-squared value is very low, which means quantity sold alone explains only a very small portion of the variation in sales value. This shows that other factors such as product category, pricing, dealer contribution, and product variant also play an important role.

## 4. Independent Sample T-Test

The independent sample t-test was used to compare per-transaction revenue between FY 2019–2020 and FY 2020–2021.

### Result

- FY 2019–2020 mean revenue: ₹13,257.83
- FY 2020–2021 mean revenue: ₹26,865.32
- T-value: -32.0043
- P-value: 5.97e-223

### Interpretation

There is a statistically significant difference in average transaction revenue between the two financial years. FY 2020–2021 recorded a higher average transaction value compared to FY 2019–2020.

## 5. Coefficient of Variation

Coefficient of variation was used to compare sales variability across product categories.

### Interpretation

Categories with higher coefficient of variation showed more unstable sales performance, while categories with lower variation showed more stable demand patterns.
