# 🍷 Wine Quality Prediction ML Pipeline

## 📌 Project Overview

This project focuses on predicting wine quality using Machine Learning classification techniques. The dataset contains physicochemical properties of wine, and the goal is to classify wines as:

- GOOD (Quality ≥ 7)
- BAD (Quality < 7)

The project demonstrates a complete machine learning workflow including data analysis, preprocessing, model training, evaluation, comparison, and optimization.

---

## 🎯 Objective

To build and compare multiple machine learning models for wine quality classification and identify the best-performing model through evaluation and hyperparameter tuning.

---

## 📊 Dataset Information

The dataset contains various physicochemical properties of wine, such as:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality

Target Variable:

- `quality_label = 1` (GOOD) if Quality ≥ 7
- `quality_label = 0` (BAD) if Quality < 7

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview using `head()`
- Data structure inspection using `info()`
- Statistical summary using `describe()`
- Missing value analysis
- Correlation analysis
- Correlation heatmap visualization

---

## ⚙️ Data Preprocessing

Steps performed:

1. Checked for missing values
2. Analyzed feature correlations
3. Converted quality scores into binary labels
4. Separated features and target variable
5. Performed train-test split
6. Applied StandardScaler for feature scaling

---

## 🤖 Machine Learning Models Used

### 1. Logistic Regression
- Trained on original data
- Trained again after Standard Scaling
- Compared performance before and after scaling

### 2. K-Nearest Neighbors (KNN)
- Model training and evaluation
- Hyperparameter tuning using GridSearchCV

### 3. Decision Tree Classifier
- Model training and evaluation
- Feature importance analysis

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🔧 Hyperparameter Tuning

GridSearchCV was used to optimize model performance by identifying the best hyperparameters for the selected model.

---

## 📊 Feature Importance Analysis

Feature importance analysis was performed to identify the variables that most influence wine quality prediction.

Key influential features include:

- Alcohol
- Volatile Acidity
- Sulphates
- Density

*(Results may vary slightly depending on model and train-test split.)*

---

## 🏆 Model Comparison

The following models were compared:

| Model | Accuracy | Precision | Recall | F1-Score |
|---------|----------|----------|---------|----------|
| Logistic Regression | Evaluated | Evaluated | Evaluated | Evaluated |
| KNN | Evaluated | Evaluated | Evaluated | Evaluated |
| Decision Tree | Evaluated | Evaluated | Evaluated | Evaluated |

The best-performing model was selected based on overall evaluation metrics.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📂 Project Workflow

```text
Data Collection
        ↓
Exploratory Data Analysis
        ↓
Data Preprocessing
        ↓
Feature Scaling
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Model Comparison
        ↓
Hyperparameter Tuning
        ↓
Feature Importance Analysis
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/rsumanth1709/wine-quality-prediction-ml-pipeline.git
```

2. Navigate to the project directory

```bash
cd wine-quality-prediction-ml-pipeline
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Open and run the notebook

```bash
jupyter notebook
```

---

## 📚 Learning Outcomes

Through this project, the following concepts were applied:

- Data Analysis
- Data Visualization
- Feature Engineering
- Classification Algorithms
- Model Evaluation
- Hyperparameter Tuning
- Feature Importance Analysis
- Machine Learning Pipeline Development

---

## 👨‍💻 Author

**Reddy Sumanth**

B.Tech AIML Student | Machine Learning Enthusiast

GitHub: https://github.com/rsumanth1709

---

## ⭐ Project Highlights

✅ End-to-End Machine Learning Pipeline

✅ Exploratory Data Analysis (EDA)

✅ Feature Scaling

✅ Multiple Model Comparison
✅ Feature Importance Analysis

✅ Internship Portfolio Project
