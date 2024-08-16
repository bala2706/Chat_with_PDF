# 📄 Chat with PDF 💬

## Overview

**Chat with PDF** is a web application that allows users to interact with PDF documents by asking questions and receiving detailed, context-aware answers. The app utilizes Streamlit for the frontend, LangChain for text processing, and Google Generative AI for embedding and conversational responses.

## Features

- 📤 **PDF Upload**: Upload multiple PDF files for processing.
- 📝 **Text Extraction**: Efficiently extracts text from PDF documents.
- 📚 **Text Chunking**: Splits large texts into manageable chunks using LangChain’s Recursive Character Text Splitter.
- 🔍 **Embeddings and Vector Store**: Uses Google Generative AI Embeddings to create a vector store with FAISS for similarity searches.
- 🤖 **Conversational AI**: Generates detailed responses to user queries using Google’s Gemini model.
- 💻 **User-Friendly Interface**: Built with Streamlit for an intuitive and responsive user experience.

## Try it Out!

Explore **Chat with PDF** now:
[Launch Chat with PDF App](https://your-app-link.streamlit.app/)

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:
- Python 3.7 or higher
- pip (Python package installer)

### Installation

Follow these steps to install and run the application:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your_username/chat-with-pdf.git
    cd chat-with-pdf
    ```

2. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Create a `.env` file:**

    In the root directory of the project, create a file named `.env` and add your environment variables. For example:

    ```plaintext
    GOOGLE_API_KEY=your_google_api_key_here
    ```

4. **Run the app:**

    ```bash
    streamlit run app.py
    ```

### Configuration

Ensure your `.env` file is correctly configured with your API keys and other necessary environment variables.

```plaintext
GOOGLE_API_KEY=your_google_api_key_here
