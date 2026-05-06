# RAG AI Chatbot — PDF Question Answering

An AI-powered chatbot that answers questions from uploaded PDF documents using 
Retrieval-Augmented Generation (RAG).

## Demo
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/412d64db-cb59-4128-8659-5e5fa6c83f90" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/438368c0-643c-4373-885b-f9eef0872f88" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/330fa6bc-ee26-4b78-b13a-513462217852" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f81c7e33-29a8-43b5-b291-0533454637d6" />


## Features
- Upload PDF documents and ask questions in natural language
- Semantic search using FAISS vector database
- Fast LLM responses powered by Groq API and streaming like ChatGPT
- JWT-based login and signup for secure access
- Clean React.js chat interface

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | React.js, Tailwind CSS |
| Backend | FastAPI, Python |
| AI/LLM | Groq API, LangChain |
| Vector DB | FAISS |
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
