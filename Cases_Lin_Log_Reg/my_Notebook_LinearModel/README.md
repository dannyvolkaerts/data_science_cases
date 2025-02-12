Folder structure:
![image](https://github.com/user-attachments/assets/18b13867-27c5-4630-b9b5-d20b58ed9b72)


Energy Consumption Analysis with Linear Regression

Introduction
This project demonstrates the application of a Linear Regression model to analyze and predict energy consumption based on various building characteristics. The goal of this analysis is to evaluate how well different features such as square footage, number of occupants, and appliances used influence energy consumption.

By leveraging statistical methods and machine learning models, the project evaluates the performance of Linear Regression alongside Decision Tree Regression, comparing their predictive capabilities using metrics like Mean Squared Error (MSE) and R² score.

Dataset, The dataset used includes the following columns:
Building Type: Type of building (e.g., residential, commercial).
Square Footage: Total square footage of the building.
Number of Occupants: Number of people occupying the building.
Appliances Used: Count of appliances in the building.
Average Temperature: Average Temperature in the building.
Day of Week: Day of the week as a categorical variable.
Energy Consumption: Energy consumed in kilowatt-hours (kWh).


Methodology, Data Exploration and Preprocessing:
Examined the distribution of data to identify patterns and anomalies.
Conducted feature engineering to ensure all variables are ready for modeling.
Split the data into training and testing subsets.

Model Training and Evaluation:
Trained a Linear Regression model on the training data.
Evaluated the model using Mean Squared Error (MSE) and R² score.
Compared performance with a Decision Tree Regressor.

Cross-Validation:
Performed cross-validation to assess model generalizability.
Calculated cross-validated R² scores to ensure consistent performance across subsets.

Results
Linear Regression:
Mean Squared Error (MSE): 0.0001955
R² Score: 0.9999999997
The Linear Regression model demonstrated near-perfect predictive power, with minimal error and an R² score close to 1.0.

Decision Tree Regression:
Mean Squared Error (MSE): 58496.26
R² Score: 0.9299
While the Decision Tree model provided good performance (93% variance explained), it was significantly outperformed by Linear Regression in terms of accuracy and error.

Cross-Validation:
Cross-validated R² Scores: [1.0, 1.0, 1.0, 1.0, 1.0]
The Linear Regression model generalized exceptionally well across all subsets of the data.

Conclusion
This analysis highlights the superior performance of Linear Regression for modeling energy consumption. The model demonstrated near-perfect predictive accuracy, making it a reliable tool for understanding the relationships between building features and energy use.
