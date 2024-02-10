# NLP
NLP Project - RAG

| Module  		| Type 			| Task 			|
| ------------- | ------------- | ------------- |
| Loader  		| FE/BE  		| 1. Add UI for Uploading pdf, word document and text file.</br> 2. Add UI for reading/downloading pdf, word document and text file from urls. </br> 3. Record each file detail in RAG Source table in database </br> 4. rag_source must have a unique id for each document so if document is expired or not applicable, can be delated from Vector database and our database </br> 5. vector database must have meta id for our database record, which will be used for deletion  |
| Embed  		| BE  			| 1. Read data from uploaded files and chunk them </br> 2. Embed using embedded model  |
| Indexer  		| BE  			| 1. Store embedded data into vector database </br> 2. delete api must be available with cleaning feature  |
