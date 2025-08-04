HELP MATE AI is a PDF-based question-answering system designed to semantically search and extract contextual answers from insurance policy documents using large language models (LLMs), semantic embeddings, vector databases, and reranking techniques.
This system is optimized for life insurance documents and enables:
•	PDF parsing & preprocessing
•	Document indexing using OpenAI embeddings
•	ChromaDB persistent storage
•	Query caching
•	Semantic search
•	Reranking using CrossEncoder
•	LLM-based contextual response generation

Dependencies
Library	Purpose
pdfplumber	PDF parsing
tiktoken	Token counting
openai	Embeddings + GPT chat
chromadb	Persistent vector storage
sentence-transformers	Cross-encoder reranking
pandas	Data structuring
google.colab.userdata	Secure API key storage
	

System Requirements
- Python 3.8+
- Google Colab or Jupyter
- OpenAI API key
- Internet connection
