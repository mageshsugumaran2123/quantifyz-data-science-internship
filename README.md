# 📱 Mobile Price Range Prediction

## Quantifyz Technologies - Data Science Internship

This project was developed as part of my Data Science Internship at Quantifyz Technologies.

The project focuses on analyzing mobile phone specifications and building machine learning models to classify mobile phones into different price ranges.

---

## 🎯 Project Objective

The main objective is to explore mobile phone specifications, identify important patterns and relationships, and develop machine learning classification models for predicting mobile phone price ranges.

---

## 📊 Dataset

The dataset contains 2,000 mobile phone records with 20 input features.

### Target Variable

`PriceRange`

The dataset contains four price categories:

- Low
- Medium
- High
- VeryHigh

Each category contains 500 records.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📚 Tasks Completed

### Level 1

#### Task 1 - Data Exploration
- Dataset loading
- Dataset structure
- Missing value analysis
- Statistical exploration

#### Task 2 - Descriptive Analysis
- Mean
- Median
- Standard deviation
- Distribution analysis
- Feature statistics

#### Task 3 - Data Visualization
- Histograms
- Boxplots
- Count plots
- Correlation heatmap
- Pair plots

### Level 2

#### Task 4 - Feature Engineering
- Feature preparation
- Feature transformation
- Data preprocessing

#### Task 5 - Mobile Specification Analysis
- Mobile specification comparison
- RAM analysis
- Price range analysis

#### Task 6 - Correlation Analysis
- Feature correlation
- Price correlation
- Top correlated features

### Level 3

#### Task 7 - Classification Models
The following machine learning algorithms were implemented:

- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Logistic Regression
- Naive Bayes

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

---

## 📁 Project Structure

```text
QUANTIFYZ_INTERNSHIP_DATASCIENCE/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── images/
│   ├── distributions/
│   ├── histograms/
│   ├── boxplots/
│   ├── heatmaps/
│   ├── comparison/
│   └── confusion_matrix/
│
├── notebooks/
│   ├── Task_01_Data_Exploration.ipynb
│   ├── Task_02_Descriptive_Analysis.ipynb
│   ├── Task_03_Data_Visualization.ipynb
│   ├── Task_04_Feature_Engineering.ipynb
│   ├── Task_05_Mobile_Specification_Analysis.ipynb
│   ├── Task_06_Correlation_Analysis.ipynb
│   └── Task_07_Classification_Models.ipynb
│
├── models/
├── reports/
├── streamlit_app/
├── README.md
├── requirements.txt
└── .gitignore
