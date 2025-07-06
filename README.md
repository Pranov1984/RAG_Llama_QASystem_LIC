📘 LIC Policy QA – RAG System Using LlamaIndex
This project implements a Retrieval-Augmented Generation (RAG) pipeline using LlamaIndex to extract structured information from the LIC New Jeevan Shanti insurance policy document.

It supports multiple embedding models and LLMs, and evaluates the quality of generated answers using faithfulness and relevance metrics.

✅ Project Features
✅ RAG pipeline powered entirely by LlamaIndex

🔍 Support for multiple embedding models:

OpenAI text-embedding-3-small

HuggingFace all-MiniLM-L6-v2, and more

🤖 Support for multiple LLMs:

GPT-4 / GPT-4o (OpenAI)

Mistral (via HuggingFace APIs)

🧪 Evaluation Metrics:

Faithfulness

Relevance

🧠 Automatically extracts predefined fields from uploaded LIC documents

📄 Extracted Data Fields
The system extracts the following fields from the LIC policy document:

Policy Name

Type of Plan

Minimum Vesting Age

Surrender Value Formula

Death Benefit for Single Life

Loan Eligibility

Annuity Modes Available

Free-Look Period

Eligibility for Joint Life

Additional Benefit Formula

🛠️ Tech Stack
Component	Technology
Framework	LlamaIndex
Vector DB	ChromaDB
Embeddings	OpenAI, HuggingFace
LLMs	GPT-4, GPT-4o, Mistral
Evaluation	Custom scoring (Faithfulness, Relevance)
Environment	Google Colab-ready
