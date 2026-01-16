# Mini-AI-ML-Project

## Project Overview
This project is a mini AI/ML research project based on a real-world public dataset (Titanic dataset).  
The work includes complete machine learning steps such as data cleaning, preprocessing, model building, and evaluation.  
A report is also created to explain the project workflow and results.

---

## Objective
- Clean and prepare a public dataset for machine learning
- Handle missing values and convert categorical data into numerical form
- Build a classification model using scikit-learn
- Evaluate the model using standard performance metrics
- Share the code on GitHub and present results in a report (Slides/PDF)

---

## Dataset Used
**Titanic Dataset (Public Dataset)**  
**Target Column:** `Survived`  
- `0` = Not Survived  
- `1` = Survived  

---

## Tools & Technologies
- Python
- Google Colab / Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization)
- GitHub (for code hosting)

---

## Steps Performed

### 1) Data Cleaning & Preprocessing
- Checked missing values
- Filled missing `Age` values using **median**
- Filled missing `Embarked` values using **mode**
- Dropped unnecessary columns like `Cabin`, `Ticket`, `Name`
- Applied **One-Hot Encoding** for categorical columns (`Sex`, `Embarked`)

### 2) Model Building
- Split dataset into training and testing sets
- Trained a **Random Forest Classifier**

### 3) Model Evaluation
The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## Results
**Accuracy:** `0.8212` (82.12%)

**Confusion Matrix:**
