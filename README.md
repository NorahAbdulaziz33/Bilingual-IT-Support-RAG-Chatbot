# Bilingual IT Support RAG Chatbot 🤖🇸🇦

An advanced AI-powered Bilingual IT Support Assistant built using n8n, Google Gemini (LLM & Embeddings), and Supabase Vector Store. This project was developed as part of the specialized training program with SDAIA (Saudi Data and Artificial Intelligence Authority).

## 🚀 Project Overview
This project implements a Retrieval-Augmented Generation (RAG) architecture. It allows users to query internal IT support documents and employee guides seamlessly in both Arabic and English. By connecting a vector database to an intelligent AI Agent, the system accurately extracts context from uploaded files and provides reliable answers, avoiding generic or fallback responses.

## 🛠️ Tech Stack & Tools
* Workflow Automation & AI Orchestration: n8n (AI Agent nodes, Tools, Memory)
* Large Language Model & Embeddings: Google Gemini Chat Model & Google Gemini Embeddings
* Vector Database: Supabase (PostgreSQL with pgvector)
* Data Processing: Default Data Loader & Text Splitter

## 📂 Architecture & Workflow
1. Data Ingestion Pipeline: Documents are loaded, split into manageable chunks using a text splitter, embedded via Google Gemini, and stored as vectors in Supabase.
2. Retrieval & Chat Agent: The AI Agent processes user queries from the chat interface, utilizes memory for context retention, and queries the Supabase Vector Store dynamically as a tool to fetch accurate knowledge base records.

## 🎯 Key Features
* Bilingual support (Arabic & English) for comprehensive IT help desk queries.
* Grounded responses using RAG to eliminate hallucinations and fallback messages.
* Session memory management for continuous, conversational user experiences.

---
Developed during the SDAIA training program.
https://github.com/SDAIAAcademy
