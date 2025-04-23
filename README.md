# 📊 Baby Weight Prediction Project
This project aims to predict newborn baby weights based on maternal and paternal characteristics using a variety of machine learning models. The notebook includes thorough data preprocessing, exploratory data analysis, multiple model evaluations, and optional deployment through an interactive Gradio interface.

Key techniques used:
- **Data Cleaning & Processing**
- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Multiple Regression Models with Regularization**
- **Model Performance Evaluation**

## 🛠 Data Preprocessing:
- **Handling Missing Values:** Filled or removed where necessary.
- **Outlier Detection & Treatment:** Used **Interquartile Range (IQR) Winsorization** to mitigate extreme values.
- **Feature Encoding:** Converted categorical variables into numerical format.
- **Scaling & Normalization:** Standardized numerical features for better model performance.

## 📈 Exploratory Data Analysis (EDA)
Key insights obtained:
- **Distribution of Baby Weight:** The highest number of pregnancies resulted in babies weighing between 6 to 10 kgs.
- **Visualization Techniques:** Used **histograms and bar charts** to understand data trends.

## 🔮 Regression Models

- **Linear Regression**
- **Ridge and Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Support Vector Regressor (SVR)**
- **K-Nearest Neighbors Regressor (KNN)**
- **XGBoost Regressor**

## 📈 Model Performance
Performance was evaluated using:
Root Mean Squared Error (RMSE)
R-squared (R²) Score

Each model's output was compared using these metrics to determine the best-performing algorithm for this dataset. Models like Gradient Boosting and XGBoost often showed superior performance due to their ability to handle non-linear patterns and feature interactions.
so i have used **XGBoost** Regressor to predict the weight of baby.

## 📊 Key Observations
- The baby’s birth weight correlates positively with gestation weeks and maternal weight gain.
- Smoking during pregnancy (CIGNUM) negatively impacts baby weight.
- Education level and age of parents also showed slight correlations with the outcome.
- Ensemble models consistently outperformed linear models.

## 🖥️ Gradio App (Optional)
An interactive user interface is built using Gradio, allowing users to input custom features and receive predicted baby weight in real time.

## 🚀 Installation & Usage
### Prerequisites:
Ensure you have **Python 3.x** installed along with the required dependencies.

### 📦 Install Required Libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost tensorflow gradio
```

### 🔧 Running the Project:
1. Clone the repository:
   ```bash
   git clone https://github.com/Sahil00017/Birth-Weight-Prediction
   ```
3. Navigate to the project folder:
   ```bash
   cd car-price-regression
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook "Birth-Weight-Prediction"
   ```
4. Deactivate the virtual environment when you're done:
   ```bash
   deactivate
   ```

