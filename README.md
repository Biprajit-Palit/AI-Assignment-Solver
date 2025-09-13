# AI Assignment Solver with Streamlit

This repository contains my **first Large Language Model (LLM) project** — an AI-powered assignment solver built using **Streamlit**. The app accepts multiple file formats (PDF, Word, PowerPoint, Excel, Python code) and generates structured assignment solutions using **Google’s Gemini 1.5 Flash** LLM.  

👉 [Live Demo](https://ai-assignment-solver.streamlit.app/)  

---

## ✨ Features

- **Multi-Format File Upload**: Supports PDF, DOCX, PPTX, XLSX, and Python code files.  
- **AI-Powered Solutions**: Uses Gemini 1.5 Flash to generate step-by-step solutions.  
- **Context-Aware Processing**: Accepts multiple related files (e.g., data/code) and integrates them into solution generation.  
- **Streamlit Interface**: Clean, interactive UI for uploading files and viewing results.  

---

## ⚙️ How It Works

1. **Upload Assignment** → Add your file(s) in supported formats.  
2. **Solution Generation** → Content is parsed and sent to Gemini API for processing.  
3. **Receive Results** → AI returns a structured solution inside the app.  

---

## 📂 Supported File Types

- PDF (.pdf)  
- Word Document (.docx)  
- PowerPoint (.pptx)  
- Excel Spreadsheet (.xlsx)  
- Python Code (.py)  

---

## 🚀 Installation

### Prerequisites
- Python 3.8+  
- Google Gemini API access (API key required)  

### Setup
```bash
# 1. Clone repository
git clone https://github.com/<your-username>/ai-assignment-solver.git
cd ai-assignment-solver

# 2. Create virtual environment
python -m venv venv
# Activate it
source venv/bin/activate     # Linux/Mac
venv\Scripts\activate        # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Set your Gemini API key
export GOOGLE_API_KEY="your-google-api-key"   # Linux/Mac
set GOOGLE_API_KEY="your-google-api-key"      # Windows

# 5. Run the app
streamlit run main.py
```
---
## 🎯 How to Use

1. Upload your assignment file(s).  
2. Optionally, add related files (data, code, etc.).  
3. Click **Generate Solution**.  
4. View the structured solution in the app.  
---
## 📌 Project Purpose

I (**Biprajit Palit**, CSE student at **NIT Agartala**) built this project as part of my portfolio to explore **LLM integration with file handling and natural language understanding**.

This project showcases:  
- Handling file uploads in **Streamlit**  
- Parsing multiple file formats in **Python**  
- Interfacing with **Google’s Gemini LLM API**  
- Building user-facing AI applications  

---

## ⚠️ Disclaimer

This app is created **for learning and demonstration purposes only**. It is not intended for academic submission. Users are responsible for ensuring compliance with academic integrity policies.  

---

## 🔮 Future Improvements

- Support for more file types  
- Smarter parsing of complex documents  
- Integration with additional LLM APIs  
- UI/UX refinements  

---

## 🛠️ Skills Demonstrated

- **Programming**: Python  
- **Frameworks**: Streamlit  
- **AI/ML**: Large Language Models (Gemini 1.5 Flash)  
- **APIs**: Google Gemini API integration  
- **Other**: File handling (PDF, DOCX, PPTX, XLSX, PY), Environment setup, Deployment  

