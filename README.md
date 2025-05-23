## Question Answering System Based on Retrieval-Augmented Generation (RAG)
Tools & Technologies: Python, Jupyter Notebook, spaCy, scikit-learn, PyMuPDF, NLP, Sentiment Analysis, Named Entity Recognition (NER), Retrieval-Augmented Generation (RAG)

Project Overview:
As part of my final year academic project, I developed an AI-based Question Answering (Q&A) system leveraging Retrieval-Augmented Generation (RAG). The system is designed to answer user questions intelligently by retrieving relevant information from documents and generating accurate, context-aware responses.

Key Features:
  1) Retrieval-Augmented Generation (RAG): Combines document retrieval with generative models to produce high-quality, natural language answers based on the content of uploaded documents.
  2) Multistage NLP Pipeline:
    Document Preprocessing: Uses PyMuPDF to extract and preprocess text from PDFs.
    Question Processing Module: Implements intent classification, Named Entity Recognition (NER), and sentiment analysis using spaCy and scikit-learn pipelines.
    Document Analysis Module: Extracts key entities and sentiment context from documents to match question intent with relevant answers.
  3) Interactive Interface: A CLI-based dialogue system continuously interacts with the user, displays extracted metadata (intent, entities, sentiment), and returns contextual answers.
  4) Support for Free-Text English Questions: Users can ask open-ended questions based on the uploaded content.
  5) Modular and Extensible Architecture: Clear separation of components (input processing, NLP pipeline, user interaction) allows future enhancements or integration with LLMs via APIs.

Technical Highlights:
  Python 3.9+ based implementation using Jupyter Notebook.
  RAG method allows combining traditional information retrieval with neural text generation.
  Intent classification includes multiple categories: factual, instructional, troubleshooting, opinion-based, and definition/clarification.
  Supports multi-document processing and entity-aware answer generation.
  Prepared for integration with external LLM APIs like OpenAI or Google AI Studio.

Deliverables:
  Fully functional Python-based Q&A system.
  Custom NLP pipeline.
  Well-documented source code, compliant with best practices (PEP8, modularity, comments).
  Example data and test cases included.
  Extensible for future cloud or web deployment.
