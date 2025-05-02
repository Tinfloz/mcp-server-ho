# 🏥 Patient Query Assistant with RAG + OpenAI API

A Python-based MCP Server that answers patient-specific medical queries using a Retrieval-Augmented Generation (RAG) system integrated with the OpenAI Chat Completions API.  
The function retrieves context-specific medical data about a patient from an Azure AI Search (a Vector Database), and uses an LLM to generate precise, context-aware responses.

---

## 📖 Overview

This utility allows you to query a patient's medical information by providing:
- **`patient_name`**: The name of the patient (as a string).
- **`query`**: The natural language question you want to ask (as a string).

The system normalizes the patient’s name by removing spaces and converting it to lowercase, retrieves relevant data using an indexer, and sends this context along with your query to an OpenAI model to generate a smart, human-readable response.

---

## 🛠️ Features

✅ Patient name normalization (removes spaces and lowercases for consistent lookups)  
✅ Retrieval-Augmented Generation (RAG) powered by Azure AI Search and Storage Accounts 
✅ Natural language interaction via OpenAI Chat Completions API  
✅ Designed for secure and context-aware medical information handling  

---