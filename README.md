# WebRAGify: End-to-End Data Scraping & Retrieval-Augmented Generation (RAG)
## Overview
WebRAGify is an end-to-end pipeline for scraping web content, processing it for large language model (LLM) training, and implementing Retrieval-Augmented Generation (RAG) for precise, context-driven question answering. This project integrates modern AI tools and libraries like LangChain, Chroma, and Google Generative AI to transform scraped data into actionable insights.

## Key Features
## Automated Web Scraping: Uses FireCrawlLoader to scrape structured data from websites.
Data Processing & Chunking: Splits large documents into manageable chunks for efficient embedding and indexing.
Vector Storage: Stores document embeddings using Chroma for fast and scalable retrieval.
Retrieval-Augmented Generation (RAG): Leverages Google’s Generative AI to answer questions based on the scraped data, enhancing LLM responses with specific, relevant context.
Batch Processing & Persistence: Processes data in batches for efficiency, with the ability to save and reload indexed data.
