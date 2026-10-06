# RAG AI Chatbot — PDF Question Answering

An AI-powered chatbot that answers questions from uploaded PDF documents using 
Retrieval-Augmented Generation (RAG).

## 🚀 Live Demo

- **App:** https://rag-ai-chatbot-theta.vercel.app
- **API Docs:** https://pavithra-1120-rag-chatbot-api.hf.space/docs

## Demo

<img width="1920" height="1020" alt="login" src="https://github.com/user-attachments/assets/b382cb7f-0c50-41bb-a06d-8ef89ed2d28a" />

<img width="1920" height="1024" alt="loginsuccess" src="https://github.com/user-attachments/assets/dad9d74c-22d9-46dc-b216-a9b54a0f54b2" />

<img width="1920" height="1020" alt="chatpage" src="https://github.com/user-attachments/assets/9baf9479-d522-4b39-ae04-8841d092f3ec" />

<img width="1920" height="1024" alt="chat" src="https://github.com/user-attachments/assets/1b5b96ed-7897-4a63-9a20-5d7d6d6f9abd" />


## Features
- Upload PDF documents and ask questions in natural language
- Semantic search using FAISS vector database
- Fast LLM responses powered by Groq API and streaming like ChatGPT
- JWT-based login and signup for secure access
- Clean React.js chat interface

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | React.js, CSS |
| Backend | FastAPI, Python |
| LLM | Groq API, LangChain |
| Vector DB | FAISS |
| Deployment | Docker, Hugging Face Spaces, Vercel |
| Database | PostgreSQL (Supabase) |
| Auth | JWT |

## Getting Started

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

## Environment Variables
Create a `.env` file in `/backend`:
```
GROQ_API_KEY=your_groq_api_key
DATABASE_URL=your_database_url
```
## Author
Pavithra K — [LinkedIn](https://www.linkedin.com/in/pavithra-k-19617b348/)| pavikk2011@gmail.com
