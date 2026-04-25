AI Course Copilot
AI Course Copilot helps students choose the right courses based on their profile, academic history, and career goals. Instead of relying on scattered resources, students can ask questions in natural language and get personalized recommendations instantly.

🚀 Features
🤖 AI-powered course recommendations

📊 Personalized suggestions based on user context

💬 Natural language queries

🛠️ Tech Stack
Frontend: Streamlit

Backend: FastAPI

AI: Hugging Face API

Data: JSON-based course dataset

📁 Project Structure
project/
│
├── app.py
│
├── main.py
├── data.json
│
├── .env
├── requirements.txt
└── README.md
⚙️ Setup Instructions
1. Clone the repo
git clone <your-repo-link>
cd project
2. Create Virtual Environment
python -m venv .venv
Activate it:

Mac/Linux:

source .venv/bin/activate
Windows:

.venv\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt
4. Set up .env file
Create a .env file in the root directory:

HF_TOKEN=your_huggingface_api_key_here
5. Run Backend
cd backend
uvicorn main:app --reload
Runs at:

http://127.0.0.1:8000
6. Run Frontend
In a new terminal:

streamlit run app.py
