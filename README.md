# ⚖️ Legal AI Assistant

Legal AI Assistant is an AI-powered application that can **read legal documents**, **summarize content**, and **answer questions** based on uploaded files.
It supports **PDF, Image, and Text files** using OCR and LLM technology.

---

## 🚀 Features

* 📄 Upload legal documents (PDF, PNG, JPG, TXT)
* 🔍 Extract text using OCR (pytesseract)
* 🤖 AI-powered summarization
* ❓ Ask questions from document
* ⚡ Fast responses using LLM (Groq / Llama model)
* 🌐 Simple UI using Streamlit

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Groq API / LLM
* PyPDF
* Pytesseract OCR
* Pillow (Image processing)
* dotenv (Environment variables)

---

## 📂 Project Structure

```
Legal-AI-Assistant/
│
├── app.py
├── requirements.txt
├── .env
│
├── utils/
│   ├── file_loader.py
│   ├── file_cleaner.py
│
├── llm/
│   ├── summarizer.py
│   ├── qa_engine.py
│
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/legal-ai-assistant.git
cd legal-ai-assistant
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate environment:

Windows:

```bash
venv\Scripts\activate
```

Mac/Linux:

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Install Tesseract OCR

Download:
https://github.com/tesseract-ocr/tesseract

After install, add path in system environment variable.

Example path:

```
C:\Program Files\Tesseract-OCR\tesseract.exe
```

---

### 5️⃣ Setup Environment Variables

Create `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Run Application

```bash
streamlit run app.py
```

---

## 🧠 How it Works

1. Upload legal document
2. System extracts text using OCR or PDF reader
3. AI summarizes content
4. User can ask questions from document
5. AI gives context-based answers

---

## 📸 Example Use Cases

* Legal document summary
* Contract analysis
* Case file understanding
* Quick legal insights
* Research assistance

---

## 🔮 Future Improvements

* Multiple document upload
* Highlight key clauses
* Chat history
* Export summary as PDF
* Support more LLM models

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Omkar Thombare

---

⭐ If you like this project, give it a star on GitHub!
