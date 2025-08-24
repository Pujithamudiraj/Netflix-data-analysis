# Netflix-data-analysis
📌 Introduction
This project applies Machine Learning (ML) to classify whether a Netflix title is a Movie or TV Show.  
It uses structured features such as duration and number of genres to train and evaluate a classification model.


🎯 Problem Statement
The goal is to build a predictive model that can determine if a Netflix title is a Movie or TV Show based on its attributes.  
This helps in:
- Understanding Netflix content distribution.
- Assisting recommendation systems.
- Automating classification of new titles.

 ⚙️ Techniques and Tools Used
- Python: Programming language for ML and data processing.
- Pandas: For data cleaning and preprocessing.
- Scikit-learn: For ML model training and evaluation.
- Matplotlib & Seaborn: For visualization of results.

Machine Learning Model
- RandomForestClassifier was used because:
  - It handles categorical and numerical data effectively.
  - Provides feature importance insights.
  - Robust against overfitting compared to single decision trees.


 📊 Results & Reports
- The model predicts Movie vs TV Show with high accuracy.
- Classification Report includes Precision, Recall, F1-Score, and Accuracy.
- Visualization includes:
  - Confusion Matrix (to show correct vs incorrect predictions).
  - ROC Curve (to measure performance).
  - Feature Importance chart.

 ✅ Conclusion
- The ML model successfully predicts whether a Netflix title is a Movie or TV Show.  
- Accuracy depends on the chosen features (duration, genres, country, etc.).  
- This project can be extended into a Recommendation System using content similarity.

