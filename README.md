🏡 House Price Prediction
📌 Overview
This project uses the California Housing dataset from Scikit-learn to build a regression model that predicts median house values based on demographic and geographic features. The workflow demonstrates data exploration, visualization, and model evaluation using Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn.

⚙️ Steps in the Project
Data Loading

Fetch dataset using fetch_california_housing()

Convert to Pandas DataFrame

Exploratory Data Analysis (EDA)

Summary statistics and correlations

Visualizations: histograms, scatter plots, heatmaps

Feature Selection & Splitting

Selected features: MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude

Train-test split (80/20)

Model Training

Linear Regression with Scikit-learn

Evaluation Metrics

MAE: 0.53

RMSE: 0.75

R² Score: 0.58

Visualizations

Predicted vs Actual scatter plot

Residuals plot

📊 Findings
Linear Regression explains ~58% of the variance in housing prices.

Median Income is the strongest predictor of house value.

Residuals show non-linear patterns → advanced models (Ridge, Lasso, Random Forest, Gradient Boosting) could improve accuracy.

🚀 How to Run
bash
# Clone the repository
git clone https://github.com/Aravinthan-G-23/House-price-prediction.git
cd House-price-prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook House_Price_Predictor.ipynb

# Or launch Streamlit app
streamlit run app.py
📦 Requirements
Python 3.9+

pandas

numpy

scikit-learn

matplotlib

seaborn

streamlit

📌 Future Work
Add Ridge/Lasso regression for regularization

Compare with tree-based models (Random Forest, Gradient Boosting)

Deploy as a web app with Streamlit
