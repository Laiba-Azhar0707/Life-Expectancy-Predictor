# Life Expectancy Predictor 🧬📊

This project explores a global life expectancy dataset through **Exploratory Data Analysis (EDA)**, **visualization**, and applies a **Linear Regression model** to predict life expectancy based on socio-economic and health indicators.

## 📁 Dataset
- **Source:** WHO / Kaggle ([Life Expectancy Dataset](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who))
- **Files used:**
  - `Life_Expectancy.csv`: Raw dataset
  - `cleaned_life_expectancy.csv`: Cleaned and preprocessed dataset

---

## 🔍 Project Workflow

### 1. Data Cleaning & Preprocessing
- Handled missing values
- Converted categorical variables where necessary
- Removed irrelevant or highly correlated features

### 2. Exploratory Data Analysis (EDA)
- Summary statistics
- Visualizations:
  - Bar Plots
  - Box Plots
  - Voilin Plots
  - Correlation heatmaps
  

### 3. Feature Selection
- Chose key features impacting life expectancy such as:
  - GDP
  - Alcohol consumption
  - Immunization rates
  - Adult mortality

### 4. Model Building
- **Model used:** Linear Regression
- **Training/Test Split:** 80/20
- **Evaluation Metrics:**
  - ✅ R² Score: **0.82**
  - ✅ Mean Absolute Error
  - ✅ Mean Squared Error

---

## 📊 Final Result

The Linear Regression model achieved an **R² score of 0.82**, indicating good predictive power on this dataset. The most influential features were related to **economic strength**, **healthcare access**, and **lifestyle factors**.

---

## 🛠️ Tools & Libraries
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/Laiba-Azhar0707/Life-Expectancy-Predictor.git
   cd Life-Expectancy-Predictor
