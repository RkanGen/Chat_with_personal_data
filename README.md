# Chat_with_personal_data

# Chat with Your Data Using LangChain

This repository demonstrates how to create a conversational AI that interacts with your data using [LangChain].
It walks through the essential steps of loading documents, splitting them, retrieving relevant information, and performing question answering (Q&A) using vector stores and embeddings.

## Repository Structure

- **document_loading.ipynb**: This script handles the loading of various types of documents into the system. It ensures that the data is in a suitable format for further processing.
  
- **document_splitting.ipynb**: After loading the documents, this script splits the documents into manageable chunks, which are necessary for efficient retrieval and processing.
  
- **retrieval.ipynb**: This script implements the retrieval logic. It uses the vectorized representations of document chunks to fetch the most relevant sections in response to a query.
  
- **Q&A.ipynb**: This script is responsible for the question-answering process. It leverages the retrieved information to generate accurate and context-aware answers.
  
- **Vectorstore.ipynb**: This file deals with the creation and management of vector stores, which are essential for storing and retrieving the embeddings of document chunks.
  
- **embeddings.ipynb**: This script generates embeddings for the document chunks using pre-trained language models, allowing for efficient similarity searches during retrieval.

## How It Works

1. **Document Loading**: Import and load your documents into the system.
2. **Document Splitting**: Split the loaded documents into smaller, more manageable chunks.
3. **Embeddings**: Generate embeddings for each document chunk to enable vector-based retrieval.
4. **VectorStore**: Store the embeddings in a vector database for fast retrieval.
5. **Retrieval**: Query the vector store to retrieve the most relevant document chunks.
6. **Q&A**: Use the retrieved information to answer user queries accurately.

## Getting Started

### Prerequisites

- Python 3.9+
- LangChain
- API key from OpenAi

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/RkanGen/Chat-with-personal_data.git
   cd Chat-with-personal_data
