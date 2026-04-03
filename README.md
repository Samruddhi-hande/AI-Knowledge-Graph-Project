# 🧠 AI Knowledge Graph System

## 📌 Overview

AI Knowledge Graph System is a full-stack web application that transforms unstructured data (notes, PDFs, or text) into a structured knowledge graph. It uses AI/NLP techniques to extract concepts and relationships, enabling users to explore their knowledge in a connected and visual way.

---

## 🚀 Features

### 👤 User Features

* User authentication (JWT-based login/signup)
* Upload notes or enter text
* View extracted concepts and relationships
* Search concepts and explore connections

### 🧠 AI Features

* Automatic concept extraction from text
* Relationship detection between entities
* Structured graph generation from unstructured input

### 📊 Visualization

* Interactive graph representation of knowledge
* Node (concept) and edge (relationship) exploration
* Dynamic and responsive UI

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* D3.js / react-force-graph
* Axios

### Backend

* Node.js
* Express.js
* JWT Authentication

### Database

* PostgreSQL (Supabase)

### AI / NLP

* OpenAI API
* spaCy
* LangChain (optional)

---

## 🧠 How It Works

1. User uploads text or notes
2. Backend processes input using AI/NLP
3. Extracted concepts (nodes) and relationships (edges) are generated
4. Data is stored in PostgreSQL
5. Frontend visualizes the knowledge graph
6. User can search and explore connections

---

## 📂 Folder Structure

/client → React frontend
/server → Node.js backend
/routes → API routes
/controllers → Business logic
/models → Database schema
/services → AI/NLP processing

---

## 🔐 Authentication

* JWT-based authentication
* Secure API endpoints
* Protected routes for user data

---

## 🗄️ Database Schema (Simplified)

* users (id, name, email, password)
* documents (id, user_id, content)
* nodes (id, name)
* edges (id, from_node, to_node, relation)

---

## 🌍 Deployment

* Frontend: Vercel
* Backend: Render
* Database: Supabase

---

## 🔮 Future Improvements

* PDF and image-based text extraction
* Voice-to-knowledge graph conversion
* Chat with knowledge (RAG system)
* Advanced semantic search with embeddings
* Chrome extension for saving web content

---

## 🤝 Contribution

Contributions are welcome! Fork the repository and submit a pull request.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---
