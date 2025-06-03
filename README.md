# 🩺 AI Powered Healthcare Assistant

This project is an AI-powered healthcare assistant that leverages **natural language processing** and **retrieval-based question answering** to respond to users' health-related queries with factual information from reliable sources. Built using **LangChain**, **ChromaDB**, and **OpenAI's language models**, this assistant can interpret medical questions and provide informative, relevant answers.

## 📌 Project Objective

To build a conversational AI assistant capable of:
- Understanding user queries related to symptoms, illnesses, treatments, etc.
- Fetching accurate answers from a curated set of medical documents.
- Providing context-aware and medically reliable responses in real-time.

## 📚 Dataset

- **Source**: [NHS Inform](https://www.nhsinform.scot/illnesses-and-conditions)
- **Documents**: 11 medical documents manually collected and used to build a knowledge base.
- **Storage**: Embedded and indexed using **ChromaDB**, a vector store for semantic search.

## 🧠 Tech Stack

- **LangChain** – For building LLM-powered chains.
- **OpenAI GPT** – For language understanding and generation.
- **ChromaDB** – For storing document embeddings and retrieving relevant chunks.
- **Python** – Core development language.
- **Jupyter Notebook** – Interactive development and testing.

## ⚙️ Workflow

1. **Data Ingestion**:
   - 11 documents from NHS Inform were scraped and prepared.
   - Split into smaller chunks using LangChain's text splitter.
   
2. **Embedding**:
   - Text chunks were embedded using OpenAI Embeddings.
   - Stored in ChromaDB for fast semantic retrieval.
   
3. **Query Handling**:
   - User enters a query in natural language.
   - Relevant documents are retrieved from ChromaDB.
   - GPT model generates a response based on the retrieved context.

4. **Response Display**:
   - The assistant returns an answer grounded in the documents.
  
## 🙋‍♀️ Author

**Nishitha Tirumalaraju**
📍 [GitHub](https://github.com/nishithat-28) | [Kaggle](https://www.kaggle.com/nishithatirumalaraju)
