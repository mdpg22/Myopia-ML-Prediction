# 👁️ Myopia & Myopia Magna Prediction using Machine Learning

Machine Learning project focused on binary and multi-label
classification to predict Myopia (M), Myopia Magna (MM), and related
subtypes using clinical and demographic data from medical students.

------------------------------------------------------------------------

## 🎯 Project Objective

This project aims to develop predictive models for ocular conditions
using structured medical data.

The goals are:

-   Binary classification to predict:
    -   Myopia (M: YES/NO)
    -   Myopia Magna (MM: YES/NO)
-   Multi-class classification:
    -   COMBO → M (Myopia), MM (Myopia Magna), C (Control)
-   Extended multi-class classification:
    -   DCOMBO → M1, M2 subtypes for myopia patients

The ultimate objective is to explore whether demographic and
risk-related variables can effectively predict ocular pathology
categories.

------------------------------------------------------------------------

## 📂 Dataset Description

The dataset contains data from third-year undergraduate students at the
Medical School of the University of Navarra.

Features include:

-   Demographic variables (age, sex, etc.)
-   Clinical measurements
-   Known risk factors associated with myopia development

Training data: - `X_train.csv` - `Y_train.csv`

Test data: - `X_test.csv`

Final predictions: - `resultados_finales.csv`

Note: Labels for the test set were not provided and had to be predicted.

------------------------------------------------------------------------

## 🛠 Technologies Used

-   Python
-   pandas
-   numpy
-   scikit-learn
-   matplotlib / seaborn
-   Jupyter Notebook

------------------------------------------------------------------------

## 🔎 Project Structure

myopia-ml-prediction/ 
│ 
├── Trabajo_final.ipynb \# Main notebook 
├── X_train.csv 
├── Y_train.csv 
├── X_test.csv 
├── resultados_finales.csv \# Final predictions 
└── README.md

------------------------------------------------------------------------

## 📊 Methodology

### 1️⃣ Data Preprocessing

-   Cleaning and validation of input features
-   Encoding categorical variables
-   Train-test separation
-   Feature scaling when required

### 2️⃣ Exploratory Data Analysis

-   Distribution analysis
-   Class imbalance inspection
-   Correlation analysis

### 3️⃣ Modeling

Models explored for classification tasks:

-   Logistic Regression
-   Random Forest
-   Support Vector Machines
-   Ensemble approaches (if applied)

Separate models were trained for:

-   M prediction
-   MM prediction
-   COMBO classification
-   DCOMBO classification

### 4️⃣ Evaluation Metrics

Depending on the task:

-   Accuracy
-   Precision
-   Recall
-   F1-score
-   Confusion Matrix

For multi-class settings: - Macro and weighted metrics

------------------------------------------------------------------------

## 📈 Key Challenges

-   Multi-label and hierarchical classification structure
-   Potential class imbalance
-   Feature importance interpretation
-   Generalization to unseen test data

------------------------------------------------------------------------

## 📌 Key Insights

-   Binary classification (M and MM) provides clearer separation than
    multi-class tasks.
-   Multi-class COMBO and DCOMBO increase model complexity.
-   Certain demographic and clinical features contribute more strongly
    to prediction performance.

------------------------------------------------------------------------

## 🚀 How to Run

1.  Clone repository:

git clone https://github.com/yourusername/myopia-ml-prediction.git

2.  Install dependencies:

pip install -r requirements.txt

3.  Open the notebook:

Trabajo_final.ipynb

4.  Run all cells to reproduce results.

------------------------------------------------------------------------

## 📚 Academic Context

This project was developed as part of a Master's level Machine Learning
/ Data Science coursework.

------------------------------------------------------------------------

## 📬 Author

Manuel de Prado García\
Master Data Analysis\
Specialization in AI, Data Science & Data Anlysis
