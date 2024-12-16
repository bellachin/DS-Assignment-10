# DS-Assignment-10 Description

This code performs data preprocessing and model training on a dataset of babies' birth weights, aiming to predict birth weight based on various features like gestation period, smoking status, and parental age. The dataset is cleaned by handling invalid values, checking for missing data, and encoding categorical features using one-hot encoding to prepare the data for machine learning. The code uses the `pandas` library for data manipulation, `seaborn` and `matplotlib` for data visualization, and `scipy.stats` for statistical tests like Chi-Square, ANOVA, and Pearson correlation to identify significant predictors of birth weight. A Random Forest Regressor (`RandomForestRegressor` from `sklearn`) is trained to predict birth weight, and various evaluation metrics, such as Mean Squared Error (MSE), R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE), are calculated to assess model performance. Additionally, model tuning is performed by experimenting with different values of the `n_estimators` parameter to optimize the Random Forest model. Lastly, a K-Nearest Neighbors (KNN) Regressor (`KNeighborsRegressor`) is applied for comparison, with hyperparameter tuning for the optimal number of neighbors (`k`) to enhance model accuracy.
