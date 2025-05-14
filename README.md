# NeuroSearch AI

🧠 Smart AI-powered search across internal company data

## 🔧 Technologies
- Backend: FastAPI, Python 3.11
- Frontend: Next.js, Tailwind CSS
- Vector DB: Qdrant / Pinecone
- Embeddings: OpenAI, BGE
- Authentication: Google OAuth 2.0

## 🚀 Quick Start

```bash
# backend
cd backend
python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload

# frontend
cd frontend
npm install
npm run dev
