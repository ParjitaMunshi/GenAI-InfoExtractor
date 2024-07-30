' GenAI-InfoExtractor

' GenAI-InfoExtractor is a comprehensive Generative AI-based Question Answering (QA) system designed 
' to extract knowledge from CSV files and provide answers through an intuitive Streamlit interface. 
' This project leverages advanced machine learning and natural language processing techniques to 
' build a robust and efficient knowledge base.

' Features

' - Knowledge Base Creation: Automatically creates a vector database from a CSV file containing FAQs or other information.
' - Advanced Embeddings: Uses HuggingFace Instruct Embeddings for high-quality vector representations.
' - Efficient Similarity Search: Implements FAISS (Facebook AI Similarity Search) for quick and accurate retrieval of relevant information.
' - Generative Answering: Utilizes GooglePalm as the underlying Large Language Model (LLM) to generate contextually accurate answers.
' - Interactive Interface: Streamlit-based user interface for easy interaction and querying of the knowledge base.

' Project Overview

' GenAI-InfoExtractor is designed to streamline the process of extracting and querying information from large datasets. 
' By converting CSV data into a searchable vector database, users can easily find answers to their questions without 
' manually sifting through the data. The project integrates several key technologies:

' - Langchain-Community Tools: For embedding, vector storage, document loading, and LLM integration.
' - Streamlit: For building an interactive web application.
' - GooglePalm API: For generating natural language answers.

' The primary components of the project are:

' 1. main.py: The main script that runs the Streamlit application.
' 2. helper.py: Contains helper functions for creating the vector database and the QA chain.
' 3. faqs.csv: A sample CSV file with FAQs used to build the knowledge base.


' GenAI-InfoExtractor/
' │
' ├── main.py                ' Main script to run the Streamlit app
' ├── helper.py              ' Helper functions for creating the vector DB and QA chain
' ├── faqs.csv               ' Sample CSV file containing the FAQs
' ├── requirements.txt       ' Required Python packages
' └── README.md              ' Project documentation

' Dependencies

' - Streamlit: For building the web application interface.
' - Langchain-Community: Tools for embedding, vector storage, and LLM integration.
' - GooglePalm API: For generating answers using a large language model.
' - HuggingFace Instruct Embeddings: For high-quality vector embeddings.
' - FAISS: For efficient similarity search.
' - Pandas: For data manipulation and loading.

