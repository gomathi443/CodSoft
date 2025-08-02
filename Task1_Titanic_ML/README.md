Titanic Survival Prediction - CodSoft Internship Task 1
  This project is part of the CodSoft Data Science Internship. The task is to build a Machine Learning model that predicts whether a passenger survived the Titanic disaster based on various features.
Objective
  To use the Titanic dataset and implement a Random Forest Classifier to predict survival outcomes using passenger information like age, sex, class, and fare.
Dataset
- Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
- Training Data: `train.csv`
- Target Column: `Survived` (0 = No, 1 = Yes)
Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
Key Steps
1. Data cleaning (null values handling, column dropping)
2. Encoding categorical variables (`Sex`, `Embarked`)
3. Splitting dataset into training and test sets
4. Model training using `RandomForestClassifier`
5. Evaluation using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
   - Visualizations
Accuracy Achieved
  82.12% accuracy on test data using Random Forest Classifier.
Output Graphs
   - Confusion Matrix (heatmap)
   - Survival Count Prediction (bar chart)
Conclusion
A basic but effective Titanic survival prediction system was built. The model performed well with an accuracy of ~82%, proving that even basic features can give useful predictions when using ensemble ML models.

