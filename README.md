Diabetes Prediction using Machine Learning
📌 Project Overview

This project aims to predict whether a person is diabetic or not using Machine Learning techniques. The model is trained on a diabetes dataset and uses important health parameters to make predictions.

🎯 Objectives
Build a machine learning model for diabetes prediction
Compare multiple algorithms
Provide user-based prediction using selected features
Improve accuracy using preprocessing and scaling

📊 Dataset
Dataset: Diabetes Dataset (diabetes.csv)
Number of Features: 8
Target Variable:
0 → Not Diabetic
1 → Diabetic
Features:
  Pregnancies
  Glucose
  Blood Pressure
  Skin Thickness
  Insulin
  BMI
  Diabetes Pedigree Function
  Age
  
⚙️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook

🤖 Machine Learning Models Used
Logistic Regression ✅ (Final Model)
Decision Tree
K-Nearest Neighbors (KNN)

🔄 Methodology
Data Collection
Data Preprocessing
Train-Test Split (80/20)
Feature Scaling using StandardScaler
Model Training
Model Evaluation
Prediction using user input

📈 Evaluation Metrics
Accuracy Score
Confusion Matrix
Classification Report

🧠 Special Feature (User Input Prediction)
User enters only:
Glucose
BMI
Age
Remaining features are filled using mean values of dataset
This ensures proper prediction even with limited input

🖥️ Sample Output
Enter Patient Details:
Glucose: 148
BMI: 33.6
Age: 50
Prediction: Diabetic

📊 Visualizations
Feature distribution graphs
Correlation heatmap
Confusion matrix
Model comparison chart
KNN K-value analysis

✅ Conclusion
Machine Learning models can effectively predict diabetes
Logistic Regression provided the most stable performance
The system helps in early detection and decision-making

🚀 Future Enhancements
Add GUI (Tkinter / Web App)
Deploy using Flask or Streamlit
Use advanced models (Random Forest, XGBoost)
Improve accuracy with hyperparameter tuning

👨‍💻 Author
Yashwanth D N

📎 How to Run
pip install pandas numpy matplotlib scikit-learn
jupyter notebook diabetespredection.ipynb
