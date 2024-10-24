![image](https://github.com/user-attachments/assets/49ec3be6-9129-4ec7-8132-ba97df1b09ab)


# Langchain---Fundumentals

# Objective : This repository serves as a comprehensive resource for learning and exploring the fundamentals of LangChain, a powerful framework for building applications that leverage large language models (LLMs).

# Section 1 : 

Langchain Models : A model in the context of LangChain is any language model that is used to generate a series of words trained on a probabilistic model in a natural language. Langchain provides two types of models :

1. LLM : LLMs are the core part of LangChain that takes a string as an input and returns a string at the output. LangChain provides a standard interface with several LLMs, such as OpenAI, Cohere, Hugging Face, etc.
2. Chat model

# Section 2 : 

Prompts : A prompt is a query that stores the style and format of an input to a model that answers the query accordingly. Prompts play an important role in the interaction with language models. A careful crafting of prompts is essential to get the desired and effective response from the model. To ease the prompting tasks, LangChain provides prompt templates.

1. Basic Prompt template
2. Few-shot prompt template

# Section 3 :

Output Parsers : LLMs typically provide a string of text as an output. However, when creating an LLM-powered application, we might need a more structured and formatted output that provides us with concise information rather than reading the complete response. Parsers are a tool that can help us in getting a structured output.

# section 4 : 

Chains : A chain contributes to a sequence of decision-based LLM calls connected by inputs and outputs. It can handle multiple elements of an application using prompt templates, which makes the streamlined process smooth and enhances the application’s capabilities.

1. LLM chain
2. Sequential chain
3. Router chain

# section 5 : 

Memory : LangChain provides memory buffers to facilitate a conversational interface where the information exchanged between the user and the model can be stored. These memory buffers act as a context store, allowing the model to retain and utilize relevant information from previous messages in the ongoing conversation.

1. Conversation buffer
2. Conversation window
3. Conversation summary

# Section 6 : 

Agents and Tools : Agents in LangChain make decisions and take action by utilizing a language model. Unlike traditional chains, where a sequence of actions is hardcoded in code, agents use a language model to generate the response based on the user’s input and the available tools.

1. Zero-shot ReAct
2. Conversational ReAct

# Section 7 : 

Data Ingestion and Text Splitting

# Section 8 : 

Example of a Q&A RAG application 


Note.
The Openai API_key is a placeholder , please generate an API key and replace it while exceuting the code .
The other key is SERP_API_KEY for tool usage , please go to the following link and create your key  https://serpapi.com/ 




