# 🎓 Student Performance Analysis

This project analyzes student performance using machine learning techniques. It uses a dataset from Kaggle and applies data preprocessing, visualization, feature engineering, and modeling using the **Random Forest Regressor**. The trained model is deployed using **Flask**, allowing users to input student-related features and receive a predicted average score.

---

## 📊 Dataset

- Source: [Kaggle – Student Performance in Exams](https://www.kaggle.com/spscientist/students-performance-in-exams)
- Rows: 1000
- Columns: 8 (gender, race/ethnicity, parental level of education, lunch, test preparation course, math score, reading score, writing score)

---

## 🚀 Workflow

1. **Dataset Collection**
   - Loaded from Kaggle and read using Pandas.

2. **Feature Engineering**
   - Handled null values.
   - Visualized patterns using seaborn/matplotlib.
   - Explored student performance trends based on gender and test preparation.

3. **Data Preprocessing**
   - Converted categorical features into numerical values.

4. **Model Training**
   - Split data into training and testing sets.
   - Trained a **Random Forest Regressor**.

5. **Evaluation**
   - Achieved **99.7% accuracy** on test data.
   - Compared with other models like Linear Regression and SVM.

6. **Deployment**
   - Built a Flask web app for real-time prediction.
   - Users can enter inputs to get a predicted average score.

---

## 🛠 Tech Stack

- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Flask
- Jupyter Notebook

---


