# Statistics Project
## Preprocessing
1. The dataset is checked for null values.
2. Null values have been identified in the columns: Gender, Region, PurchaseAmount, ProductCategory, Churn and Campaign Group.
3. Except PurchaseAmount all other columns are categorical columns.
4. The null values in categorical columns are filled with mode values of the respective columns.
5. The null values in the PurchaseAmount column has been filled with median value since outliers have identified in the column.
6. The dataset is checked for duplicate rows but none were identified.
## Average, Median and Mode of PurchaseAmount column
The mean, median and mode of the PurchaseAmount column has been calculated.
## Outliers in PurchaseAmount Data column
Outliers have been identified in the PurchaseAmount column using Box plot, IQR method and Z-Score method.
## Skewness and Kurtosis in PurchaseAmount column
Skewness and Kurtosis of the PurchaseAmount column is calculated. The data is almost symmetric and slightly platykurtic.
## Difference in spending between male and female customers
Two sample Z-Test is conducted to check if there is any difference in spending between male and female customers. It has been identified that there is a significant difference in spending between male and female customers.
## Relationship between ProductCategory and customer churn
Chi-Square Test is conducted to identify if there is any relationship between ProductCategory and Churn but no relationship was identified.
## Purchase amount vary significantly across different regions
One Way ANOWA Test is conducted to check if the PurchaseAmount vary significantly across different regions. It was found that there is no significant difference in PurcaseAmount across different regions.
## Email Campaign (A or B) performed better in terms of average PurchaseAmount
Two Sample Z-test is used to identify if there is any difference between the two email campaigns but the performance of the two campaigns was found to be identical.
## PurchaseAmount follows a normal distribution
From the skewness and kurtosis values it can be concluded that the PurchaseAmount data follows a normal distributtion.
## Insights by applying Central Limit Theorem
It was observed that when we take large enough samples from the dataset the mean of these samples is following a normal distribution.
## 95% confidence interval for the average PurchaseAmount
The average purchase amount with 95% confidence interval is calculated.

