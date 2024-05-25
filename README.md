# QA-Chatbot-Using-Llama3-and-Groq

This project demonstrates how to create a Question-Answering (QA) chatbot using Llama3, GROQ, and OpenAI embeddings with a Streamlit interface. The chatbot is designed to answer questions based on the context provided by documents loaded from a specified directory.

Techstack

- Streamlit
- PyPDF2
- Langchain
- GROQ
- OpenAI Embedding

Installation

1. Clone the repository:

```
git clone https://github.com/patelshehbaz/QA-Chatbot-Using-Llama3-and-GROQ.git
```

Set up environment variables by creating a .env file in the root directory and adding your OpenAI and GROQ API keys:

```
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```

Run the Streamlit application:

```
streamlit run app.py
```
