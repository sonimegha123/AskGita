#DocChat: Where PDFs Open Up to Conversation

Overview  

DocChat is a Streamlit-based web application that allows users to interact with PDF documents by uploading them and then querying their content using natural language. The application utilizes OpenAI's language models to generate responses based on the content of the uploaded documents. This project is particularly useful for extracting insights, answering questions, or exploring the content of PDFs without manually reading through them. 

Features  

1. Upload PDFs: Users can upload multiple PDF files through the sidebar. These files are saved to a designated directory for processing.
Document Indexing: Uploaded documents are indexed, allowing for efficient querying using OpenAI's language models.
2. Query Documents: Users can input questions related to the content of the uploaded documents. The application will generate a response based on the indexed data.
3. Pre-loaded GitaGyan: The application includes a special feature where the users' can get answers to their questions based on Gita. 

Requirements 

Python 3.7+
Streamlit
OpenAI Python Client
LlamaIndex
PyPDF2 
