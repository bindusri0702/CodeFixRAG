# CodeFixRAG: AI-Powered Code Error Correction

**CodeFixRAG** is an advanced AI system that uses Retrieval-Augmented Generation (RAG) to automatically suggest corrections or fixes for errors in Python code. By leveraging the traceback information from errors, the system retrieves relevant code lines and generates corrected code suggestions.

## Features
- **Traceback-Driven Retrieval**: Uses error traceback to find the most relevant code snippets.
- **RAG-Powered Code Fixes**: Combines `relevant_code` and `traceback_info` to generate code fixes.
- **Vector Search Integration**: Retrieves relevant parts of the codebase using vector search models for more precise error identification.

## How It Works
1. **Input Error Traceback**: When an error occurs in your code, simply copy the `traceback_info` from the error message.
2. **Retrieve Relevant Code**: The vector search model analyzes the `traceback_info` and retrieves relevant code lines from the entire codebase.
3. **Generate Fixes**: Using the retrieved code and traceback, the RAG model suggests a correction or fix for the error.
4. **Correct Your Code**: Review the suggested code correction and apply the changes to fix the error.

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/CodeFixRAG.git
cd CodeFixRAG
pip install -r requirements.txt
```
