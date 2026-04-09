- Generate summary of legal documents
- Answer questions based on uploaded document
- Work using Groq LLM (Llama 3 models)

Built using Python, Streamlit, and Groq API.

---

# Features 🚀

• Upload PDF document  
• Upload Image (PNG, JPG, JPEG)  
• Upload Text file (TXT)  
• Extract text automatically  
• Generate AI summary  
• Ask questions from document  
• Fast response using Groq API  

---

# Project Structure 📁


LEGAL AI
│
├── app.py
├── requirements.txt
├── .env
│
├── llm
│ ├── summarizer.py
│ └── qa_engine.py
│
└── utils
├── file_loader.py
└── text_cleaner.py


---

# Installation ⚙️

## Step 1 - Clone repository


git clone https://github.com/your-username/legal-ai.git

cd legal-ai


---

## Step 2 - Create virtual environment


python -m venv venv


Activate environment:

Windows:


venv\Scripts\activate


---

## Step 3 - Install dependencies


pip install -r requirements.txt


---

## Step 4 - Add Groq API key

Create file:


.env


Add your API key:


GROQ_API_KEY=your_api_key_here


Get API key:

https://console.groq.com/

---

## Step 5 - Install Tesseract OCR

Download:

https://github.com/tesseract-ocr/tesseract/wiki

Install and verify path:


C:\Program Files\Tesseract-OCR\tesseract.exe


---

## Step 6 - Run application


streamlit run app.py


Open browser:


http://localhost:8501


---

# Usage 🧠

1. Upload document (PDF, Image, TXT)
2. View extracted text
3. Click Generate Summary
4. Ask questions related to document

---

# Technologies Used 💻

- Python
- Streamlit
- Groq API
- Llama 3 LLM
- PyPDF
- Tesseract OCR
- Pillow

---

# Example Use Cases 📊

Legal contract analysis  
Case document summarization  
Research document understanding  
Question answering from legal files  

---

# Future Improvements 🔮

• Chat interface  
• Highlight important clauses  
• Export summary as PDF  
• Risk clause detection  
• Multi-language support  

---

# Author 👨‍💻

Omkar Thombare

---

# License 📜

This project is for educational purposes.
Also update requirements.txt
groq
streamlit
python-dotenv
pypdf
pillow
pytesseract
