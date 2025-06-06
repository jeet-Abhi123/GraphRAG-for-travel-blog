# GraphRAG for a travel blog
Using [Neo4j](https://neo4j.com/product/auradb/) graph database I created a RAG system utilizing knowledge graphs. <br> 

### 🎯 Goal 
Goal is to scrape a website and load the text file using langchain. And by using Cypher query language(retrieving), we can get structured and contextualizaed response from an LLM. <br> 
Blog : [Seven Sister Hill](https://fitnesstravelfood.com/seven-sisters-hill-the-best-trek-near-nagpur/)


### Knowledge graphs 
These are graphs which have been created using the graph transformers. In future work, I can improve the quality of node and relationships by manually creating it. <br> 

![KG_1](https://github.com/user-attachments/assets/c638e846-a923-45b3-9a03-26da1d9a4bdf) <br> 
The above graph captures the 7 different hills which are the part of the Seven Sister hill. <br> 
Some more important relationships captured. 

![KG_3](https://github.com/user-attachments/assets/e4ea594c-1f35-46ed-ae95-bfde1e07eeb4)
