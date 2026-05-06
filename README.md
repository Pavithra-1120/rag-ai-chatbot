# RAG AI Chatbot — PDF Question Answering

An AI-powered chatbot that answers questions from uploaded PDF documents using 
Retrieval-Augmented Generation (RAG).

## Demo
<img width="1920" height="1028" alt="Screenshot (320)" src="https://github.com/user-attachments/assets/8981ec3b-4912-4054-a1ed-8b7d8a62043e" />
<img width="1920" height="1017" alt="Screenshot (321)" src="https://github.com/user-attachments/assets/c6a3d0ab-5d4a-4729-bfdd-c5cf5c97f01d" />
<img width="1920" height="1021" alt="Screenshot (322)" src="https://github.com/user-attachments/assets/3f28e1d3-7d47-49be-811a-9b5a74982400" />

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
