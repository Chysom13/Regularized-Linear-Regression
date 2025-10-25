# 🎓 Student Performance Prediction

This project analyzes student performance data and builds predictive models to estimate students' academic outcomes based on multiple features such as study hours, attendance, and other behavioral or demographic variables.

The notebook performs data exploration, visualization, preprocessing, model training, and evaluation using several regression algorithms.

---

## 📊 Dataset

**File:** `Student_Performance.csv`

The dataset contains student-related attributes (e.g., hours studied, previous scores, attendance rate, etc.) and a target variable representing performance or grades.

Typical columns include:

| Feature | Description |
|----------|--------------|
| Hours_Studied | Number of hours spent studying |
| Attendance | Attendance percentage |
| Past_Score | Previous exam score |
| Parental_Support | Level of parental academic support |
| Test_Score | Target variable (student performance) |

> *Note: Actual feature names may vary depending on the dataset.*

---

## 🧠 Project Workflow

### 1. Data Loading and Exploration
- Load the dataset using **pandas**.
- Inspect data shape, info, and summary statistics.
- Check for missing or duplicate records.

### 2. Data Visualization
- Use **Matplotlib** and **Seaborn** for:
  - Correlation heatmaps
  - Distribution plots
  - Pairplots and boxplots to identify patterns

### 3. Data Preprocessing
- Handle missing or inconsistent values.
- Encode categorical features (if present).
- Split data into training and test sets.
- Normalize or standardize numerical features.

### 4. Model Training
Implemented models:
- **Linear Regression**
- **Lasso Regression**
- **Ridge Regression**
- **ElasticNet Regression**

Each model is trained using the **scikit-learn** framework.

### 5. Model Evaluation
- Evaluate models using:
  - R² Score
  - Mean Squared Error (MSE)
  - Cross-validation (`KFold`, `cross_val_score`)
- Compare model performance to identify the best predictor.

---

## ⚙️ Installation & Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/Chysom13/student-performance.git
   cd student-performance
