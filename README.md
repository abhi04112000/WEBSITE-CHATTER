# Website Chatter: End-to-End Advanced RAG Platform | LLMOps

## Project Overview

This project involves creating an advanced Retrieval-Augmented Generation (RAG) platform designed for website chat applications. The system integrates various tools and technologies to handle data ingestion, embedding, vector storage, ranking, and LLM operations. The project aims to deliver a robust, secure, and high-performance chatbot solution with advanced RAG capabilities.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [System Architecture](#system-architecture)
- [Results](#results)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)

## Project Description

The Website Chatter project focuses on developing an end-to-end RAG platform for website chat applications. It incorporates advanced technologies for data ingestion, embedding, ranking, and LLM operations. The platform ensures high-speed inference, robust security, and user-friendly interaction through a well-designed interface.

## Features

- **Data Ingestion:** Implemented with WebLoader tool and BeautifulSoup for efficient parsing and chunking of web data.
- **Embedding and Vector Storage:** Integrated OpenAI Embedding with Pinecone Vector DB for vector storage and retrieval.
- **Ranking:** Utilized Hybrid Search and Cohere re-rankers to improve result relevance and accuracy.
- **High-Speed Inference:** Leveraged Llama 3 LLM from Groq with LangChain and Langsmith for managing LLM operations.
- **Security:** Applied NVIDIA Nemo Guardrails to ensure robust security on input and output.
- **User Interface:** Developed a user-friendly interface using Streamlit.
- **RAG Evaluation:** Evaluated using RAGAS, achieving a Faithfulness score of 84% and an Answer Relevance score of 0.78 for 100 sample queries.

## Technologies Used

- **Data Ingestion:** WebLoader, BeautifulSoup
- **Embedding & Vector Storage:** OpenAI Embedding, Pinecone Vector DB
- **Ranking:** Hybrid Search, Cohere re-rankers
- **LLM Operations:** Llama 3 LLM (Groq), LangChain, Langsmith
- **Security:** NVIDIA Nemo Guardrails
- **User Interface:** Streamlit
- **Evaluation:** RAGAS

## System Architecture

1. **Data Ingestion:** Data is ingested using WebLoader and parsed with BeautifulSoup. Data chunks are created using a character splitter.
2. **Embedding & Storage:** Text embeddings are generated using OpenAI's embedding model and stored in Pinecone Vector DB.
3. **Ranking:** Results are ranked using Hybrid Search and re-ranked with Cohere re-rankers to ensure relevance.
4. **Inference:** High-speed inference is performed with Llama 3 LLM from Groq, managed by LangChain and Langsmith.
5. **Security:** NVIDIA Nemo Guardrails are used to secure input and output.
6. **User Interface:** Streamlit provides an interactive interface for user interactions.
7. **Evaluation:** The RAG system is evaluated using RAGAS with metrics for Faithfulness and Answer Relevance.

## Results

- **Faithfulness Score:** Achieved 84% Faithfulness in responses.
- **Answer Relevance Score:** Obtained a score of 0.78 for Answer Relevance on 100 sample queries.

## Usage

1. **Setup:** Ensure all dependencies are installed and configured, including WebLoader, BeautifulSoup, OpenAI Embedding, Pinecone, and CPLEX.
2. **Data Ingestion:** Configure WebLoader and BeautifulSoup to parse and chunk data from the desired sources.
3. **Embedding & Storage:** Integrate with OpenAI Embedding and Pinecone Vector DB for data storage and retrieval.
4. **Ranking & Inference:** Set up Hybrid Search, Cohere re-rankers, and configure Llama 3 LLM with LangChain and Langsmith.
5. **Security:** Apply NVIDIA Nemo Guardrails to secure the input/output processes.
6. **User Interface:** Run the Streamlit app to interact with the chatbot and test its capabilities.
7. **Evaluation:** Use RAGAS to evaluate the system's performance and fine-tune as needed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. For more details, see the [CONTRIBUTING](CONTRIBUTING.md) guidelines.
