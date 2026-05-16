# Real-Time-Public-Transport-Delay-Prediction
📌 Project Overview

This project focuses on predicting real-time public transport arrival delays using Machine Learning techniques.
The system analyzes factors such as traffic congestion, weather conditions, operational delays, and event-related information to estimate transport delay in minutes.

The project compares multiple regression models and selects the best-performing model for accurate delay prediction.

🎯 Objectives
* Predict public transport arrival delays in real time
* Analyze the impact of traffic, weather, and operational factors
* Compare different regression algorithms
* Build a deployment-ready machine learning model

🛠️ Technologies Used
Programming Language

* Python

Libraries
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn


📂 Dataset Information

The dataset contains:

* Traffic conditions
* Weather information
* Operational delay details
* Event-related data
* Transport type information

🎯 Target Variable
* actual_arrival_delay_min

⚙️ Project Workflow
* 1️⃣ Data Collection & Understanding
Loaded and explored the dataset
Checked data types and missing values
* 2️⃣ Data Preprocessing
Handled missing values
Filled missing values in event_type with "None"
Encoded categorical variables using One-Hot Encoding
* 3️⃣ Exploratory Data Analysis (EDA)

Performed:

* Univariate Analysis
* Bivariate Analysis
* Correlation Heatmap
* Feature Importance Analysis
  
* 4️⃣ Model Building
Implemented:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor
  
* 5️⃣ Model Evaluation
Models were evaluated using:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

 📊 Model Performance

<img width="1410" height="112" alt="image" src="https://github.com/user-attachments/assets/80180d6f-2756-4655-9956-c5e58f080920" />

🏆 Final Model Selection
✅ Selected Model: Random Forest Regressor

Why Random Forest?
* Best overall performance
* Handles non-linear relationships effectively
* Robust to noisy real-world data
* Better generalization capability
  
📈 Key Insights
* Delay propagation was the strongest predictor of arrival delays
* Traffic congestion and weather conditions influenced delays
* Tree-based models significantly outperformed linear regression

🚀 Future Scope
* Integration with live GPS and traffic APIs
* Deployment using Flask/FastAPI
* Real-time dashboard for commuters
* Mobile application integration
* Deep learning approaches for large-scale datasets

📌 Conclusion

This project demonstrates how machine learning can improve public transport systems by predicting delays in real time. Among all evaluated models, Random Forest achieved the best performance and proved suitable for practical deployment scenarios.
