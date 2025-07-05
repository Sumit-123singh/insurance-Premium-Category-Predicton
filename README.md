# 🚑 Insurance Premium Category Prediction
insurance Premium Category Prediction is a machine learning web application designed to predict the insurance premium category—Low, Medium, or High—for individuals based on their personal and financial details.


This project predicts the insurance premium category (e.g., Low, Medium, High) for individuals based on their profile using a Machine Learning model (Random Forest Classifier). The system is built with:

⚙️ FastAPI as the backend API

🔐 Pydantic for data validation

📊 scikit-learn (Random Forest) for model building

🌐 Streamlit for an interactive frontend

🧠 ML Model
Algorithm: Random Forest Classifier (via sklearn)

Features Used:

Age

Weight

Height

Income (LPA)

Smoking habits

Occupation

City

Target: Premium Category (Low / Medium / High)

⚙️  Backend (FastAPI)
Endpoints
POST /predict: Accepts JSON input and returns predicted premium category.




eatures
Input validated using Pydantic

Handles exceptions and bad input gracefully

🌐 Frontend (Streamlit)
Features
User-friendly form to input user details

On submit, calls the FastAPI backend and shows the prediction

Can be hosted easily with Streamlit Cloud or locally


🧪 Example Use Cases
Insurance companies can pre-classify customers

Risk-based pricing for new applicants

Automation in insurance onboarding systems

✅ Future Improvements
Add authentication and user login

Save predictions in a database

Add support for model retraining through frontend

Visualize feature importance

👨‍💻 Author
Sumit Singh
Backend & ML Enthusiast
