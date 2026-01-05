# Streamlit-based-AI-application
An AI-powered Streamlit app for financial news research that retrieves, summarizes, and answers questions from multiple articles using LangChain, FAISS, and OpenAI embeddings.
News Research Tool is a Streamlit-based AI application that allows users to perform intelligent research on financial news articles. It leverages LangChain to load articles from URLs, splits them into overlapping text chunks using a recursive character splitter, and creates vector embeddings with OpenAI or SentenceTransformers. FAISS is used as the vector database for fast similarity search, enabling the retrieval of relevant content. Users can ask natural language questions about the articles, and the app provides summarized answers along with source attribution using a Map-Reduce QA chain. This tool is ideal for quickly extracting insights from multiple financial news sources, making equity research more efficient and interactive

It Covers:

✅LangChain + OpenAI embeddings

✅ FAISS vector DB

✅ CSV + Unstructured URL Loader

✅ RecursiveCharacterTextSplitter (overlapping chunks)

✅ Map-Reduce QA with sources

✅ Streamlit UI (run via Colab + ngrok/localhost)

✅ Shows answer + sources + summarized answer

✅ Pickle-based in-memory vector storage
