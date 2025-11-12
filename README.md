# GenAI-Document-Assistant

## Built with Python, Gemini LLM, LlamaIndex, HuggingFace, and PyMuPDF

## 📘 Overview

This project is a Generative AI-powered Document Assistant designed to process, understand, and answer user queries from complex PDF documents.
By leveraging Retrieval Augmented Generation (RAG), the system combines semantic search, keyword-based retrieval, and LLM-driven reasoning to deliver contextually accurate answers.

## 🚀 Features

Document Parsing: Extracts and structures text from PDF files using PyMuPDF.

Semantic Chunking: Splits documents into meaningful segments for efficient embedding and retrieval.

Embeddings & Indexing: Uses HuggingFace sentence-transformers and ChromaDB for vector storage.

Hybrid Retrieval: Combines vector-based (semantic) and BM25 (keyword) search for improved accuracy.

Query Expansion & Reranking: Utilizes Gemini LLM for rewriting and ranking responses to ensure relevance.

End-to-End RAG Pipeline: Integrates all components for seamless question answering over document data.

## 🧩 Tech Stack

Languages & Frameworks: Python, LlamaIndex
LLM: Google Gemini
Embeddings: HuggingFace Sentence Transformers
Document Processing: PyMuPDF
Retrieval: BM25, HybridRetriever
Database: ChromaDB

## 💡 Example Use Case

Upload a financial or legal document → Ask “What are the borrower’s payment obligations?” →
The assistant retrieves the relevant section, expands the query semantically, and generates a natural-language response.

## 📈 Future Improvements

Add multi-document querying support

Integrate user interface for interactive chat experience

Support additional file formats (DOCX, TXT, etc.)
