🩺 Diabetes Prediction Using Machine Learning
This project uses various machine learning models to predict whether a person has diabetes based on health-related parameters. It includes data preprocessing, model evaluation, visualization, and user prediction functionality.

📁 Dataset
Source: Pima Indians Diabetes Dataset

Shape: (768, 9)

Features:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Outcome (0 = No Diabetes, 1 = Diabetes)

📌 Features
Preprocessing (Missing value handling, scaling)

Multiple ML models:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Support Vector Machine (SVM)

XGBoost (optional)

Model comparison using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix
![image](https://github.com/user-attachments/assets/e9ea7251-970c-4061-b0ae-7e5e3da2c017)


Visualizations for model performance
![image](https://github.com/user-attachments/assets/198c776a-4416-4039-bcdf-7cbeb0a1d876)


Custom prediction using user input

🧠 ML Models Comparison
Each model is evaluated and compared using multiple metrics, and the best-performing model is used for final prediction.

📊 Visualizations
Bar plots for Accuracy, Precision, Recall, and F1 Score across all models.
![image](https://github.com/user-attachments/assets/a800a4d1-0069-4f29-8386-a989278a0812)
![image](https://github.com/user-attachments/assets/7aa119a1-6007-4bac-827d-6ffcb5c16c29)
![image](https://github.com/user-attachments/assets/3b46fdd7-ff19-46fc-b41a-778ee5fdf914)
![image](https://github.com/user-attachments/assets/41a6dbeb-dc94-4357-80ab-5f28c9b8735a)


Confusion matrix for the best model.

🚀 How to Run
🧪 Local Environment
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/diabetes-prediction.git
cd diabetes-prediction
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook

bash
Copy
Edit
jupyter notebook diabetes.ipynb
(Optional): Run the Streamlit UI (if available)

bash
Copy
Edit
streamlit run app.py

✅ Sample Prediction
python
Copy
Edit
sample_input = [3, 130, 78, 25, 100, 28.1, 0.5, 45]
predict_diabetes(sample_input)
Output:

vbnet
Copy
Edit
✅ The person is likely to have diabetes (Probability: 0.84)


