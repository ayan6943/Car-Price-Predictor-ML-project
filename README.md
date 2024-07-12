# Car-Price-Predictor-ML-project
This project implements a machine learning model to predict the selling price of cars based on various features such as brand, model, year, kilometers driven, fuel type, seller type, transmission, and ownership history. The goal is to assist car dealerships, online marketplaces, and individual sellers in determining fair and competitive prices for used cars.

# Key Features
Data Collection: Utilized a dataset containing information about car listings including pricing and specifications.
Data Preprocessing: Cleaned and prepared the dataset by handling missing values, encoding categorical variables using one-hot encoding, and splitting the data into training and testing sets.
Model Selection: Chose Linear Regression as the predictive model due to its simplicity and ability to capture linear relationships between features and car prices.
Model Training: Trained the model on the training dataset and evaluated its performance using metrics such as Mean Absolute Percentage Error (MAPE) and Root Mean Squared Error (RMSE).
Deployment: Created a live demo using Streamlit, allowing users to input car details and get real-time predictions of car prices.
Technologies Used
Python: Programming language used for data preprocessing, model training, and web application development.
Pandas, NumPy: Libraries used for data manipulation and numerical operations.
Scikit-learn: Library used for machine learning model implementation and evaluation.
