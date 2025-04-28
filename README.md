📑 Project Overview:
In this project, Risk Analytics was applied to a large bank loan dataset to analyse how consumer attributes influence the likelihood of loan defaults.
Through Exploratory Data Analysis (EDA), key patterns and strong indicators driving defaults were identified by handling missing values, detecting outliers, addressing data imbalance, and conducting univariate, segmented univariate, and bivariate analyses.

📊 Approach:
Data Extraction: 
* Downloaded and imported the dataset into Excel.

Data Cleaning: 
* Removed irrelevant columns (>60% missing data).
* Handled missing data with Median (numeric) and Mode (categorical).
* Detected and addressed outliers using the IQR method.

Analysis:
* Conducted univariate, segmented univariate, and bivariate analyses.
* Explored correlations between key variables.
* Studied the impact of family status, income, and loan type on default rates.

Reporting:
* Compiled insights and visualisations into a structured report.

Outlier Detection:
* Outliers were found using the IQR method on variables like AMT_INCOME_TOTAL, AMT_CREDIT, and AMT_ANNUITY.

Data Imbalance:
* Defaulters: 8%
* Non-Defaulters: 92%
* Highly imbalanced dataset.

Univariate Analysis:
* Income distribution, credit amount, contract type, and family status.

Segmented Univariate Analysis:
* Identified that lower-income applicants and single individuals are more likely to default.

Bivariate Analysis:
* Explored relationships between income, credit amount, family status, loan type, and default rates.

Correlation Analysis:
* Strong correlations between loan amount, goods price, and annuity amount.
* Family size and number of children are highly correlated.
* Employment stability plays a greater role for non-defaulters.

📝 Results & Conclusion:
Risk Factors:
* Being single.
* Lower-income levels.
* Taking revolving loans instead of cash loans.

Protective Factors:
* Being married.

Higher income groups.
* Larger loan amounts (especially for non-revolving loans).

Key Takeaway:
* Focusing on applicant stability, income, family status, and loan type can significantly help banks refine loan approval strategies and mitigate default risks.

Link for Dataset: https://drive.google.com/file/d/1mxB6TJ3u942QSZwPdmyGUv1MUYxOYNYl/view

