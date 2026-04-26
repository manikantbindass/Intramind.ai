<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=Intramind.ai&fontSize=90&animation=fadeIn&fontAlignY=38" />
</div>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=manikantbindass&show_icons=true&theme=tokyonight" alt="manikantbindass's GitHub stats" />
</p>

# Intramind.ai

**Intramind.ai** is an enterprise-grade AI-powered knowledge platform that helps organizations unlock information from internal documents through intelligent conversations.

Built with a high-performance **RAG (Retrieval-Augmented Generation) Pipeline**, it allows teams to query company knowledge naturally and receive context-aware answers with citations.

---

## 🏗 Project Structure

### 🎨 Frontend (Next.js)
```text
frontend/
├── app/                  # Next.js App Router
│   ├── (auth)/           # Auth routes (login, signup)
│   └── dashboard/        # Main app dashboard (workspace, chat, docs)
├── components/           # Reusable UI components
├── hooks/                # Custom React hooks
├── services/             # API service layer
├── store/                # State management (Zustand)
└── utils/                # Utility functions
```

### ⚙️ Backend (FastAPI)
```text
backend/
├── api/                  # API routes & endpoints
├── core/                 # App configuration & security
├── models/               # Database models (SQLAlchemy/Tortoise)
├── services/             # Business logic layer
├── ai/                   # RAG pipeline & AI logic
├── embeddings/           # Text embedding logic
├── vectorstore/          # FAISS / Pinecone integration
└── db/                   # Database session & migrations
```

### ☁️ Infrastructure & CI/CD
```text
infra/                    # Docker & K8s configurations
.github/workflows/        # CI/CD pipelines (Lint, Test, Build, Deploy)
```

---

## 🧠 RAG Pipeline (Core Engine)
1. **Document Upload**: Multi-format support (PDF, MD, TXT).
2. **Text Extraction**: High-accuracy parsing.
3. **Chunking**: Intelligent text splitting.
4. **Embedding**: Converting text to high-dimensional vectors.
5. **Vector Store**: Storage in FAISS/Pinecone.
6. **Query**: Natural language retrieval.
7. **Similarity Search**: Finding the most relevant context.
8. **LLM Response**: AI-generated answers with source citations.

---

## 🔐 Security & Compliance
- **Auth**: JWT + refresh tokens.
- **Access Control**: RBAC enforcement.
- **Protection**: Rate limiting (Redis) & Input sanitization.
- **Network**: HTTPS everywhere & Secure headers.

---

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=manikantbindass&theme=tokyonight" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=footer" />
</div>
