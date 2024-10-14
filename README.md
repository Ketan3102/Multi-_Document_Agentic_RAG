# Multi-Document Agentic RAG

This repository contains a Jupyter notebook that demonstrates the implementation of a **Multi-Document Agentic Retrieval-Augmented Generation (RAG)** model using the **LLamaIndex** framework. The notebook walks through the process of building a model capable of retrieving and generating insights across multiple documents, scaling from a basic setup to handling a larger corpus efficiently.

## Overview

RAG combines the strengths of information retrieval with generation capabilities, enhancing language models' responses by grounding them in external documents. In this project, we explore the following key steps:

- **Document Ingestion**: Loading and parsing multiple documents using the LLamaIndex framework.
- **Index Creation**: Structuring the documents for optimized retrieval using various indices.
- **Query Processing**: Implementing a query system that retrieves relevant information and generates comprehensive responses.
- **Scalability**: Scaling the system from a 3-document setup to an 11-document setup, maintaining performance and relevance.

## Key Features

- **Multi-Document RAG**: Supports retrieval and generation over multiple documents, making it highly versatile for applications requiring knowledge from diverse sources.
- **Agentic System**: The system allows for autonomous decision-making to determine the best documents to consult for generating the most accurate responses.
- **Efficient Scaling**: Demonstrates how to scale the RAG system from a small number of documents to a larger set without significant performance trade-offs.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Ketan3102/Multi_Document_Agentic_RAG.git
   cd Multi_Document_Agentic_RAG
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the notebook and execute the cells to run the RAG model.

## Usage
* You can modify the document set in the notebook to explore retrieval over different documents.
* Experiment with different queries to see how the system processes and generates responses.
* The notebook contains explanations at each step to help you understand how to extend the model for larger-scale retrieval tasks.

## For More In-depth Understanding
For a detailed explanation of the Multi-Document Agentic RAG and its scalability, refer to the following blog posts:

1. [Multi-Document Agentic RAG using LLamaIndex - Part 1](https://www.analyticsvidhya.com/blog/2024/09/multi-document-agentic-rag-using-llamaindex/)
2. [Scaling Multi-Document Agentic RAG - Part 2](https://www.analyticsvidhya.com/blog/2024/10/scaling-multi-document-agentic-rag/)

These blogs provide step-by-step guides and discuss advanced techniques to improve the performance and scalability of the RAG system.
