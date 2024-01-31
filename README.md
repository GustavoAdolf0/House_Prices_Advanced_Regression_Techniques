# House Prices Prediction: Advanced Regression Techniques

## Introduction
Predicting the sales price of a house is a crucial aspect of real estate, influenced by a myriad of factors. Some factors contribute to price increments, some to decrements, and others are interdependent. To unveil the intricate relationship between these attributes and sale prices, this project utilizes data from 1460 houses, encompassing various influencing factors like overall condition, neighborhood, and presence of basement and garage, among others. Created for the Kaggle competition, this project has garnered 2000+ views and earned a feature on Kaggle. It comprises both exploratory data analysis and predictive modeling. If you find this project valuable, kindly consider giving it a star. Thank you!

## Workflow
1. **Loading, Exploring, and Visualizing the Data:**
   - Utilizing Pandas, NumPy, Matplotlib, Seaborn, and Plotly for a comprehensive exploration of the dataset.

2. **Preparing the Dataset for Training:**
   - Identifying input and target columns, as well as numeric and categorical columns.
   - Imputing missing values in numeric columns.
   - Scaling numeric columns in the range of [0,1].
   - Encoding categorical columns.
   - Splitting the dataset into training and validation datasets.

3. **K-Fold Cross Validation:**
   - Checking the base accuracy of different models using K-Fold cross-validation.

4. **Training, Evaluating, and Tuning Models:**
   - Identifying the best model(s) with the least Root Mean Squared Error (RMSE).
   - Taking a weighted average of the best-performing models to make predictions on valid.



