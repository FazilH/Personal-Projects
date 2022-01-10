# Regression

# 

# Regression is an approach for finding the relationship between the response/target variable and one or more explanatory/independent variable. In regression the target variable is scalar/numerical.

# 

# Data Used : [Medical Cost Personal Datasets \| Kaggle](https://www.kaggle.com/mirichoi0218/insurance)

# 

# Variables :

| **Variables Name** | **Description**                                                                                                                                                                                                         |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Age                |  Age of primary beneficiary                                                                                                                                                                                             |
| Sex                | Gender female or male                                                                                                                                                                                                   |
| BMI                | Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m \^ 2) using the ratio of height to weight, ideally 18.5 to 24.9 |
| Children           | Number of children covered by health insurance / Number of dependents                                                                                                                                                   |
| Smoker             | Whether the beneficiary is a smoker or not                                                                                                                                                                              |
| Region             | The beneficiary's residential area in the US, northeast, southeast, southwest, northwest.                                                                                                                               |
| Charges            | Individual medical costs billed by health insurance                                                                                                                                                                     |

**Steps performed:**

1.  Data Exploration : Checked for the shape of the data, missing values and
    duplicate values.

2.  Separated the data into categorical and numerical variable.

3.  Visually explored the data distribution.

4.  Count plot for number of children/dependents.

5.  Count plot for number of male and female.

6.  Count plot for whether the beneficiary is a smoker or not.

7.  Region-wise count plot for the beneficiaries.

8.  Chart for product-wise complaint chart.

9.  Side-by-side bar chart for whether the smoker is male or female.

10. Converting the smoker and sex variable into categorical variable using
    LabelEncoder

11. Correlation analysis via heatmap.

12. Made the dummy values for region and concatenated with original data.

13. Used StandardScaler for data standardization.

14. Divided the data into train and test dataset.

15. Performed Linear regression, Ridge regression, Lasso regression, ElasticNet,
    and evaluated each model using Root Mean Square Error(RMSE), Mean Absolute
    Error(MAE), Mean Absolute Percentage Error(MAPE) and R2 Value/Coefficient of
    Determination.

16. Also used Random Forest and XGBoost for regression.

17. Prepared the comparison table to compare the performance of each model.
