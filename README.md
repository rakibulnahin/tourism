# tourism
I am trying to create a chatbot that can assist people in creating a travel plan for people who love to travel.
I am using Llama model for making my chatbot.

Jupyter notebook llama2-fine-tuning-for-travel-chatbot.ipynb has the code to train llm and also the Llama weights are here
I am trying to use image and text prompt both for a better travel recommendation system so that it can help people see their travel plan

The reply I am currently getting from the fine-tuned model is shown below but I want to make a more vivid and descriptive response

<img width="500" height="700" alt="image" src="https://github.com/user-attachments/assets/ebf8a65e-a335-4387-bf4a-427cc6164690" />

My second chaarge!!
I have used Chroma based vector database with tag based queries and SegTransformer for image segmentation. 
All this pass info to the RAG system to choose the best information based on which LLM provides the simple. 

<img width="500" height="700" alt="image" src="https://github.com/user-attachments/assets/9a6f6e88-d811-47d1-8fde-38109f660a0c" />

Just asked it where to go for a swim and it replied Bondi not a fan of bondi thought but workss!!!

Next Integrate with my trained model for better response and chatting rather than just Q&A
