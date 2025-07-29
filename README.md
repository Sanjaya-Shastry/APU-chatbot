Chat with Azim Premji University (A RAG based Chatbot)

This project is a Retrieval Augmented Generation (RAG) chatbot built using content scraped from the official Azim Premji University website. It allows users to ask natural language questions and receive accurate, context aware answers based on the site’s content.

Features
	•	Crawls and extracts text from dynamically rendered pages using Selenium
	•	Recursively scrapes internal links up to 8 levels deep
	•	Splits and embeds text using LangChain and OpenAI embeddings
	•	Stores vectors in FAISS for fast semantic retrieval
	•	Uses LangChain’s ConversationalRetrievalChain for context-aware dialogue
	•	Interactive UI built with Gradio

Use Cases
	•	Ask about faculty, research, academic programs, or social initiatives
	•	Explore admissions, campus life, or university events

This project demonstrates how LLMs can be integrated with custom data sources for building intelligent, domain-specific chat interfaces.
