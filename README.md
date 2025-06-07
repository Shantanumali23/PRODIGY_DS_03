📊 Bank Marketing Campaign Classifier
This repository contains the implementation for Prodigy Infotech Internship Task 3 — building and evaluating a machine learning model to predict whether a customer will subscribe (yes) or not (no) to a term deposit after a marketing campaign.

🚀 Project Overview
What’s included:

✅ Data preprocessing (encoding categorical + numerical features)
✅ Handling class imbalance (undersampling / SMOTE)
✅ Decision Tree Classifier training
✅ Performance evaluation using classification metrics
✅ Decision tree visualization

📁 Files
Prodigy_Infotech_Task_3.ipynb: Main Jupyter notebook with the complete code and steps.
bank-full.csv : Data used for train and test the model having 10000+ records.
bank-names.txt : Information about all the attributes of data
🛠️ Main Workflow
Load Data
Import and inspect the dataset.

Preprocess Data
Encode categorical columns as numerical values (0, 1, 2, …).

Resample Data
Apply undersampling or SMOTE to balance the dataset.

Train Model
Train a Decision Tree Classifier on the balanced dataset.

Evaluate Model
Review precision, recall, f1-score, and accuracy.

Visualize
Plot the decision tree structure to understand the splits.

📊 Final Results
              precision    recall  f1-score   support

          no       0.85      0.80      0.82      7908
         yes       0.82      0.86      0.84      8061

    accuracy                           0.83     15969
   macro avg       0.83      0.83      0.83     15969
weighted avg       0.83      0.83      0.83     15969
✅ Accuracy: 83%
✅ Balanced performance across both classes

✨ Future Work
Test additional models (Random Forest, Logistic Regression, XGBoost).
Apply feature selection or dimensionality reduction.
Tune hyperparameters for even better accuracy.
Explore interpretability tools like SHAP or LIME.
👨‍💻 Author
Made by Kunal Biradar
Feel free to connect! 🚀
