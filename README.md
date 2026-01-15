# Educational AI Assistant

## About
This project is an intelligent agent that answers student questions about educational processes at Lviv Polytechnic National University (NULP) and mathematical concepts.

It uses RAG (Retrieval-Augmented Generation) to search through NULP documentation and Wikipedia, providing accurate, source-attributed answers in Ukrainian.

## What It Does
The notebook (`agent.ipynb`) includes:
- loading and indexing NULP educational documents (PDFs),
- semantic search using multilingual embeddings,
- intelligent query routing to appropriate information sources,
- Wikipedia integration for mathematical concepts,
- structured response generation with source attribution.

The agent automatically:
- filters out off-topic questions,
- selects the best tool (NULP docs or Wikipedia),
- provides clear answers with confidence indicators.
