# House_price_prediction
🏠 House Price Prediction using Linear Regression
💡 Project Title
House Price Prediction using Linear Regression

📝 Project Overview
This project focuses on predicting house prices in California using a Linear Regression model. It uses real-world housing data and analyzes how features like median income, average number of rooms, house age, and population affect housing prices.

The model is built using scikit-learn, and data visualization is performed using Seaborn and Matplotlib to better understand feature relationships and model performance.

🔧 Technologies & Libraries Used
Python – Core programming language

scikit-learn – Machine learning and model building

pandas – Data loading and manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization and plotting

📌 Step-by-Step Explanation
Install Required Libraries
All necessary libraries are installed for data processing, visualization, and modeling (especially useful for platforms like Google Colab).

Import Libraries
Libraries like pandas, NumPy, seaborn, and scikit-learn are used for handling data, building the model, and evaluating performance.

Load Dataset
The project uses the built-in fetch_california_housing() dataset, which contains features such as median income, average rooms, population, and housing prices.

Convert to DataFrame
Data is converted into a pandas DataFrame for easy handling, with the target column renamed to Price.

Explore the Dataset
Dataset structure, types, and summaries are explored using basic pandas functions to understand data distribution.

Visualize the Data
Histograms and scatter plots help in visualizing the distribution and correlation between variables like income, rooms, and price.

Prepare the Data
Features (X) and target (y) are separated, and the data is split into training and testing sets (commonly 80/20 split).

Train the Model
A Linear Regression model is trained on the training data to learn the relationships between the input features and the target price.

Predict House Prices
The trained model is used to predict prices on the test dataset.

Evaluate the Model
Performance is measured using Mean Squared Error (MSE) and R² Score, which give insights into prediction accuracy.

Visualize Results
A scatter plot of actual vs predicted prices helps in visually assessing how well the model performed.

✅ Outcome
The project successfully builds a machine learning model that can predict house prices with reasonable accuracy. It covers important concepts like data preprocessing, visualization, model training, prediction, and evaluation — forming a complete ML workflow suitable for real-world use.

