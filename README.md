# 🧠 Deepseek R1 Chatbot with Ollama & Streamlit
This project is a locally-hosted AI chatbot built using the Deepseek LLM R1 and powered by Ollama for model management and Streamlit for the frontend interface.

# 🚀 Features
Runs entirely locally — no internet or API key required

Powered by the Deepseek R1 LLM

Fast and responsive Streamlit-based chat UI

Simple, clean interface with markdown rendering

Easy to set up and extend

# 🛠️ Tech Stack
Ollama: Local model runner and management CLI

Deepseek R1 LLM: Downloaded and loaded through Ollama

Streamlit: Interactive web UI for chatbot interaction

Langchain

Python 3.9+

# 📦 Setup Instructions
1. Install Ollama
Download and install Ollama from: https://ollama.com/download

Make sure ollama is accessible from your terminal.

# 2. Download Deepseek R1
In your terminal, run:
bash
Copy
Edit
ollama run deepseek
Ollama will automatically download and prepare the Deepseek R1 model.

# 3. Clone this Repository

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# 4. Install Dependencies

pip install -r requirements.txt

# 5. Run the Chatbot

streamlit run app.py
The chatbot will open in your browser at http://localhost:8501.

# 📁 File Structure
bash
Copy
Edit
├── app.py              # Streamlit frontend
├── chatbot.py          # LLM interaction logic
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation

# ✍️ Customization
You can modify chatbot.py to change system prompts, memory behavior, or model behavior as needed. Ollama supports other models as well — just swap "deepseek" with another supported model name.
