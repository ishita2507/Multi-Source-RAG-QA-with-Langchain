# Multi-Source-RAG-QA-with-Langchain
Goal: To build an AI-powered analytics assistant that allows business users to ask questions across company documents, financial reports, company web links, product documentation, and structured company data, while providing grounded answers with source citations. 
In simple terms, built an assistant/system that answer any user question by searching across company pdf, policy documents, weblinks and structured data and provides answers along with source citations. 

# Experimentation
How would the output vary by changing Chunk Size, Chunk Overlap, or no of retrieved documents (Top-3, Top-5, Top-10)

# Flow Diagram
<img width="300" height="350" alt="image" src="https://github.com/user-attachments/assets/82acadbe-df36-4c6c-a254-2e436fac455d" />
<br>
<img width="300" height="100" alt="image" src="https://github.com/user-attachments/assets/fc166a43-0950-4d29-be9f-9a88fc0d187e" />


# Hypothetical Case: AmazonX RetailMart
A fictional U.S. e-commerce company selling consumer products.
This company will have data in multiple sources like;

1. **Company Documents:** Annual Report, Product Strategy, Customer Policy, Returns Policy, Operations Report, Pricing Strategy
2. **Web Content (Web links):** Amazon-hosted Seller Central pages covering returns and shipping-related policies.
3. **Structured Data:** SQL dataset containing: customers, orders, products, sales, returns

# Tech Stack
Language: Python
Data Manipulation: Pandas 
Structured Data: SQLite
Document Ingestion: Langchain
Chunking: Langchain Text Splitters
Embeddings: OpenAI Embeddings
LLM: OpenAI
Retrieval: Langchain
Vector Database: Chroma
UI: Stremalit

   
4. Create our own realistic datasets
5. Explore the structured data with Python/Pandas/SQL
6. Create our business documents
Build the basic PDF/document RAG
Understand embeddings deeply
Build the Chroma vector store
Build retrieval
Connect the LLM
Add structured SQL retrieval
Build hybrid SQL + RAG questions
Add source citations
Add hallucination/“I don't know” handling
Create an evaluation dataset
Measure Precision@K, Recall@K, MRR, faithfulness, etc.
Experiment with chunk sizes / top-K / embeddings
Build Streamlit UI
Package everything for GitHub + resume
Mock interview specifically around this project
And I'll make sure you understand the Python behind the LangChain code rather than memorizing it.


   


