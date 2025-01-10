# Contextual PDF RAG (Retriever-Augmented Generation)

This project is designed to **help users limit the scope of their queries** by enabling them to upload specific PDFs (such as books, novels, or any other documents) and retrieve answers directly from the provided content. This system allows users to ask context-aware questions, maintain a conversational history, and get precise answers from their uploaded documents.

Whether you're studying a novel, analyzing a technical manual, or referencing a handbook, this tool simplifies the process by focusing on the specific content you provide.

## Features

- **Custom Scope Limitation**: Users can upload any PDF to define the boundaries of their queries.
- **Efficient Document Retrieval**: Quickly find the most relevant sections of the uploaded document.
- **Contextualized Answers**: Provides answers considering the document content and conversational history.
- **Stateful History Management**: Tracks user conversations over multiple queries and ensures a seamless interaction experience.
- **Versatile Use Cases**: Ideal for researchers, students, writers, and professionals seeking insights from specific documents.

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
    git clone https://github.com/davetej/GenAI.git
    cd GenAI
    ```

2. **Install dependencies**:
    Create a virtual environment and install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

    Let's Play!
