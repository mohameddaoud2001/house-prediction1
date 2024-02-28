 1. Dataset Description:
   - The dataset, sourced from Kaggle, focuses on California housing prices.
   - Features include geographical coordinates, median age, total rooms, total bedrooms, population, and ocean proximity.
   - The target variable is the median house value, making it a regression problem.

 2. Data Analysis and Exploration:
   - **Data Loading and Exploration:** The script uses Pandas to load the dataset and explores its structure.
   - **Handling Null Values:** Any missing values in the dataset are identified and subsequently dropped.
   - **Distribution Analysis:** The distribution of numeric features is examined through histograms.
   - **Correlation Visualization:** Correlation among features is visualized using heatmaps.

 3. Data Preprocessing:
   - **Data Splitting:** The dataset is divided into training and testing sets for model training and evaluation.
   - **Skewed Feature Scaling:** Logarithmic transformation is applied to scale skewed features.
   - **Categorical Feature Encoding:** The categorical feature "ocean proximity" is one-hot encoded.
   - **Further Exploration:** Additional exploration is conducted through visualizations and correlation analysis to understand the data better.

 4. Feature Engineering:
   - **New Feature Creation:** Features like the bedroom ratio and rooms per household are generated.
   - **Geographical Visualization:** The geographical distribution of house values is visualized for insights.

 5. Linear Regression Model:
   - **Model Training:** A basic linear regression model is trained on the preprocessed data.
   - **Scaling Impact Analysis:** The script investigates the effect of scaling on the linear regression model's performance.

 6. Random Forest Regression Model:
   - **Default Model Training:** A random forest regressor is trained with default hyperparameters.
   - **Grid Search:** Hyperparameters like the number of estimators, max features, and min sample split are fine-tuned using grid search and cross-validation.
   - **Evaluation:** The performance of the random forest model is assessed on the test set.

 7. Hyperparameter Tuning:
   - **Exploration:** Different values for hyperparameters are experimented with to find the optimal combination.
   - **Selection:** The best hyperparameter combination is selected based on cross-validated performance.

 8. Results:
   - **Model Scores:** The linear regression model achieves a moderate score, while the default random forest model outperforms it.
   - **Hyperparameter Impact:** Tuning hyperparameters improves the random forest model, although not consistently.
