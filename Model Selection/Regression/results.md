# Model Selection for Dataset

We have to select the model for our dataset, so we are applying all regression models on our dataset and then selecting the best regression model based on the R-squared coefficient. The best model will have an R-squared coefficient closest to one.

`Data.csv` is the dataset for model selection. This dataset is cleaned and numeric, so we don't have to pre-process it.

The R-squared coefficients of all regression models are given below:

- **Multiple Linear Regression:** 0.9325315554761303
- **Polynomial Regression:** 0.9458193330952832
- **Support Vector Regression:** 0.9480784049986258
- **Decision Tree Regression:** 0.922905874177941
- **Random Forest Regression:** 0.9615908334363876

Hence, according to the R-squared coefficient, **Random Forest Regression** is the best regression model for this dataset `Data.csv`.
