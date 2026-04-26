# AI Course Copilot 🤖📚

AI Course Copilot helps students choose the right courses based on their profile, academic history, and career goals. Instead of relying on scattered resources, students can ask questions in natural language and get personalized recommendations instantly.

---

## 🚀 Features

- 🤖 AI-powered course recommendations  
- 📊 Personalized suggestions based on user context  
- 💬 Natural language queries  

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit  
- **Backend:** FastAPI  
- **AI:** Hugging Face API  
- **Data:** JSON-based course dataset  

---

## 📁 Project Structure

project/
├── app.py
├── main.py
├── data.json
├── .env
├── requirements.txt
└── README.md

---

## ⚙️ Setup Instructions

### 1. Clone the repository
git clone <repo-url>
cd project

### 2. Create a virtual environment
python -m venv .venv

Activate it
Mac/Linux - source .venv/bin/activate
Windows - .venv\Scripts\activate

### 3. Install dependencies
pip install -r requirements.txt

### 4. Set up environment variables
Create a .env file in the root directory:
HF_TOKEN=your_huggingface_api_key_here

### 5. Run the backend
uvicorn main:app --reload
Backend runs at: http://127.0.0.1:8000

### 6. Run the frontend
streamlit run app.py
