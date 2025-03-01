# RAG with LLM using data of financial glossary from SEBI
 
In this project, we will see an example of RAG with Llama LLM using glossary definition from SEBI on capital markets. We provide the glossary definition as context to LLM to generete response. This is a base version for **experimentation**, this project could be improved to question answering on any docuement for better user interaction. Since the glossary is provided by a recognized institution, it improves the credibility of response from the cahtbot. Also users with less exposure in financial terms can use LLMs to increase their understanding in an interactive and easy way rather distilling large pdf documents

Attached the jupyter notebook for this experimental project. We could see the response from chatbot matching the glossary definition from SEBI.

Few improvements that can be made:

1) using finance specific embedding instead of generic text embedding
2) vector db for storing the RAG information
3) deepseek llm instead of Llama for better reasoning with knowledge graph for complex data
4) text preprocessing : here the text is split into fixed chunks, further processing could be done to better splits.
5) pdf with with images and tables : for this, agentic document extraction could be used for better results e.g. landing.ai

Reference :

Data - https://www.sebi.gov.in/reports/glossary/mar-2004/glossary-of-capital-market_12317.html

Code - https://huggingface.co/blog/ngxson/make-your-own-rag
