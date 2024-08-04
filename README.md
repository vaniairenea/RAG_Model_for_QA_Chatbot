# RAG QA Chatbot 🤖📚

Welcome to the **RAG QA Chatbot** repository! This project features a sophisticated Retrieval-Augmented Generation (RAG) model tailored for an advanced question-answering (QA) bot. By utilizing Hugging Face Transformers and Pinecone DB, this chatbot offers accurate and contextually relevant responses to user queries.

![Python](https://img.shields.io/badge/python-3.8-blue)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Transformers-orange)
![Pinecone](https://img.shields.io/badge/Pinecone-DB-yellow)
![VS Code](https://img.shields.io/badge/IDE-VS%20Code-blueviolet)

## 📖 Introduction

The **RAG QA Chatbot** enhances the question-answering process by dynamically retrieving relevant information from provided documents and generating precise answers. This project leverages the Hugging Face Transformers library for model implementation and Pinecone DB for efficient vector storage and retrieval.

## 🚀 Features

- **Document Retrieval**: Efficiently extracts and processes information from various types of documents.
- **Advanced Question Answering**: Uses a robust question-answering pipeline to deliver accurate responses.
- **Scalable Vector Storage**: Utilizes Pinecone DB for scalable and fast document embedding storage and retrieval.
- **Customizable Configuration**: Easily configurable to adapt to different document types and query requirements.

## 📂 Getting Started

### Prerequisites

- Python 3.8 or higher
- Required Libraries: 
  - `transformers`
  - `pinecone-client`
  - `sentence-transformers`
  - `langchain`

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/vaniairenea/rag_qa_chatbot.git
   cd rag_qa_chatbot
2. **Install the Dependencies**:

   ```bash
   pip install -r requirements.txt
3. Configure Settings:

- Create a config.json file with your Pinecone API key and other necessary settings.
- Update the config.json with the details for the Hugging Face model you plan to use.
4. Run the Chatbot:

   ```bash
   python run_chatbot.py
### 🌟 Contributing
We welcome contributions to enhance the RAG QA Chatbot! To contribute:

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your changes.
3. Implement and thoroughly test your changes.
4. Submit a pull request with a description of your modifications.
5. Please ensure your code adheres to the project's coding standards and is well-documented.

### 📧 Contact
For any questions, feedback, or inquiries, please reach out to vaniairenea@gmail.com.

### 🔗 Connect with Me
Feel free to connect with me on LinkedIn for updates and professional networking.

### 📝 View This Notebook in Google Colab
You can view and interact with this notebook directly in Google Colab by clicking the link below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1_59Qkz5RD9kbebJy1AMs7AqMoNyg5eVi?usp=sharing)

