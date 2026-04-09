# 🤖 AI Knowledge Assistant (RAG Chatbot)

## 📌 1. Business Problem

Many organizations struggle to provide instant and accurate answers to user queries based on their internal documents. Traditional chatbots fail to understand context and cannot retrieve meaningful information from large datasets.

---

## 💡 2. Possible Solution

A smart AI chatbot that can understand user queries and fetch relevant information from stored documents using semantic search and AI models.

---

## 🚀 3. Implemented Solution

I built a Retrieval-Augmented Generation (RAG) based chatbot using n8n workflows, Qdrant vector database, and HuggingFace embeddings.

The system:

* Converts documents into vector embeddings
* Stores them in Qdrant
* Retrieves relevant data based on user query
* Uses an LLM to generate accurate answers

---

## 🛠️ 4. Tech Stack Used

* Frontend: React (Vite)
* Backend: n8n (Workflow Automation)
* Vector Database: Qdrant Cloud
* Embeddings: HuggingFace
* LLM: Groq / OpenAI
* API Communication: Webhooks

---

## 🏗️ 5. Architecture Diagram

User → Frontend → Webhook → Embeddings → Qdrant → LLM → Response → Frontend

(Add diagram image here if possible)

---

## ▶️ 6. How to Run Locally

1. Start n8n:

   * Run n8n (localhost:5678)
   * Activate workflow

2. Ensure Qdrant Cloud is active

3. Run frontend:

   ```
   npm install
   npm run dev
   ```

4. Open browser:
   http://localhost:5173

5. Ask questions in chatbot

---

## 📚 7. References & Resources

* Qdrant Documentation: https://qdrant.tech/documentation/
* n8n Docs: https://docs.n8n.io/
* HuggingFace: https://huggingface.co/
* RAG Concepts: https://www.pinecone.io/learn/retrieval-augmented-generation/

---

## 🎥 8. Demo Recording

(Add your video link here – Google Drive / YouTube)

---

## 📸 9. Screenshots


* Chatbot UI
* n8n Workflow
* Qdrant Dashboard

---

## ⚠️ 10. Problems Faced & Solutions

1. Qdrant 404 Error

   * Cause: Cluster was suspended
   * Solution: Reactivated Qdrant cluster

2. ngrok Dependency

   * Cause: Frontend was using ngrok URL
   * Solution: Switched to localhost

3. Response Format Issue

   * Cause: Incorrect JSON format
   * Solution: Fixed webhook response structure

4. CORS Issues

   * Cause: Localhost communication
   * Solution: Configured proper API calls

---

## 📌 11. Conclusion

This project demonstrates how RAG architecture can be used to build intelligent chatbots that provide accurate and context-aware responses using vector databases and LLMs.

---

## 🔗 Project Links

(Add your GitHub repo / deployment links here)
