# 🚀 Decision Tree Classification - Car Evaluation Dataset

## 📌 Project Overview
This project is part of my **30-day data science challenge** where I complete one project per day using different machine learning models. On **Day 3**, I implemented a **Decision Tree Classifier** on the **Car Evaluation dataset** to predict car acceptability based on various categorical features.

## 📂 Dataset
- **Source**: Car Evaluation Dataset[https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set]
- **Description**: The dataset consists of **1,727 instances** with **6 categorical features**:
  - **buying** 💰: Cost of buying the car (vhigh, high, med, low)
  - **maint** 🔧: Maintenance cost (vhigh, high, med, low)
  - **doors** 🚪: Number of doors (2, 3, 4, 5more)
  - **persons** 🧑‍🤝‍🧑: Number of persons it can hold (2, 4, more)
  - **lug_boot** 🎒: Size of luggage boot (small, med, big)
  - **safety** ⚠️: Safety rating (low, med, high)
- **Target Variable**:
  - ✅ unacc (Unacceptable)
  - ✅ acc (Acceptable)
  - ✅ good (Good)
  - ✅ vgood (Very Good)

## 🚀 Technologies Used
- **Python** 🐍
- **Pandas & NumPy** 📊 – Data handling and preprocessing
- **Scikit-Learn** 🤖 – Machine Learning (Decision Tree Classifier)
- **Matplotlib & Seaborn** 📈 – Data visualization
- **Graphviz** 🌳 – Decision Tree visualization

## 📜 Project Workflow
### 1️⃣ Data Preprocessing
✅ Loaded and explored the dataset
✅ Checked for missing values and performed data cleaning
✅ Converted categorical features into numerical using **Ordinal Encoding**
✅ Split the dataset into **training (67%)** and **testing (33%)** sets

### 2️⃣ Model Training & Evaluation
✔ Implemented **Decision Tree Classifier** using `sklearn.tree.DecisionTreeClassifier`
✔ Used two splitting criteria:
   - **Gini Index** 🎲
   - **Entropy (Information Gain)** 📊
✔ Trained models with **max_depth=3** to prevent overfitting
✔ Evaluated model accuracy:
  - **Gini Index Accuracy**: **80.53%**
  - **Entropy Accuracy**: **80.53%**
✔ Visualized decision trees using `graphviz` and `tree.plot_tree`
✔ Compared training and test accuracy to check for overfitting

## ⚡ Results & Insights
🔹 The Decision Tree classifier achieved **80.5% accuracy**, showing good performance on categorical data.
🔹 Both **Gini Index** and **Entropy** provided the same accuracy in this case.
🔹 Decision Trees are easy to interpret and visualize, making them useful for classification problems with categorical variables.

## 🔥 Next Steps
🚀 Implement **pruning techniques** to optimize the decision tree.
🚀 Perform **hyperparameter tuning** (`max_depth`, `min_samples_split`).
🚀 Compare Decision Tree with **other classifiers** like **Random Forest** and **SVM**.

---
🛠️ **This is part of my 30-day challenge where I explore different ML models daily. Stay tuned for Day 4!** 🎯

📌 **Author**
Ishmeen Garewal

