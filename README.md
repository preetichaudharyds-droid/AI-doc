🩺 AI Doctor – Disease Prediction System
📌 Overview

AI Doctor is a machine learning-based web application that predicts possible diseases based on user-input symptoms. It provides quick and intelligent predictions using trained ML models and a user-friendly interface.

🚀 Features
🔍 Predict diseases based on symptoms
👤 User authentication (Login & Signup)
📊 Stores prediction history
🌐 Web-based interface using Flask
⚡ Fast and real-time predictions
🧠 Machine Learning model using Scikit-learn
🛠️ Tech Stack

Frontend:

HTML
CSS
JavaScript

Backend:

Python
Flask

Database:

SQLite (via Flask-SQLAlchemy)

Machine Learning:

NumPy
Pandas
Scikit-learn
📂 Project Structure
AI-Doctor/
│
├── static/                # CSS, JS, images
├── templates/            # HTML files
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── history.html
│   └── ...
│
├── models/               # Trained ML model
│   └── model.pkl
│
├── main.py               # Main Flask app
├── models.py             # Database models
├── users.db              # SQLite database
├── requirements.txt      # Dependencies
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/ai-doctor.git
cd ai-doctor
2️⃣ Create virtual environment
python -m venv venv
venv\Scripts\activate   # Windows
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Run the application
python main.py
5️⃣ Open in browser
http://127.0.0.1:5000/
🧠 How It Works
User enters symptoms in the web interface
Symptoms are converted into a numerical vector
The trained ML model predicts the disease
Result is displayed instantly
Prediction is stored in user history
📊 Machine Learning Model
Algorithm: Support Vector Machine (SVM)
Data preprocessing:
Label Encoding
Feature Vectorization
Input: Symptoms
Output: Predicted Disease
🔐 Authentication Features
User Signup
Login/Logout
Password hashing for security
User-specific prediction history
📸 Screenshots (Optional)

Add screenshots of your UI here

📈 Future Improvements
Add more diseases and datasets
Improve model accuracy
Add chatbot integration
Voice input support
