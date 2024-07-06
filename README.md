# Alemeno-Assignment
# Content Engine Chatbot

This project demonstrates how to create a Content Engine Chatbot using Streamlit, Google Colab, and `ngrok`. The chatbot extracts insights from PDF files using embeddings and generates responses using GPT-2.

## Features

- Extract text from PDF files
- Create FAISS indices for text embeddings
- Query indices to retrieve relevant text
- Generate insights using GPT-2

## Requirements
- Google Colab
- Streamlit
- ngrok
- sentence-transformers
- faiss-cpu
- transformers
- PyMuPDF

# Development Steps
- Parse Documents: Extract text and structure from PDFs.
- Generate Vectors: Use a local embedding model to create embeddings for the document content.
- Store in Vector Store: Utilize local persisting methods in the chosen vector store.
- Configure Query Engine: Set up retrieval tasks based on document embeddings.
- Integrate LLM: Run a local instance of a Large Language Model for contextual insights.
- Develop Chatbot Interface: Use Streamlit to facilitate user interaction and display comparative insights.


## Usage Guide
1. **Go to the website given by ngrok https://c45e-34-16-144-25.ngrok-free.app/**.
2. **Enter your query** and **get the answer** from the chatbot.
3. **View the results** from the FAISS index and the generated insights from GPT-2.

## Troubleshooting

- If you encounter any issues with package installations, restart the Colab runtime and try installing the packages again.
- Ensure that the PDF files are properly uploaded before running the query.

## License

This project is licensed under the MIT License.

---
