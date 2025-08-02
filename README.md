# 📊 Bank Marketing Dataset - EDA & Classification

This project performs **data cleaning**, **exploratory data analysis (EDA)**, and builds a **Decision Tree Classifier** using the **Bank Marketing dataset**, where the objective is to predict whether a client will subscribe to a term deposit.

---

## 📁 Dataset

- **Name:** bank-full.csv
- **Source:** UCI Machine Learning Repository
- **Rows:** ~45,000 entries
- **Target Variable:** `y` (binary: "yes" or "no")

---

## 📌 Objectives

- Perform data cleaning and preprocessing
- Explore relationships and trends in client data
- Build and evaluate a Decision Tree model to classify client subscription

---

## 🛠️ Libraries Used

- `pandas`, `numpy` for data handling
- `seaborn`, `matplotlib` for visualizations
- `sklearn` for modeling and evaluation

---

## 🧹 Data Preprocessing

- Removed irrelevant features: `duration`, `pdays`, `contact`, `day`, `month`
- Converted categorical variables using `LabelEncoder`
- Split data using `train_test_split`

---

## 📊 Exploratory Data Analysis (EDA)

- Checked class balance in the target (`y`)
- Analyzed distributions of features like:
  - Age
  - Job
  - Marital status
  - Education
  - Loan & housing status

---

## 🤖 Model Building

- Used `DecisionTreeClassifier` from scikit-learn
- Visualized decision tree structure
- Evaluated using:
  - Confusion matrix
  - Accuracy score
  - Classification report

---

## ✅ Results

- Basic tree model was trained and evaluated.
- Metrics include precision, recall, F1-score, and overall accuracy.
- Useful insights drawn from feature relationships with target variable.

---

## 📂 Project Structure
📦Bank-Marketing-EDA
┣ 📄 bank-full.csv
┣ 📄 Bank_EDA_Tree.ipynb
┗ 📄 README.md

 
