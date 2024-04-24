# Welcome to How to Survive the Titanic 101
Mini-Project for SC1015 - Introduction to Data Science and Artificial Intelligence

## About
This is our mini-project for SC1015 using the [Titanic](https://www.kaggle.com/c/titanic/overview) dataset we obtained from Kaggle.

## Table of Contents
1. Introduction & Problem Definition
2. Code
3. Models Used
4. Insights & Conclusion
5. Learning Points
6. Individual Contributions
7. References

## Introduction & Problem Definition
The sinking of RMS Titanic in 1912 is perhaps the most infamous maritime disaster, with over 1,500 passengers and staff dying in the disaster. Hence, we wanted to find out:
1. What are the main factors contributing to whether one survives or not;
2. Whether one of us, Jun Han, would be able to survive if he were onboard the Titanic.

## Code
- [Data Extraction and Exploratory Data Analysis](https://github.com/CUSTEDLOL/titanic-survival/blob/main/Data_Extraction_EDA.ipynb)
- [Machine Learning Models](https://github.com/CUSTEDLOL/titanic-survival/blob/main/Machine_Learning.ipynb)

## Models Used
- Random Forest
- Decision Tree
-	KNN
-	Logistic Regression
-	Naive Bayes
-	Stochastic Gradient Decent
-	Linear SVC
-	Perceptron

![Prediction Scores](https://github.com/CUSTEDLOL/titanic-survival/assets/23294168/b0ef41d3-e1bb-43fe-ad21-04c9c780320d)

The models were ordered according to their accuracy and we found that perceptron performed the worse whereas random forest performed the best.
The Titanic dataset contains non-linear relationships and interactions between features that can be well captured by the random forest model.

## Insights & Conclusion
- The age, gender and fare paid by a passenger are the most important factors determining survivability onboard.
- Jun Han would unfortunately not survive if he were onboard the Titanic. However, if he were to be female, he would have survived.

## Learning Points
- Data Exploration: Focused on understanding the distribution of variables (age, gender, passenger class, etc.), looked for missing data, or explore correlations between different factors
- Feature engineering in Data Cleaning to extract only the crucial information
- Machine learning model training as well as determining which is a better model
- Model validation and finetuning
- Interpretating the results and applying examples on the model
- Visualisations so that readers are able to better visualise the processes

## Individual Contributions
- Jun Han (@jhthenub): Data preparation, exploratory data analysis
- Vishesh (@CUSTEDLOL): Binary Classification and Correlation
- Jet (@j370): Machine learning, data driven insights

## References
- https://www.kaggle.com/c/titanic/overview
- https://www.britannica.com/topic/Titanic
