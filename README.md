# n8n-rag-support-agent
Customer Support RAG Agent built with n8n, OpenAI, Pinecone, Google Drive, and Chat Trigger

# n8n RAG Support Agent

This project shows how to build a Retrieval-Augmented Generation (RAG) assistant for customer support using **n8n**, **OpenAI GPT-5**, **Pinecone**, **Google Drive**, and **ChatTrigger**.

## Workflows
- **IPineCone RAG Agent (`PineCone RAG Agent`)**  
  Watches a Google Drive folder, chunks documents, creates OpenAI embeddings, and upserts them into Pinecone .

- **RAG-Query-Agent(`RAG-Query-Agent`)**  
  Listens to user questions (via Chat Trigger), queries Pinecone for relevant docs, and uses GPT-5 to generate grounded answers.
