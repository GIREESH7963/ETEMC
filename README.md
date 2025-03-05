Medical AI Assistant - RAG-based Diagnostic Tips

📌 Project Overview

This project is a Retrieval-Augmented Generation (RAG) based AI assistant designed to provide medical diagnostic tips. It utilizes The Gale Encyclopedia of Medicine as a knowledge source, leveraging Pinecone for vector search and LangChain for retrieval. The frontend is built using Flask, offering an interactive interface for users to query medical information efficiently.

🚀 Features

Medical Knowledge Retrieval: Extracts relevant diagnostic tips from a trusted medical encyclopedia.

Vector Search with Pinecone: Enables fast and accurate retrieval of medical information.

LangChain for Contextual Responses: Enhances AI responses by leveraging structured medical data.

Flask-based Web Interface: Provides a user-friendly and interactive platform.

PDF-based Knowledge Source: Uses preprocessed medical PDFs for AI-driven insights.

🏗️ Tech Stack

Framework: Flask (Frontend & API)

Embedding Database: Pinecone

Retrieval Framework: LangChain

Knowledge Source: The Gale Encyclopedia of Medicine (PDF)

Backend: Python

📖 How It Works

Preprocessing: The Gale Encyclopedia of Medicine is converted into vector embeddings.

User Query: The user inputs a medical question via the Flask-based interface.

Retrieval: LangChain fetches the most relevant sections from the vector database (Pinecone).

Response Generation: The AI formulates a response using the retrieved context.

User Interaction: The response is displayed on the web interface.

🎯 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-username/medical-ai-rag.git
cd medical-ai-rag

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Set Up Pinecone

Sign up for Pinecone and get your API key.

Add the key to your .env file:

PINECONE_API_KEY=your_api_key_here

4️⃣ Run the Flask App

python app.py

Open http://localhost:5000 in your browser.

📊 Future Enhancements

✅ Improve response summarization using LLM fine-tuning.

✅ Expand knowledge base with more medical sources.

✅ Deploy as a cloud-based API for broader accessibility.
