📚 PDF Chatbot with LangChain and Hugging Face

An AI-powered chatbot that allows you to **chat with your PDF documents**. Upload multiple PDFs and ask questions — it reads, understands, and responds with relevant answers using a language model and vector search.


🚀 Features

🔍 Extracts and chunks text from uploaded PDFs
 💡 Embeds and stores text using FAISS (vector database)
 🧠 Uses `google/flan-t5-base` for natural language answers
 💬 Remembers chat context with conversational memory
 🌐 Streamlit web interface for easy interaction


 🛠️ Tech Stack

- Python
- Streamlit – Web interface
- LangChain – Conversational AI logic
- FAISS – Vector storage and similarity search
- Hugging Face Transformers – Language model (FLAN-T5)
- PyPDF2 – PDF parsing
- dotenv – Environment variable handling

Set up Hugging Face API key:  

 HUGGINGFACEHUB_API_TOKEN=your_token_here
