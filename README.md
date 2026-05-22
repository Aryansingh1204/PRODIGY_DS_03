# Prodigy InfoTech Data Science Internship - Task 03

## 📌 Project Overview
This repository contains the completion of **Task 3** for the Data Science Internship at Prodigy InfoTech. The objective was to build a **Decision Tree Classifier** to predict whether a customer will purchase a product or service (term deposit) based on their demographic and behavioral data from the Bank Marketing dataset.

## 🛠️ Tools & Libraries Used
* **Python** (Programming Language)
* **Pandas & NumPy** (Data Preprocessing)
* **Scikit-learn** (Machine Learning Model Construction & Evaluation)
* **Matplotlib & Seaborn** (Data Visualization)

## ⚙️ Methodology
1. **Data Preprocessing:** Handled categorical variables by converting them into dummy variables (One-Hot Encoding) so the machine learning model can process them.
2. **Model Training:** Split the data into training (80%) and testing (20%) sets. Initialized and trained a Decision Tree Classifier with a `max_depth` of 5 to prevent overfitting.
3. **Model Evaluation:** Evaluated the model's accuracy on the test set and generated a classification report and confusion matrix to analyze precision, recall, and f1-scores.

## 📊 Results & Visualizations
* **Accuracy:** The Decision Tree model achieved a strong accuracy in predicting customer behavior.
* **Confusion Matrix:** Visualized true positives, true negatives, false positives, and false negatives to understand where the model excels and makes errors.
* **Decision Tree Visualization:** Plotted the actual tree rules the algorithm learned to classify whether a customer will say "yes" or "no" to the marketing campaign.

## 📁 Files in this Repository
* `task3.ipynb`: The Jupyter Notebook containing the code.
* `bank.csv`: The dataset used for model training and testing.
* `decision_tree.png`: The visual representation of the trained model.
* `confusion_matrix.png`: Heatmap of the evaluation matrix.
