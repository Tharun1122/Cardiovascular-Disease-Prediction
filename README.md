#Cardiovascular Disease Prediction using Feature Selection and Machine Learning

Predicting cardiovascular diseases (CVD) can save lives by enabling early interventions and personalized healthcare plans. This project leverages feature selection techniques (LASSO, LLBFS) and machine learning models (Random Forest, Logistic Regression, K-Nearest Neighbors, Decision Tree) to predict heart disease with high accuracy.

We experimented with various feature selection methods to improve model efficiency and identify the most significant predictors.

Project Structure :

📁 Cardiovascular-Disease-Prediction
│
├── data/                  # Dataset files
│   └── heart_disease_dataset.csv
│
├── notebooks/             # Jupyter notebooks for EDA and modeling
│   ├── 1_EDA.ipynb
│   ├── 2_Feature_Selection.ipynb
│   └── 3_Model_Training.ipynb
│
├── src/                   # Python scripts for modular implementation
│   ├── preprocess.py
│   ├── feature_selection.py
│   ├── train_models.py
│   └── evaluate_models.py
│
├── results/               # Visualizations and evaluation results
│   ├── lasso_accuracy.png
│   ├── llbfs_accuracy.png
│   └── confusion_matrices/
│
├── main.py                # Main execution script
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation

Features

✅ Predicts cardiovascular disease based on patient data
✅ Implements advanced feature selection techniques for improved model performance
✅ Compares multiple ML models for best accuracy
✅ Visualizes results with clean graphs and charts
✅ Modular code for easy customization and experimentation

⸻

📊 Results

We compared model accuracies after applying LASSO and LLBFS feature selection techniques:

Best Model:
✔ Logistic Regression + LASSO Feature Selection
✔ Achieved 91.24% accuracy
✔ Reduced dimensionality and improved interpretability
