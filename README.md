# Predicting Student Academic Performance Using Machine Learning

This project applies **machine learning regression models** to predict final mathematics grades (G3) of secondary school students in Portugal. Using demographic, behavioral, and academic features, the study compares **Linear Regression, Random Forest, and XGBoost** models.

Exploratory Data Analysis (EDA) highlights the importance of prior grades (G1, G2), failures, and school support. Random Forest outperformed other models with **RMSE 1.85** and **R² 0.83**, showing strong predictive power.

The repository includes the Jupyter Notebook, detailed research report, and preprocessing pipeline for reproducibility. The insights help educators design targeted support strategies to improve student outcomes.

---

## **Features**

* Data preprocessing (outlier removal, one-hot encoding)
* Exploratory Data Analysis (correlation heatmaps, distributions)
* Model training & evaluation (Linear Regression, Random Forest, XGBoost)
* Feature importance analysis
* Research-style report with results and conclusions

---

## **Repository Structure**

```
Predicting-Student-Academic-Performance/
│── README.md
│── requirements.txt
│── student-performance.ipynb
│── report/
│   └── Predicting Student Academic Performance.pdf
│── data/
│   └── student-mat.csv (or link to Kaggle dataset)
```

---

## **Results**

| Model             | RMSE | R²   |
| ----------------- | ---- | ---- |
| Linear Regression | 2.26 | 0.75 |
| XGBoost           | 2.14 | 0.78 |
| Random Forest     | 1.85 | 0.83 |

---

## **Dataset**

* Source: [Kaggle – Student Performance Dataset](https://www.kaggle.com/spscientist/students-performance-in-exams)
* Records: 395 students
* Features: 33 (demographics, behavior, academic performance)

---

## ⚙️ **Installation**

```bash
git clone https://github.com/saisrivatsat/predicting-student-academic-performance.git
cd predicting-student-academic-performance
pip install -r requirements.txt
```
