💳 AltScore: An Alternative Credit Scoring System
Democratizing credit access using rent, utilities, and transaction data 🚀


📌 Problem Statement
Millions are "credit invisible" due to lacking traditional credit histories. AltScore is a transparent credit scoring solution using alternative data sources like:

📊 Rent Payments

💡 Utility Bills

💳 Cash Flow / Bank Statements

🎓 Education & Employment History

We compute an explainable credit score and offer:

🧠 A dashboard explaining the score

🛠️ Personalized credit improvement tips

🕵️ Fair and bias-aware predictions

📂 Project Structure
bash
Copy
Edit
.
├── data/                   # Sample alternative data files
├── models/                 # Trained ML models (or saved pipelines)
├── dashboard/              # Streamlit / React frontend
├── app.py                  # Main backend server (Flask/FastAPI)
├── scoring_engine.py       # Score calculation logic
├── explainability.py       # SHAP / LIME model explainers
├── utils.py                # Data cleaning + transformation
├── requirements.txt
└── README.md

🔧 Setup Instructions
🔹 Option 1: Run Locally (Python 3.8+)
bash
Copy
Edit
# Clone the repo
git clone https://github.com/<your-username>/altscore.git
cd altscore

# Create virtual env
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run dashboard/app.py
