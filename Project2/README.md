Project 2: Forecasting and understanding the types of STEEL and its materials, dimensions, variations, Faults and Errors - Machine Learning
Tools: Python, Google Colab, Scikit-learn, Linear Regression, Decision Tree, TensorFlow, Neural Networks, Tableau, PowerBI

We loaded the given 'faultsFile.csv'data set and utilized various functions to understand the data. We looked for any non-filled/null values throughout the cleaning process and discovered that there are none. Then we checked for duplicate values and discovered that there were no duplicate entries. Later, we divide the data set into independent and target/fault features, and then into training and testing sets.

First, we applied Linear Regression Classification and discovered an R2(R_Square) of 22%, indicating that this module is less accurate in predicting future input. We then used Decision Tree Classification. We learn that it has a 71% accuracy in predicting the defect aspects of future input. Finally, we used Support Vector Classification, which has a prediction accuracy of 65%.

