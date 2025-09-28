🧠 Breast Cancer Classification using Decision Trees 🚀
📌 Project Overview

This project focuses on building a Machine Learning model to classify tumors as Malignant (M) or Benign (B) using a Decision Tree Classifier. The workflow includes data loading, cleaning, visualization, preprocessing, model training, evaluation, and hyperparameter tuning.

📂 Workflow Summary
✅ 1. Importing Required Libraries

The project begins with importing essential libraries for data processing (Pandas, NumPy), visualization (Matplotlib, Seaborn), and Machine Learning (Scikit-learn).

📁 2. Loading the Dataset

The dataset is loaded from a CSV file and examined using functions like .head(), .shape, .isnull().sum() to understand its structure and check for missing values.

🧹 3. Data Cleaning & Column Fixing

File path verification using os.getcwd().

Column names are stripped to remove extra spaces.

The diagnosis column is identified automatically (case insensitive).

📊 4. Target Variable Visualization

Counts of each diagnosis type (Malignant vs Benign) are calculated.

A bar plot is displayed with value labels to show class distribution.

🔢 5. Encoding Labels

The diagnosis column is converted into numeric values:

M → 1 (Malignant)

B → 0 (Benign)

🗑 6. Removing Irrelevant Columns

The id column is dropped as it does not contribute to model training.

✂️ 7. Splitting Data

Features (X) and target (y) are defined.
Data is split into Training (80%) and Testing (20%) sets.

🌳 8. Training the Decision Tree Model

A Decision Tree Classifier is trained on the dataset and predictions are made.

✅ 9. Model Evaluation

Accuracy score is calculated on the test data to measure performance.

🔍 10. Hyperparameter Tuning (Max Depth)

A loop iterates through tree depths from 1 to 20, printing:

Training Accuracy

Cross-validation Score

This helps identify the optimal depth to prevent overfitting or underfitting.

🏁 Final Outcome

You now have a fully functional Breast Cancer Classification Model with:

✔ Cleaned dataset
✔ Visualized target distribution
✔ Trained Decision Tree Model
✔ Evaluated Accuracy
✔ Tuned Hyperparameters for best performance

🌟 Next Enhancements (Optional Ideas)

Compare with Random Forest / SVM / Logistic Regression

Visualize the Decision Tree structure

Deploy using Streamlit or Flask
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/2fdc4d4d-7a9e-4580-a2ce-5f9008d922ef" />
