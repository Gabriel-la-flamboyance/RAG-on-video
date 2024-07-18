# RAG-on-video
Making Retrieval-Augmented Generation (RAG) on a video
# Definition
Retrieval-augmented generation (RAG) is a technique for enhancing the accuracy and reliability of generative AI models with facts fetched from external sources.

To understand the latest advance in generative AI, imagine a courtroom.

Judges hear and decide cases based on their general understanding of the law. Sometimes a case like a malpractice suit or a labor dispute requires special expertise, so judges send court clerks to a law library, looking for precedents and specific cases they can cite.

Like a good judge, large language models (LLMs) can respond to a wide variety of human queries. But to deliver authoritative answers that cite sources, the model needs an assistant to do some research.

The court clerk of AI is a process called retrieval-augmented generation, or RAG for short.

![image](https://github.com/user-attachments/assets/e93219a1-567b-4e8b-9202-5ad153515ba6)

![image](https://github.com/user-attachments/assets/c7e4ffef-120f-4fc7-b829-89707b999ac7)

# Cosine similarity
Cosine similarity measures the similarity between two vectors of an inner product space. It is measured by the cosine of the angle between two vectors and determines whether two vectors are pointing in roughly the same direction.
![image](https://github.com/user-attachments/assets/3f301e30-5bf5-4431-aa9f-f1cbdad800d5)

# Usage
In a google colab notebook, load the notebook and in the files load your .env file containing the keys and VOILA!. 

In the .env file make sure to have:

OPENAI_API_KEY = [ENTER YOUR OPENAI API KEY HERE]

PINECONE_API_KEY = [ENTER YOUR PINECONE API KEY HERE]

![image](https://github.com/user-attachments/assets/de7e6f71-1416-46bf-ba7b-664723ea43b4)

# In the pinecone

![image](https://github.com/user-attachments/assets/f8e51255-2187-416a-82f6-922c65701dca)

Choose the model

![pinecone](https://github.com/user-attachments/assets/ced12ee8-dcc0-4c96-b892-7da030acca1c)
