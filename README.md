# Laptop_price_predictor
Laptop Price Predictor
This project builds a machine learning model to predict laptop prices based on various configurations, such as brand, RAM, CPU, GPU, and more. The model leverages a stacking approach using scikit-learn, combining multiple regression models to enhance predictive accuracy.

Overview
The Laptop Price Predictor is designed to estimate laptop prices based on key features like brand, type, RAM size, weight, touchscreen capability, screen size, CPU, GPU, storage, and operating system. It employs a stacked regression model that integrates Random Forest, Gradient Boosting, and XGBoost, with Ridge regression as the final estimator.

Dataset
The dataset includes various laptop configurations and their corresponding prices. Features include brand, type, RAM, weight, touchscreen, IPS display, screen size, screen resolution, CPU, HDD, SSD, GPU, OS, and price.

Modeling Process
Data Preprocessing
Categorical features are transformed, missing values are handled, and numerical features are scaled to prepare the data for modeling.

Model Selection
The model uses a stacking approach, combining:

Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor
These models are stacked, with Ridge regression serving as the final estimator.

Model Evaluation
The model’s performance is evaluated using the R² score and Mean Absolute Error (MAE) to ensure accurate predictions.

Exporting the Model
The trained model and dataset are saved using pickle for future use.

Usage
Load the model and input new laptop configurations to predict their prices.

Installation
Clone the repository.
Set up a virtual environment.
Install the required dependencies.
Contributing
Contributions are welcome. Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License.
