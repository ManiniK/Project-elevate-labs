# Project-elevate-labs
# Mental Health Chatbot  
An **AI-driven chatbot** designed to provide supportive and empathetic conversations around mental health.  
This project integrates **LangChain**, **Groq LLaMA-3.3-70B**, **ChromaDB**, and **Gradio** to deliver context-aware and interactive responses based on PDF knowledge sources.  
##  Features  
- Conversational AI powered by **Groq LLaMA-3.3-70B**  
- Context-aware answers with **ChromaDB vector database**  
- PDF document ingestion with **SentenceTransformers embeddings**  
- Prompt-engineered for **empathetic mental health support**  
- **Gradio web interface** for easy interaction  
## How It Works  
1. **Load LLM** – Initializes the Groq LLaMA-3.3-70B model.  
2. **Build Vector Database** – Processes PDF files and stores embeddings in ChromaDB.  
3. **Retrieve Context** – Matches user queries against stored document embeddings.  
4. **Generate Responses** – Produces empathetic, context-aware answers using LangChain.  
5. **Output** – Provides responses via **Command-Line Interface (CLI)** or **Gradio Web App**.  
