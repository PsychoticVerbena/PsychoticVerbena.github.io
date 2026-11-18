# Modeling Revenue Determinants Across 687,000+ New York Businesses

**Tech Stack:** Python, Scikit-Learn (Random Forest, Linear Regression), Data Engineering, Statistical Modeling

## The Business Problem
Understanding what structural factors—such as workforce size, corporate subsidiary status, and business registration type—actually drive annual revenue in dense markets, and proving why traditional linear forecasting fails at enterprise scale.

## Data Engineering & Cleaning Pipeline
To analyze this enterprise-scale dataset of 687,588 New York State business records, I built an end-to-end cleaning pipeline to handle extreme skew and categorical missingness:
* **Diagnosed Bimodal Missingness:** Pruned columns with >90% missingness (e.g., secondary addresses) and removed redundant HQ fields.
* **Engineered Structural Signals:** Converted sparse categorical fields (like `Subsidiary Code`) into binary flags (`1`/`0`), turning missing data into a measurable corporate-structure feature.
* **Preserved Sample Size:** Applied constant imputation to columns missing 27–38% of records, retaining over 250,000 rows that would have otherwise been lost. Filtered core predictors down to **676,016 clean records**.
* **Normalized Extreme Skew:** Applied log transformations to both `Yearly Revenue` and `Employee Total` to prevent mega-corporations from distorting model weights while retaining valid $0 revenue startups and R&D entities.

## Machine Learning Validation & Business Impact
I compared a baseline Multiple Linear Regression against a Random Forest regression model. The Random Forest model successfully captured non-linear relationships at the enterprise level, increasing revenue prediction accuracy ($R^2$) from **42.5% to 86.1%** and cutting Mean Absolute Error by more than half (1.043 down to 0.470).

### Real-World Revenue Prediction Comparison
| Company Profile | Workforce | Actual Revenue | Linear Regression Prediction | Random Forest Prediction |
| :--- | :--- | :--- | :--- | :--- |
| **NYC Allied Holdings, LLC** *(Early-Stage)* | 0 | $0 | $157,096 | **$0** |
| **W. W. Norton & Company, Inc.** *(Mid-Market Publisher)* | 500 | $180.77M | $5,847 | **$124.54M** |
| **BBDO Worldwide, Inc.** *(Enterprise Agency)* | 10,000 | $617.00M | $11.64M | **$755.76M** |

> *Interactive Dashboard Visualizing NY Market Revenue Trends — [Insert Link Here Once Built]*
