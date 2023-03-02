# Prompt-Engineering-Intro
This repository contains a starter python notebook to get one started with basic Prompt engineering using OpenAI's GPT3 models. This accompanies the medium blog: [An Introduction to Prompt Engineering for OpenAI GPT LLMs](https://medium.com/cloudcraftz/an-introduction-to-prompt-engineering-for-openai-gpt-llms-f109ca4f1739)

### Setup
1. Create a new environment using conda 
   
    `conda create -n genai python=3.10`

2. intall required packages 
   
   `pip install -r requirements.txt`

You also need to create couple of api keys
- OpenAI Api Key - signup and generate one here - https://platform.openai.com/signup
- SerpApi Key - Setup Search capability to be able to search using Google and various other services. Visit this link and follow instructions to create an api key - https://serpapi.com/

One of the example uses Sqlite database - [chinook](https://database.guide/2-sample-databases-sqlite/), a database representing a digital media store, including tables for artists, albums, media tracks, invoices and customers. 

### References
#### Libraries used:
1. [openai](https://platform.openai.com/docs/libraries)
2. [LangChain](https://github.com/hwchase17/langchain)

#### Papers referenced
1. Chain of Thoughts Prompting - https://arxiv.org/pdf/2201.11903.pdf
2. Self Consistency Prompting - https://arxiv.org/pdf/2203.11171.pdf
3. ReAct - Reason and Act prompting - https://arxiv.org/pdf/2210.03629.pdf
4. PAL - Program aided Language Models - https://arxiv.org/pdf/2211.10435.pdf
5. MRKL Systems - Modular Reasoning, Knowledge and Language  - https://arxiv.org/pdf/2205.00445.pdf
6. Self Ask with Search - https://arxiv.org/pdf/2210.03350.pdf

#### Misc other references
1. https://learnprompting.org/
2. https://github.com/dair-ai/Prompt-Engineering-Guide
   

