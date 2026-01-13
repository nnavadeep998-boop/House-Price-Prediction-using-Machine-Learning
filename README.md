# House-Price-Prediction-using-Machine-Learning
This project predicts house prices based on features such as area, number of bedrooms, bathrooms, and location. A Linear Regression model is trained on housing data to estimate the price of a house. The project demonstrates basic data preprocessing, model training, and evaluation.


| Library                 | Purpose              |
| ----------------------- | -------------------- |
| `numpy`                 | Numerical operations |
| `pandas`                | Data handling        |
| `matplotlib`            | Data visualization   |
| `sklearn.cluster`       | K-Means clustering   |
| `sklearn.preprocessing` | Feature scaling      |


Algorithm Used
Linear Regression
Linear Regression models the relationship between independent variables and the house price by fitting a best-fit straight line.

The required libraries are imported for numerical computation, data handling, model training, and evaluation.
A small housing dataset is manually created and converted into a Pandas DataFrame.
Independent variables such as area, bedrooms, and bathrooms are selected as input features, and price is used as the target variable.
The dataset is divided into training and testing sets using an 80–20 split.
A Linear Regression model is trained using the training data.
The trained model predicts house prices for the test data.
Model performance is evaluated using Mean Absolute Error, Mean Squared Error, and R² score.
