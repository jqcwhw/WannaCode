# 🤖 WANNACODE – AI-Powered Code Assistant

**WANNACODE** is a Streamlit-based AI-powered coding environment that enables users to generate, edit, and execute code interactively using Google's Gemini API. The system supports Python code execution, provides natural language-based code generation, and ensures prompt safety and system integrity using role-based behavior constraints.

---

## 🚀 Features

- 🔐 **Role-Based AI Assistant** powered by Gemini 2.0 Flash
- 🧠 **Natural Language to Code Generation** using Gemini
- 💻 **Code Compilation** from user input or uploaded files
- 🌍 **Language Detection** via `langdetect`
- 🧪 **Input Handling** for interactive programs
- 🖼️ **Image Integration** for enhanced UI experience
- 🛡️ **Prompt Injection Defense** against prompt-leaking attacks

---

## 📂 Project Structure

wannacode/
│
├── main.py # Streamlit App Entry Point
├── 1.png # Welcome Image for Home Page
├── 2.png # Compiler Page Banner
├── 3.png # Generator Page Banner
└── requirements.txt # Required Python Packages

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/wannacode.git
cd wannacode

2. **Create a virtual environment (optional but recommended)**
```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

3. Install required packages
```bash
pip install -r requirements.txt

4. 🔑 Set Up API Key
Replace the API key in main.py:
genai.configure(api_key="YOUR_GOOGLE_GENAI_API_KEY")

5. ▶️ Run the Application
streamlit run main.py
Open http://localhost:8501 in your browser.

👨‍💻 Author
Ghosh (ghosh)
📅 Created: May 17, 2025
📬 Email: sanchayan7432@gmail.com