# Techathon_Joel_Angels
# 🤖 AI-Powered Contract Template Generator

A smart Streamlit-based web app that generates contract templates tailored to specific clients using AI. The app also supports multi-language translation, clause-level customization, feedback collection, and a legal advisor chatbot to assist users during contract preparation.

---

## 🚀 Features

### 📄 1. Client-Specific Contract Generation
- Upload 20–30 sample contracts from a new client.
- Learns clause structure, tone, and preferences.
- Enter a contract type (e.g., "Master Service Agreement").
- Generates a formatted `.docx` contract template.

### 🌐 2. Contract Translation
- Generate contracts in your desired language: English, Spanish, French (more languages can be added).
- Powered by OpenAI's multilingual capabilities.

### 🔁 3. Clause Regeneration
- Allows regeneration of specific clauses for better clarity, tone, or legal strength.

### 🧠 4. Legal Advisor Chatbot
- Integrated chatbot helps with:
  - Clause explanations
  - Legal best practices
  - Structuring and negotiation tips

### 🗳️ 5. User Feedback
- Collects user ratings and comments on generated contracts.
- Enables future enhancement and learning.

---

## 📦 Requirements

- Python 3.8 or higher
- OpenAI API Key

---

## 🛠️ Setup Instructions

### 1. Download the Project

Download the ZIP or clone from GitHub:
```bash
git clone https://github.com/your-username/contract-template-generator.git
cd contract-template-generator
```

### 2. Create and Activate Virtual Environment

#### Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

> If you face PowerShell script errors, run PowerShell as Administrator:
```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```

#### macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### requirements.txt contains:
```
streamlit
streamlit-option-menu
python-dotenv
langchain
langchain-community
langchain_community
langsmith
openai
faiss-cpu
huggingface-hub
sentence-transformers
python-docx
docx2txt
textstat
language_tool_python
unstructured[all-docs]
```

---

### 4. Set Your OpenAI API Key

#### Windows:
```bash
set OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxx
```

#### macOS/Linux:
```bash
export OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxx
```

---

### 5. Run the App

```bash
streamlit run app.py
```

Then visit `http://localhost:8501` in your browser.

---


## 📬 Feedback & Contributions

Open an issue or submit a pull request if you find bugs or want to contribute features like:
- Clause-level editor
- Template saving to database
- PDF support

---

## 📜 License

MIT License – Free to use, modify, and distribute.
