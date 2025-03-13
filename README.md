# AI-Powered-End-to-End-Medical-Chatbot

### Overview

This project is an AI-powered Medical Assistant Chatbot that provides real-time medical guidance using advanced NLP and retrieval-augmented generation (RAG) techniques. It leverages Google Gemini-1.5-Pro, a vector database built with Pinecone, and embeddings from Hugging Face to ensure accurate and context-aware responses.

### Features

- Symptom Analysis & Condition Prediction

- Retrieval-based Medical Information (from The Gale Encyclopedia of Medicine)

- Conversational AI with Google Gemini-1.5-Pro

- Secure and Scalable Deployment using Flask

- Optimized Data Retrieval using Pinecone Vector Store


### Tech Stack & Libraries Used

### 1. Backend & Frameworks
 - Flask: Web framework for serving the chatbot API.

### 2. AI & NLP
 - Google Gemini-1.5-Pro: Advanced language model for generating medical responses.

 - LangChain: Framework for building retrieval-augmented generation (RAG) applications.

 - Hugging Face Embeddings: Used to generate vector embeddings for efficient text retrieval.

 - Pinecone: Vector database for fast and scalable similarity search.

### 3. Data Processing

 - PyPDFLoader & DirectoryLoader: Used for loading medical documents.

 - RecursiveCharacterTextSplitter: Splits text into smaller chunks for efficient vector search.

 - pypdf: PDF processing library for extracting medical knowledge from documents.

### 4. Environment & Configuration

 - dotenv: Manages environment variables securely.

 - os: Handles file and environment operations.
 

# How to run?
### Steps:

Clone the repository

```bash
Project repo:https://github.com/Niteshsinghbisht03/AI-Powered-End-to-End-Medical-Chatbot.git
```

### STEP 01 - Create a conda enivronment after opening the repository

```bash
conda create -n medibot python=3.13.2 -y
```

```bash
conda activate medibot
```


### STEP 02 - install the requirements
```bash
pip install -r requirements.txt
```


### STEP 03 - Set up environment variables
```bash
cp .env.example .env
```


### STEP 04 - Run the application:
```bash
python app.py
```

### Future Enhancements

- Expansion to image and voice-based interaction.

- Enhanced disease prediction models.