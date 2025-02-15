# Contract Advisor RAG (Contract Reviewer & Analyzer)
## Business Need
In today's fast-paced business environment, organizations are faced with an ever-increasing volume of contracts to manage. Manual contract review and management processes are time-consuming, prone to errors, and can lead to missed opportunities, compliance issues, and financial losses. There is a pressing need for an automated contract review and management system that can accurately identify key contract terms, detect potential risks, and provide actionable insights to support informed decision-making.
Legal professionals, including in-house counsel and law firm attorneys, spend a significant amount of time reviewing contracts. According to industry estimates, contract review consumes approximately 50-60% of a legal professional's time. 

## Goal
The objective of the project is to build, evaluate, and improve a RAG (Retrieve, Answer, Generate) system for Contract Q&A. This system will enable users to interact with contracts, asking questions and receiving relevant answers, effectively creating a conversational interface for contract-related inquiries. Instead of reinventing the wheel, the project will leverage existing frameworks and open-source projects specialized in LLM (Large Language Model) applications, such as Langchain, LlamaIndex, and Azure Rag. By adopting Langchain, a prominent LLM application framework, the focus will be on mastering RAG fundamentals, evaluating the RAG pipeline’s performance, and refining the quality of contract Q&A interactions.
In order to accomplish the goal of this project the first thing we need is to review literatures and trending analysis.

## RAG Pipeline Overview
The essence of Retrieval-Augmented-Generation (RAG) technology lies in the seamless integration of two key AI methodologies: information retrieval and generation. RAG systems elevate the accuracy of language models by dynamically sourcing relevant information from different data sources. This strategy overcome the constraints faced by LLMs dependent solely on pre-existing knowledge. Through coordination of retrieval mechanisms, these models tap into current datasets, empowering them to produce responses that are not just coherent, but also
inspire with contextual depth and factual precision.

## Dependencies
The project requires the following libraries and frameworks:
- Langchain: a leading LLM application framework
- LLM API: for embedding and retrieval
- RAGAS: a RAG evaluation framework

## Usage
To run the project, follow the following steps
- Clone the repo
- Install the dependencies: pip install -r requirements.txt
- To run the backend: cd backend and python3 server.py
- To run the fronted: cd frontend and npm run dev
    


