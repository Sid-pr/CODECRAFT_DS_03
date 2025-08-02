# 🌳 Customer Purchase Prediction using Decision Tree Classifier

This machine learning project builds a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on their **demographic** and **behavioral data**. It uses the **Bank Marketing Dataset** from the **UCI Machine Learning Repository**.

---

## 🎯 Objective

To classify potential customers into two categories:
- ✅ **Will purchase** the product/service
- ❌ **Will not purchase** the product/service  
based on features such as age, job type, marital status, contact method, previous campaign outcomes, etc.

---

## 📂 Dataset

- **Source**: (https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **Records**: 45,211
- **Target variable**: `y` (yes/no – whether the client subscribed to a term deposit)

---

## 📊 Features Used

| Feature       | Description                        |
|---------------|------------------------------------|
| age           | Age of the client                  |
| job           | Type of job                        |
| marital       | Marital status                     |
| education     | Education level                    |
| default       | Has credit in default?             |
| balance       | Average yearly balance             |
| housing       | Has housing loan?                  |
| loan          | Has personal loan?                 |
| contact       | Contact communication type         |
| campaign      | Number of contacts in this campaign|
| previous      | Number of contacts before this     |
| poutcome      | Outcome of previous campaign       |
| ...           | And more...                        |

---

## 🛠️ Technologies Used

- Python 🐍
- Scikit-learn
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🧠 Model Summary

- **Model**: Decision Tree Classifier
- **Preprocessing**: 
  - Categorical encoding
  - Handling class imbalance
  - Train-test split
- **Evaluation Metrics**:
  - Accuracy
---

## 📈 Results

- Achieved **91.49% accuracy** on the test set.
- Feature importance and tree depth were analyzed to avoid overfitting.

---

## 🔍 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Sid-pr/CODECRAFT_DS_03.git
   cd customer-purchase-decision-tree

2. Install Dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the notebook:
   ```bash
   jupyter notebook Bank_decision_tree.ipynb
