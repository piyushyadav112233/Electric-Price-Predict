# Electric-Price-Predict
Data Cleaning: The data had missing values and outliers, which were addressed before analysis. This ensures the results are more reliable.

Feature Importance: We discovered that electricity prices (SMPEP2) were most strongly related to other electricity price variables like SMPEA, SystemLoadEP2, SystemLoadEA. This is intuitive, as current and past prices often influence future prices. Factors like wind production and the time of year also played a role.

Model Selection: We tested several machine learning models, including RandomForest, DecisionTree, etc., to predict SMPEP2. Random Forest model emerged as a potential candidate, demonstrating a high prediction accuracy.

Model Improvement: Feature selection and hyperparameter tuning were employed to further enhance the model's performance, leading to a potential improvement in price predictions.
Think of it like predicting the weather. We looked at past weather data like temperature, wind speed, and rainfall to predict tomorrow's temperature. Similarly, we analyzed past electricity usage and prices to predict future electricity prices. We used advanced tools (machine learning models) to build a prediction system and found that it has good accuracy.

Overall, the analysis successfully developed a potential model for predicting electricity prices, paving the way for better energy planning and cost management.

