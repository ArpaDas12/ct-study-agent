# CT Study Agent 🎓

BUET CSE students দের জন্য AI-powered CT study assistant.

## Features
- 📁 CT slides upload (PDF + Images)
- 📖 Auto study note generation
- 💬 RAG-based chatbot (answers only from your CT content)
- 📝 Exam question generation (MCQ, Math, Theory)

## Tech Stack
- **Backend:** FastAPI + Python
- **AI:** Google Gemini + RAG Pipeline
- **Vector DB:** ChromaDB
- **Frontend:** React

## Architecture
Multi-agent system:
- **Orchestrator** → routes tasks to correct agent
- **Retriever Agent** → fetches relevant chunks from Vector DB
- **Study Note Agent** → generates detailed HTML study notes
- **Chatbot Agent** → RAG-based Q&A
- **Exam Agent** → generates exam questions with answers

## Status
🚧 Work in Progress — exam শেষে complete করা হবে
