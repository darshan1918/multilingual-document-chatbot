Create a .env file with:
GEMINI_API_KEY=your_key
PINECONE_API_KEY=your_key

# 🗂️ AI-Powered Multilingual Document Q&A Bot

This app lets you:
✅ Upload PDFs, DOCX, TXT, MD, HTML  
✅ Ask questions via text or voice in your language  
✅ Get Gemini-generated answers, grounded in the document  
✅ Hear answers spoken aloud  
✅ Supports Pinecone vector DB + LangChain + Streamlit

## 🚀 Tech Stack
- Google Gemini API (LLM + embeddings)
- Pinecone (vector DB)
- LangChain
- Streamlit
- gTTS, SpeechRecognition, Deep Translator

## 💻 How to Run
```bash
pip install -r requirements.txt
streamlit run stremlit_app.py




# !pip install langchain-cli
# !pip install langchain
# !pip install langchain-community
# !pip install langchain-google-genai
# !pip install google-generativeai
# !pip install langchain-pinecone
# !pip install pypdf
# !pip install python-dotenv


# For speech
pip install speechrecognition pydub gtts 
pip install pyaudio

# Transalator
pip install deep-translator

