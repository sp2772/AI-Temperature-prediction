In this Python script, we performed temperature forecasting using machine learning techniques on a dataset obtained from Kaggle. The dataset includes various features such as present temperature, LDAPS (Land Data Assimilation System) variables, geographical features, and solar radiation, along with the next-day maximum and minimum air temperatures.

We began by importing necessary libraries and loading the dataset. After exploring the dataset's structure, we visualized the distribution of temperature values and examined their correlations with other variables.

The preprocessing phase involved handling missing values and dropping non-numeric columns like dates. We split the dataset into training and testing sets, and applied the Random Forest Regressor algorithm for temperature prediction. Through hyperparameter tuning using GridSearchCV, we optimized the model's performance.

Finally, we evaluated the model's accuracy on the test set and compared it with a base model. The script offers insights into temperature prediction and serves as a foundational template for similar forecasting projects.
