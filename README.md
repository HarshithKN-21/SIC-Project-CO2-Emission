# SIC-Project-CO2-Emission

🚗 CO₂ Emissions Prediction Project


📌 Project Overview
This project uses machine learning models (Decision Tree, Random Forest, and Linear Regression) to predict vehicle CO₂ emissions (g/km) based on features such as engine size, fuel type, annual mileage, vehicle age, driving style, and more.
The dataset contains real-world vehicle attributes and emission values, making it useful for exploring data cleaning, feature engineering, and regression modeling.

⚙️ Workflow
1. 	Data Loading
• 	Reads  dataset.
• 	Removes duplicates and handles missing values.
2. 	Data Cleaning & Preprocessing
• 	Numeric missing values filled with mean.
• 	Categorical missing values filled with mode.
• 	One-hot encoding applied to categorical features.
3. 	Model Training
• 	Splits data into training and test sets.
• 	Trains models:
• 	Decision Tree Regressor
• 	Random Forest Regressor
• 	Linear Regression
4. 	Evaluation
• 	Metrics: MAE, MSE, R² Score.
5. 	Visualization
• 	Heatmap of correlations.
• 	Boxplots for numeric features.
• 	Scatter plots (e.g., engine size vs emissions).
• 	Distribution plots of emissions.
• 	Pairplots for feature relationships.

📂 Files
• 	 → Dataset.
• 	 → Main script with preprocessing, training, evaluation, and visualization.
• 	 → Project description and instructions.

🎯 Goals
• 	Build a clean ML pipeline for regression tasks.
• 	Compare different models for accuracy.
• 	Visualize feature relationships and importance.
• 	Provide a reproducible workflow for CO₂ emissions prediction.
