# Q&A Chatbot using Mistral 7B model and RAG Approach
Creating an end to end chatbot using Open Source Mistral 7B model from HuggingFace to chat with Pdf's using RAG based approach.
## Architecture for Q&A Chatbot using Mistral 7B LLM based on RAG Method.
![GenAI_Chatbot](https://github.com/Rahul713713/Q-A_Chatbot_using_Mistral_and_RAG_Approach/blob/main/images/RAG.png "Q&A Chatbot Power by Gen AI using Mistral LLM and RAG")
- Used an open source model called Mistral 7B from HuggingFace along with the Langchain Library to build a product that can be used to chat with the uploaded PDF.
- Built the solution in two parts where the first part uses Tesla T4 GPU provided by Google Colab to run the ~14 GB Mistral 7B model using GPU and then created a production ready codebase using streamlit and python for the same solution. 
- Explained concepts like RAG, Vector embeddings, Open source LLMs,etc. in the google colab notebook and built a production ready Gen AI powered chatbot using Mistral 7B, Langcahin and Streamlit.
- Used **Attention is all you need** research paper to demonstrate the application as this is probably the most important reseach paper in the history of NLP and LLMs. 

# Problem Statement
### The Solution is built in two parts to give a complete undestanding of building an end to end project from stratch to deploying it to production. 
#### Part 1: Build a solution using Mistral 7B LLM based on RAG methodology to interact with PDF's on Goggle Colab
The objective here is use the ~14GB Mistral 7B model from HuggingFace to built the prototype and test the solution using T4 GPU provided by Google Colab.

### Part 2: Build an end to end Q&A Chatbot using Mistral 7B LLM and Streamlit based on RAG methodology to interact with PDF's on local CPU. 
Here, we try to build a end to end Q&A Chatbot tailored for PDF interaction and powered by Mistral 7B, Langchain, and Streamlit. This solution runs seamlessly on your local laptop, putting the power of dynamic Q&A sessions right at your fingertips. **No need for GPU.**

While operating on a CPU, the response time may be delayed. However, the primary objective is to gain insights and enhance our understanding of the system over the inference time.

# Models and Libraries used
- Libraries: python, langchain, langchain-community, sentence-transformers, llama-cpp-python, faiss-cpu, streamlit, streamlit_chat, pypdf, etc.
- Model:  Mistral 7B from HuggingFace

# Important resources
- Link to download the model-> https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.2-GGUF/blob/main/mistral-7b-instruct-v0.2.Q2_K.gguf)
