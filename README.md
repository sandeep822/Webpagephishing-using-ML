# Webpagephishing-using-ML


<img width="507" alt="image" src="https://github.com/sandeep822/Webpagephishing-using-ML/assets/50867031/caefad55-4a05-4059-9f1a-db66d28a5be7">

The line graph visually represents the variations in specific website characteristics (features) across the dataset's 11430 entries. This exploration is crucial for understanding the distribution and patterns of these features, such as the frequency of dots, hyphens, at symbols, and other symbols in URLs. Detecting trends or anomalies in these features is essential for assessing potential phishing or suspicious website behavior. Analyzing this data aids in building predictive models or identifying important factors contributing to the overall classification or 'status' of websites in the dataset.

<img width="507" alt="image" src="https://github.com/sandeep822/Webpagephishing-using-ML/assets/50867031/b8599cd3-283c-4df5-b990-3d0863826ed5">

The removal of the 'web_traffic,' 'domain_age,' and 'domain_registration_length' columns from the dataset is a strategic move for enhancing the effectiveness of machine learning model predictions through feature selection. While 'web_traffic' offers valuable insights into website performance and popularity, its direct dependency on the 'status' column suggests a potential source of multicollinearity, which could introduce noise and hinder model performance. Removing 'web_traffic' facilitates a more independent analysis of other features, reducing the risk of overfitting and improving the model's generalizability. Similarly, 'domain_age' and 'domain_registration_length' may contribute less predictive power compared to other features, especially if they exhibit low variability or redundancy with other columns. By pruning these columns, the dataset becomes more focused, enhancing the model's ability to discern relevant patterns and relationships among the remaining features, ultimately improving its predictive accuracy and interpretability.

<img width="507" alt="image" src="https://github.com/sandeep822/Webpagephishing-using-ML/assets/50867031/e1973413-8075-4dac-9b39-0869973954ac">

The bar chart depicts the mean values for specified columns with low dependency on the 'status' variable, providing a concise overview of their distribution. Notably, features like 'nb_tilde,' 'nb_star,' 'nb_dslash,' 'punycode,' and 'port' exhibit low average values, suggesting limited variation in these characteristics across the dataset. Similarly, columns such as 'abnormal_subdomain,' 'random_domain,' 'path_extension,' and 'nb_external_redirection' demonstrate relatively consistent mean values. Analyzing these averages aids in understanding the typical magnitudes of these features, assisting in the evaluation of their impact on website attributes and contributing to informed decisions during feature selection for machine learning models.

#Mixed ROC curve for multiple models:

<img width="507" alt="image" src="https://github.com/sandeep822/Webpagephishing-using-ML/assets/50867031/7a76b186-41d4-4b3d-a5d5-2be3f71a5945">

The ROC curves and AUC (Area Under the Curve) values provide a comprehensive comparison of the performance of the various models in distinguishing between phishing (positive class) and legitimate (negative class) instances. Logistic Regression, Random Forest, and XGBoost exhibit excellent discrimination capabilities, with AUC values around 0.92-0.95, indicating a strong ability to correctly classify instances while minimizing false positives and false negatives. SVM and CNN also demonstrate solid performance, with AUC values around 0.91-0.93. While Naive Bayes has a slightly lower AUC of 0.87, it still shows reasonable discriminatory power. Overall, the models with the highest AUC values, such as Random Forest and XGBoost, are the most effective in separating the two classes and making accurate predictions, making them the top-performing models in this phishing detection task.











