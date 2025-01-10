# RAG Q&A Conversation With PDF Including Chat History

A Conversational Q&A Chatbot that enables interactive discussions with PDF documents while maintaining chat history. The project combines RAG (Retrieval Augmented Generation) with conversation memory to create an intelligent document interaction system.


**Key Features**

• PDF document processing and vectorization

• Contextual question answering using transformer models

• Conversation history tracking across sessions

• Interactive chat interface using Streamlit

• Vector storage using Chroma DB

• Document chunking and embedding generation

• History-aware retrieval system


**Technical Components**

• LLM Integration: Uses Grok's Gamma2 model for text generation

• Embeddings: Implements HuggingFace embeddings for document vectorization

• Document Processing: Handles PDF parsing and text chunking

• Memory Management: Maintains conversation context through session-based history

• Vector Storage: Utilizes Chroma for efficient document retrieval


**Usage**

• The system allows users to:

• Upload PDF documents for analysis

• Ask questions about document content

• Reference previous conversations

• Get contextual responses based on document content and chat history

• Request conversation summaries
