RAG
Brief Summary of my Project, I have built a Retrieval-Augmented Generation (RAG) system that integrates web scraping and advanced AI models for efficient information retrieval and response generation. My project includes:

Web Scraping & Crawling:

Trafilatura Spider + Selenium + Beautiful Soup for handling JS-heavy websites, ensuring deep, recursive crawling.
Crawl4AI for efficient crawling of normal websites.
Data Processing & Storage:

ChromaDB as the vector database for embedding storage and retrieval.
Google Generative AI for generating responses in the main app script.
text-embedding-004 model to embed document chunks optimally.
Dynamic Chunking Strategy to optimize retrieval efficiency.
End-to-End Workflow:

Load API keys and documents from .env.
Chunk and embed documents.
Use a generate_response function to retrieve relevant chunks and answer user queries.
Why These Tools?
Trafilatura Spider + Selenium + Beautiful Soup: Handles JavaScript-heavy sites dynamically, ensuring deep crawling.
Crawl4AI: Lightweight, efficient for normal crawling tasks.
ChromaDB: Fast, scalable, and optimized for vector search.
Google Generative AI: Provides high-quality responses using Gemini models.
text-embedding-004: High-performance embedding model ensuring semantic search accuracy. 
