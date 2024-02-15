# Telecom-Customer-Churn_Machine-Learning-Project

**Objective**:
The goal is to predict customer churn by analyzing demographic information, account information, and services information of customers. Predicting churn is crucial for retaining existing customers and reducing the costs associated with acquiring new ones.

**Dataset:**
The dataset contains 19 columns, including independent variables like gender, senior citizen status, partner, dependents, tenure, contract type, billing information, payment method, monthly charges, total charges, and various services-related information. The response variable is 'Churn,' indicating whether a customer left the company in the last month (Yes) or not (No).

**Steps in Analysis:**
1. Data Preprocessing and Analysis
Started by reading and storing the data in a Pandas dataframe. Conducted exploratory data analysis (EDA) to understand the data, identify patterns, and clean inconsistencies. Visualized the data using stacked bar plots, histograms, and other methods to observe the influence of different variables on customer churn.
2. Feature Importance and Engineering
Evaluated mutual information scores to analyze the relationship between each independent variable and the response variable (Churn), assessed variable importance, and performed feature engineering by transforming both categorical and numerical variables to enhance compatibility with machine learning models.
3.Algorithm Selection and Model Training
The machine learning algorithm of choice was Gradient Boosting, selected for its widespread use and efficacy in ensemble learning, with a Gradient Boosting Classifier constructed using Scikit-Learn's GradientBoostingClassifier class, subsequently trained and evaluated on the dataset.
4. Hyperparameter Tuning
Employed random search to fine-tune hyperparameters and enhance the performance of the Gradient Boosting Classifier, experimenting with various combinations of parameters like learning rate, number of estimators, max depth, max features, and min samples split, resulting in a model that demonstrated superior accuracy compared to default settings.
5. Model Evaluation
The model's performance was analyzed through the examination of a confusion matrix and diverse metrics such as accuracy, precision, sensitivity, specificity, and F1-score, while also pinpointing both strengths and weaknesses and suggesting potential areas for enhancement.

**Conclusion:**
Stressed the iterative process in machine learning projects, advocating the revisiting of steps as insights accumulate, underscored the significance of comprehending the problem and data, along with continuous refinement, and ultimately culminated in the development of an accurate predictive model for customer churn, offering valuable insights to improve telecommunications company's customer retention strategies.
