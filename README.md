# Semantic_chunking_comarison
# 📄 Semantic Document Chunking using OpenAI Embeddings and Huggingface embedding model.

An AI-powered document processing pipeline that performs **semantic chunking** on Microsoft Word documents (.docx). The project extracts textual content (including table data), generates semantic embeddings using OpenAI, and creates context-aware chunks suitable for RAG (Retrieval-Augmented Generation), vector databases, and enterprise document search.

## 🚀 Features

- Load and parse `.docx` documents using LangChain
- Extract both text and table content
- Semantic chunking based on document meaning instead of fixed chunk sizes
- Generate embeddings using OpenAI  "text-embedding-3-small" / "text-embedding-3-large"
- Preserve contextual relationships between paragraphs
- Ready for Vector Databases (Qdrant, FAISS, ChromaDB, Pinecone, Azure AI Search, etc.)
- Suitable for enterprise RAG applications

## 🔑 Configure OpenAI API

Create a `.env` file.
OPENAI_API_KEY=your_api_key


## Workflow

DOCX Files
      │
      ▼
Document Loader
      │
      ▼
Extract Text + Tables
      │
      ▼
OpenAI Embeddings
      │
      ▼
Semantic Chunking
      │
      ▼
Context-Aware Chunks
      │
      ▼
Vector Database / RAG Pipeline

## 📈 Use Cases
- Enterprise RAG Systems
- Legal Document Processing
- Knowledge Base Creation
- Contract Analysis
- Document Search
- AI Chatbots
- Semantic Retrieval
