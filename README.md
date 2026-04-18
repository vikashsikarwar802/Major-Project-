# Major-Project- 
🏠 Project Title

House Price Prediction using Regression Techniques

📌 Project Description

This project is a Machine Learning-based House Price Prediction System that predicts the price of a house based on various input features such as area, number of rooms, location, etc.

It uses:

Linear Regression
Random Forest Regressor

Additionally, an interactive dashboard is created using ipywidgets where users can input house details and get real-time predictions.

🎯 Objectives
Predict house prices accurately using ML models
Compare performance of multiple regression algorithms
Provide a user-friendly interface for predictions
Visualize data insights using graphs and charts
🛠 Technologies Used
Python 🐍
Pandas & NumPy (Data Handling)
Matplotlib & Seaborn (Visualization)
Scikit-learn (Machine Learning)
ipywidgets (Interactive Dashboard)
Jupyter Notebook
📂 Dataset
CSV file containing housing data (15k rows approx.)
Features include:
Area
Bedrooms
Location
Other property details
Target variable:
Price
⚙️ Project Workflow
🔹 1. Data Loading
CSV dataset is loaded using Pandas
Initial shape and sample data displayed
🔹 2. Exploratory Data Analysis (EDA)
Dataset information (info())
Missing values check
Statistical summary (describe())
Histograms for numerical features
Correlation heatmap
🔹 3. Data Preprocessing
Missing values handled:
Numerical → median
Categorical → mode
Feature and target separation
One-hot encoding for categorical data
🔹 4. Train-Test Split
Dataset split into:
80% Training
20% Testing
🔹 5. Model Training
📈 Linear Regression
Simple regression model
Learns linear relationship between features and price
🌲 Random Forest Regressor
Ensemble model
Uses multiple decision trees
Provides better accuracy and robustness
🔹 6. Model Evaluation

Metrics used:

R² Score → Accuracy of model
MAE (Mean Absolute Error) → Average error
RMSE (Root Mean Squared Error) → Error magnitude
🔹 7. Visualization
Actual vs Predicted plot
Feature importance (Random Forest)
Model comparison charts
🔹 8. Interactive Dashboard 🎛️

Features:

User inputs house details using sliders/dropdowns
Predict button generates price
Shows:
Linear Regression prediction
Random Forest prediction
Average prediction
Reset option available
📊 Model Comparison
Model	R² Score	MAE	RMSE
Linear Regression	Good	Medium	Medium
Random Forest	Better	Low	Low

👉 Random Forest generally performs better due to non-linear learning.

🚀 How to Run the Project
Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn ipywidgets
Open Jupyter Notebook
Update dataset path:
csv_path = "your_dataset_path.csv"
Run all cells step by step
Use dashboard to predict house prices
📌 Key Features

✔ Data preprocessing handled automatically
✔ Multiple ML models used
✔ Visualization included
✔ Interactive dashboard
✔ Real-time prediction

🔥 Future Enhancements
Add more advanced models (XGBoost, Gradient Boosting)
Deploy as web app (Flask / Streamlit)
Add location-based map integration
Improve UI/UX
Use larger real-world datasets
🧠 Conclusion

This project demonstrates how machine learning can be used to predict house prices effectively.
The combination of:

Data analysis
Model building
Interactive dashboard

makes it a complete end-to-end ML project.
