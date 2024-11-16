# Heart Disease Prediction
Heart Disease Prediction Model  This project builds a machine learning model to predict the presence of heart disease in patients using 14 key medical records:

•	Features: 	
1.	Age
2.	Sex
3.	Chest pain type 	
4. Resting blood pressure (trestbps)
5. Cholesterol level
6. Fasting blood sugar
7. Resting electrocardiographic results (restecg)
8. Maximum heart rate achieved (thalach)
9. Exercise-induced angina
10. Old peak (ST depression induced by exercise)
11. Peak exercise ST segment
12. Number of major vessels (0-3) colored by fluoroscopy
13. Thalium stress test result
14. Target: Presence or absence of heart disease
    
•	Workflow:
1.	Data Preparation: The dataset was cleaned, processed, and split for training and testing.
2.	Model Selection & Tuning: Various models were tested, with XGBClassifier performing best.
3.	Accuracy: Fine-tuning the model achieved a high accuracy of 92.13%, indicating its robustness.
4.	Evaluation: Model performance was assessed using key metrics such as precision, recall, and F1 score.
   
This repository demonstrates the practical application of Python libraries like Pandas, NumPy, Matplotlib, and Scikit-Learn in machine learning. It showcases end-to-end implementation, including data analysis, visualization, modeling, and optimization.  Note: XGBClassifier was used for its ability to handle imbalanced datasets and achieve high predictive accuracy of 92.13%.
