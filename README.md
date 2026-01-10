# **BANK CUSTOMERS RETIREMENT ANALYSIS**

Developing a model that can predict whether a customer is able to retire or not based on his/her features. Features are his/her age and net 401K savings (retirement savings in the U.S.).

## **About the Dataset**
The dataset is a short one used for this analysis with customer id, age, 401K savings and target variable called "Retire". 

## **Project Overview**

### **Exploratory Data Analysis (EDA) and Preprocessing**
1. **Import Libraries and Load Dataset**
    - Essential libraries are imported, and the dataset is loaded for analysis.

2. **Exploratory Data Analysis (EDA)**
    - **Numerical EDA**: Summary Statistics
        - **Target Variable Analysis**: Insights on the distribution and characteristics of the target variable.
    - **Visual EDA: Data Visualization**: Various visualizations to explore relationships and patterns in the data.
3. **Data Preprocessing**
    * **Data Cleaning and Reduction:** Steps taken to clean the dataset and reduce dimensionality if necessary.
    * **Handling Missing Data:** Strategies employed to address missing values.
    * **Outlier Detection and Treatment:** Identification and treatment of outliers in the dataset.
    * **Feature Engineering:** Creation of new features to enhance model performance.
    * **Data Scaling and Encoding:** Techniques applied to scale numerical features and encode categorical features.
      
4. **Model Development**

    * **Baseline Model Evaluation:** Initial evaluation of various models to establish a performance baseline.
    * **Hyperparameter Tuning with GridSearchCV**
        * **SVM Optimization**: Tuning hyperparameters for the SVM model.
          
=5. **Final Model Evaluation**
    * **Model evaluation:** Evaluating and comparing the performance of the model of base and optimized. USed confusion matrix to check the model as well checking for over/under fitting.
    * **Predictions on the Test Set and Final Evaluation Metrics:** Generating predictions on the test set and calculating final evaluation metrics.
    * **Save the Final Model:** The final model is saved for future predictions and usage.

## **Summary**
This project provides an in-depth exploration of factors affecting bank employees, employing advanced data analysis and machine learning techniques. Through meticulous EDA, preprocessing, and modeling, we aim to deliver actionable insights and a robust predictive model. The findings and methodologies presented in this project can serve as a foundation for better understanding customers for companies who are looking for new people group in the market. 
