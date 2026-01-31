# 🎓 Student Performance Prediction (ML Project)

This project uses a dataset generated from a student database to build a simple **machine learning model** that predicts whether a student will **pass or fail** a course based on academic and enrollment data.

It combines **SQL (database design)** and **Python (machine learning)** to show how real-world data can be used for predictive modeling.

---

## 📌 Project Goals
- Extract structured data from a relational database  
- Prepare the data for machine learning  
- Train a classification model  
- Predict student performance (Pass / Fail)  
- Practice end-to-end ML workflow  

---

## 🗃️ Data Source
The dataset was generated from a MySQL database containing:
- Students  
- Courses  
- Enrollments  
- Attendance  
- Grades  

Data was exported using SQL queries and saved as a CSV file for ML processing.

---

## 🧠 Machine Learning
**Model used:** Logistic Regression  
**Task:** Classification (Pass / Fail prediction)

### Features used:
- Attendance  
- Enrollment data  
- Course data  
- Student data  

### Target:
- Pass/Fail label based on grade logic  

---

## 📊 Model Output
The model was evaluated using:
- Accuracy score  
- Confusion matrix  
- Classification report  

This shows how well the model predicts student performance.

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- Scikit-learn  
- Jupyter Notebook  
- MySQL  
- SQL  
- GitHub  

---

## 📁 Project Structure
student-passfail-ml/
│
├── data/
│ └── student_ml_data.csv
│
├── notebook/
│ └── student_ml_model.ipynb
│
└── README.md

## 🎯 Purpose

This project was created as a learning project to improve my understanding of:
- How databases can be used for machine learning
- How to prepare real-world data for ML models
- How to build and evaluate a simple prediction model
- How SQL and Python can work together in real applications

It is also part of my personal portfolio as I work towards becoming a **machine learning engineer**.
