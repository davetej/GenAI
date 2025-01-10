# Contextual PDF RAG (Retriever-Augmented Generation)

This repository implements a **Retriever-Augmented Generation (RAG)** system that processes PDF documents and answers questions based on the content. It uses advanced NLP techniques to contextualize prompts and provide relevant answers, while also maintaining chat history across multiple interactions.

## Features

- **PDF Processing**: Load and parse PDFs for document retrieval.
- **Contextual Question Formulation**: Reformulate questions to improve clarity and relevance with respect to the chat history.
- **Retriever-Augmented Generation**: Leverage a combination of document retrieval and generative language models (GPT-4) to answer questions.
- **Stateful History Management**: Track user conversations over multiple queries and provide a coherent context for ongoing interactions.

## Requirements

To run this project, you need Python 3.x and the following libraries:

- `langchain`
- `openai`
- `chromadb`
- `pdfminer.six`
- Other required dependencies listed in `requirements.txt`

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. **Install dependencies**:
    Create a virtual environment and install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

    Let's Play!
