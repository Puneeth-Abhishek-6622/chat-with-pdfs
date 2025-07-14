# 📚 Chat with Multiple PDFs using Gemini

[![Streamlit](https://img.shields.io/badge/Streamlit-Enabled-brightgreen)](https://streamlit.io/) [![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)

A user-friendly Streamlit app that lets you upload multiple PDF documents and chat with them using Google Gemini (via LangChain, FAISS, and Google Generative AI). The app extracts text from your PDFs, creates vector embeddings, and answers your questions based on the content of your documents.

---

## 🚀 Features
- Upload and process multiple PDF files
- Ask questions and get answers based only on your uploaded documents
- Uses Retrieval-Augmented Generation (RAG) with Google Gemini
- Fast vector search with FAISS
- Clean, modern Streamlit interface

---

## 🛠️ Requirements
- Python 3.8+
- Google Generative AI API key ([get one here](https://makersuite.google.com/app/apikey))

### Python Packages
- streamlit
- PyPDF2
- langchain
- langchain-community
- langchain-google-genai
- google-generativeai
- python-dotenv

Install all requirements with:
```bash
pip install -r requirements.txt
```

---

## ⚙️ Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up your API key:**
   - Create a `.env` file in the project root:
     ```env
     GOOGLE_API_KEY=your_google_generative_ai_api_key
     ```
4. **Run the app:**
   ```bash
   streamlit run app.py
   ```

---

## 💡 Usage Guide
1. **Upload PDFs:** Use the sidebar to upload one or more PDF files and click "Submit & Process".
2. **Ask Questions:** Enter your question in the main input box. The app will answer based only on the content of your uploaded PDFs.
3. **Iterate:** Upload new PDFs or ask more questions as needed!

---


![App Screenshot](https://i.postimg.cc/wMxK2Mhm/Screenshot-2025-07-14-212421.png)





- **Upload:** `sample.pdf`
- **Ask:** "What is the main topic of the document?"
- **Reply:** "The main topic is..."

---

## 🔒 Environment Variables
- `GOOGLE_API_KEY`: Your Google Generative AI API key (required)

---

## 🙏 Credits
- [Streamlit](https://streamlit.io/)
- [LangChain](https://python.langchain.com/)
- [Google Generative AI](https://ai.google.dev/)
- [FAISS](https://github.com/facebookresearch/faiss)

---

## 🚧 Future Improvements
- Support for more file types (Word, TXT, etc.)
- User authentication
- Persistent chat history
- Deploy to Streamlit Cloud or Hugging Face Spaces
- UI/UX enhancements

---

## 📬 Contributing
Pull requests and suggestions are welcome! Please open an issue first to discuss changes.

---

## 📄 License
[MIT](LICENSE) 
