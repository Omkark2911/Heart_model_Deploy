# Heart_model_Deploy

❤️ Heart Disease Prediction

A Machine Learning project that predicts the likelihood of heart disease based on patient health-related features.

The trained model is deployed as an interactive Streamlit web application using Joblib to load the saved model.

🛠️ Technologies
Python
Pandas
NumPy
Scikit-learn
Joblib
Streamlit
Jupyter Notebook
🔄 Workflow
Data Cleaning
Data Preprocessing
Feature Engineering
Model Training
Model Evaluation
Model Saving using Joblib
Deployment using Streamlit
🤖 Model

The trained classification model is saved using:

joblib.dump(model, "heart_model.pkl")

and loaded in Streamlit using:

model = joblib.load("heart_model.pkl")
🌐 Deployment

The model is deployed using Streamlit, providing a user-friendly interface where users can enter patient information and get a prediction.

📊 Evaluation

The model was evaluated using classification metrics such as:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

▶️ Run Locally
pip install -r requirements.txt
pip3 install streamlit
pip3 install joblib
pip3 install scikit-learn

streamlit run app.py

👨‍💻 Author

Omkar Kambli
