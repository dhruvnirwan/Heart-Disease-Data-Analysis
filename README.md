# Heart Disease Data Analysis

This project performs **Exploratory Data Analysis (EDA)** and **feature scaling** on a heart disease dataset.  
The dataset used is `heart.csv`, which contains patient attributes like age, cholesterol, blood pressure, and target variable `HeartDisease`.

---

## Project Steps

### 1. Importing Libraries
- **pandas, numpy**: Data handling
- **seaborn, matplotlib**: Visualization
- **sklearn.preprocessing.StandardScaler**: Feature scaling

### 2. Loading Dataset
- The dataset is loaded using `pd.read_csv('heart.csv')`.
- Basic exploration: `.head()`, `.shape()`, `.info()`, `.describe()`

### 3. Exploratory Data Analysis (EDA)
- Checked duplicate values
- Visualized target variable (`HeartDisease`)
- Reviewed column details and statistics

### 4. Feature Scaling
- Scaled numerical columns: `['Age', 'RestingBP', 'Cholesterol', 'MaxHR', 'Oldpeak']` using `StandardScaler`

---
