# PDF-Text-Embedding-RAG-System

## Problem Statement
Extract text from PDF files stored in Azure Blob Storage, generate embeddings using open-source LLM, and create a Retrieval Augmented Generation (RAG) system to perform document queries.

## Prerequisites
- Azure Databricks workspace
- Azure Blob Storage account
- Python 3.x
- Access to Azure Blob Storage container

## Required Libraries
- langchain
- langchain_community
- sentence-transformers
- chromadb
- PyPDF2
- transformers
- torch

## Configuration
```python
storage_account_name = "genaicertificationsa"
container_name = "gen-ai-container"
mount_point = "/mnt/gen-ai-container"
```

## Features
- **Azure Blob Storage Integration**
  - Secure mounting to DBFS
  - Efficient file access management
  - Blob storage connectivity validation

- **PDF Processing**
  - Text extraction from PDF documents
  - Content validation and cleaning
  - Multi-page document support

- **Embedding Generation**
  - Integration with open-source LLM
  - Sentence Transformer implementation
  - Vector representation creation

## Installation Steps
1. **Repository Setup**
   - Clone the repository
   - Configure development environment
   - Set up virtual environment

2. **Azure Configuration**
   - Configure storage credentials
   - Set up authentication
   - Validate access permissions

3. **Dependencies**
   - Install required packages
   - Configure environment variables
   - Verify installations

4. **Storage Setup**
   - Mount blob storage
   - Validate connectivity
   - Set up access paths

## Usage Guide
1. **Storage Operations**
   - Mount Azure Blob Storage
   - Verify mount points
   - Access PDF files

2. **Document Processing**
   - Load PDF documents
   - Extract text content
   - Validate extracted data

3. **Embedding Operations**
   - Generate text embeddings
   - Create vector store
   - Validate embedding quality

## Error Handling
- **Storage Validation**
  - Mount point verification
  - Access permission checks
  - Connection status monitoring

- **Document Processing**
  - File existence validation
  - Format verification
  - Content extraction validation

- **Embedding Generation**
  - Model loading verification
  - Processing error management
  - Output validation

## Contributing Guidelines
1. **Repository Management**
   - Fork the repository
   - Create feature branches
   - Follow coding standards

2. **Development Process**
   - Implement changes
   - Test thoroughly
   - Document updates

3. **Submission**
   - Create pull requests
   - Address review comments
   - Update documentation
