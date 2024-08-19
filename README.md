# No-Churn Telecom Project

1. Introduction
This project aims to analyze customer data to understand factors influencing customer churn and to build predictive models that can help in identifying customers likely to churn. The project involves data preprocessing, exploratory data analysis (EDA), and the implementation of multiple machine learning models to predict customer churn.

2. Data Preprocessing
Missing Data Handling: Missing values in the dataset were identified and managed appropriately, either by imputation or removal, depending on the extent and importance of the missing data.
Outliers Detection: Outliers were detected using statistical methods and visualizations. These outliers were either removed or transformed to reduce their impact on the model.
Duplicate Records: The dataset was checked for duplicate records, which were then removed to ensure the accuracy of the analysis.
Categorical Variable Conversion: Categorical variables were converted into numerical formats using techniques like Label Encoding, which is crucial for machine learning models that require numerical input.
3. Exploratory Data Analysis (EDA)
Visualizations: Various plots, such as count plots, pie charts, and bar charts, were created to understand the distribution of key variables like customer demographics, state-wise distribution, and plan usage.
Insights:
There are no duplicate values in the dataset.
The dataset has categorical variables like State, International Plan, and VMail Plan, which required transformation.
Certain states and plans have a higher concentration of customers, which might influence churn rates.
4. Machine Learning Modeling
Models Implemented:
Logistic Regression
K-Nearest Neighbors (KNN)
Random Forest Classifier
Decision Tree Classifier
Gradient Boosting Classifier
XGBoost Classifier
Naive Bayes
Support Vector Classifier (SVC)
Model Evaluation:
Models were evaluated using accuracy scores, confusion matrices, and classification reports.
The Random Forest and Gradient Boosting models showed the highest accuracy, making them the best models for this dataset.
5. Results & Insights
Key Factors Influencing Churn:
Customer service call frequency was found to be a significant predictor of churn.
International call plans also had a noticeable impact on churn rates.
Model Comparison:
Random Forest and XGBoost emerged as top performers, with accuracy scores surpassing other models.
The Naive Bayes model, although simple, performed reasonably well and provided a good baseline for comparison.
6. Conclusion
The project successfully identified key factors influencing customer churn and developed predictive models with high accuracy. The Random Forest and Gradient Boosting models are recommended for deployment.

7. Challenges Faced
Data Imbalance: One of the significant challenges was the imbalanced dataset, with a lower proportion of churned customers. This required careful handling to avoid biased model performance.
Feature Selection: Selecting the right features without overfitting the model was crucial, and several iterations were performed to fine-tune the models.
