# E2E_IE_ChatBot_LLama2
Chatbot for Industrial Engineering Handbook


##Steps to run the project
1. Create own env: ```conda create -n ie_chatbot_env python=3.12.5 -y```
2. Activate env by : ```conda activate ie_chatbot_env```
3. Install requirements: 
   1. ctransformers-0.2.5 - For quantized model to run on CPU
   2. sentencetransformers-2.2.2 - For Embeddings Model from HuggingFace
   3. pinecone-client - For Pinecone
   4. langchain - 0.0.225 - For langchain
   5. flask - For frontend
4. To install: ```pip install -r requirements.txt```
5. Run: ```!pip install --upgrade langchain```
    ```!pip install -U langchain-community```
    ```!pip install pinecone```
6. Create Pinecone Cluster: 