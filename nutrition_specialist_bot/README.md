# Nutrition Specialist Bot

An AI-powered nutrition specialist bot that provides personalized nutrition advice and guidance based on medical and nutritional references.

This project is a AI nutrition specialist bot deployed hugging-face that leverages LangChain for agent orchestration, LlamaParse/LlamaIndex for document parsing and indexing, ChromaDB/FAISS for vector search, and OpenAI/Llama APIs for LLM-powered responses. It is designed for interactive, evidence-based nutrition advice using advanced retrieval and NLP techniques.

Check the live version in https://huggingface.co/spaces/daniela-veloz/nutrition_bot

## Overview

This project implements an AI agent specialized in nutrition and dietary guidance. The bot is designed to provide accurate, evidence-based nutritional advice while considering individual health factors and dietary requirements.

## Project Structure

- `nutrition_specialist_bot.ipynb`: The main Jupyter notebook containing the bot's implementation
- `Nutritional_Medical_Reference.zip`: Reference materials and data used by the bot for providing accurate nutritional information
- `README.md`: This documentation file

## Features

- Personalized nutrition advice
- Evidence-based dietary recommendations
- Medical reference integration
- Interactive consultation capabilities

## Requirements

To run this project, you'll need:

- Python 3.x
- Colab
- Open AI API key
- Llama API Key
- Required Python packages (specified in the notebook)

## Getting Started

1. Clone this repository
2. Extract the `Nutritional_Medical_Reference.zip` file
3. Open `nutrition_specialist_bot.ipynb` in Colab
4. create `config.json` with the following keys
    - API_KEY (open_ai api key)
    - OPENAI_API_BASE (open_ai api base, default https://api.openai.com/v1/, you still need to add default")
    - LLAMA_KEY (Llamma key)
4. Run the cells in sequence to start using the bot

## Usage

The bot can be interacted with through the Jupyter notebook interface. It's designed to:
- Answer nutrition-related questions
- Provide personalized dietary recommendations
- Consider medical conditions and dietary restrictions
- Offer evidence-based nutritional guidance

# Frameworks Used in the Nutrition Specialist Bot Project

## 1. LangChain
  Core framework for building the AI agent, handling document loading, vector storage, retrieval, prompt management, and agent execution. Enables advanced retrieval-augmented generation (RAG) workflows and integrates with various LLMs and vector stores.

---

## 2. LlamaParse & LlamaIndex
  Parsing and indexing documents, especially for extracting structured information from medical and nutritional references. LlamaParse is used for document parsing, and LlamaIndex for managing and querying document collections.

---

## 3. ChromaDB & FAISS 
  Vector databases for storing and querying dense vector representations of documents, enabling efficient semantic search and retrieval.

---

## 4. OpenAI & Llama APIs
  Accessing large language models (LLMs) for generating responses, embeddings, and performing advanced NLP tasks.

---

## 5. Google Colab
  The notebook is designed to run in Google Colab, leveraging its environment for interactive development, file handling, and user data management.

---

## 6. HuggingFace (CrossEncoder)
  Used for reranking and cross-encoding in retrieval pipelines, improving the relevance of retrieved documents.

---

## 7. Pydantic
  Data validation and structured data management.

---

## 8. Other Utilities
  General Python utilities for file handling, environment management, async operations, progress bars, etc.





