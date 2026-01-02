# RAG
Retrieval Augmented Generation

## Components of RAG
**1. Data collection and Preprocessing**
- - This is the foundation: gathering and preparing the knowledge base.

**2. Indexing and Embedding**
- - Transforming text into vector representations for retrieval.

**3. Store data in  Vectorstores**
- - Stores the embedded chunks in vectorstores which acts as Knowledge base

**4. Retrieval**
- - Finding the most relevant chunks from the knowledge base.

**5. Fusion/Reranking**
- - Improving the quality of retrieved results before generation.

**6. Prompting**
- - Create proper prompt which include instructions and retrived content

**7. Memory**
- - For chat conversion need to add memory to RAG

**8. Generation**
- - The model generates answers using retrieved context.

**9. Post Prcessing**
- - Ensuring the output is accurate, useful, and safe.

**10. Feedback and Iteration**
- - Improving the system continuously.