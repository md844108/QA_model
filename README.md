# QA_model
## AIM : 
Here I am implementing a QA model in which you upload files of any type and can also give a git link. After that, you can ask questions based on the information available in the document.

## The following are the concepts, tools, and libraries that I used to build this prototype:
    Semantic search.
    Embeddings.
    Facebook Faiss.
    langchain.
    Openai’s GPT-3.

## References
   https://github.com/whitead/paper-qa
   
## huggingface app deploy link
https://huggingface.co/spaces/irfan844108/Doc-QA

## Requirement OpenAI key
Open OpenAI website(https://platform.openai.com/account/api-keys) and create key , It will use in code.

## Install some pckages on which our dependency

      pip install paper-qa>=0.0.21
      pip install gradio
      pip install requests
      pip install transformers
 
## To Run Code 
        gradio app.py
