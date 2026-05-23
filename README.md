# RAGnarok
RAGnarök implements a full RAG pipeline that retrieves relevant text chunks from a knowledge base and uses them as context for a language model to generate factual answers. Every component is built from scratch with detailed visualizations.

# Architecture
User Query → Embedding → FAISS Vector Search → Retrieved Chunks → FLAN-T5 Generator → Answer

# Components:
Embedding Model: all-MiniLM-L6-v2 (Sentence Transformers)
Vector Database: FAISS (Facebook AI Similarity Search)
Generator Model: Google FLAN-T5-Base
Dataset: Curated knowledge base covering AI, ML, NLP, science, and geography

# ✨ Features
🔍 Semantic Search - Finds relevant context using embedding similarity
🤖 Context-Aware Generation - Grounds answers in retrieved evidence
📊 Rich Visualizations - PCA, t-SNE, similarity heatmaps, distance charts
💬 Interactive Q&A - Real-time question answering interface
📈 Evaluation Metrics - Recall@K, distance scoring, multi-query comparison
🚀 Colab Ready - Runs entirely in Google Colab with zero setup
