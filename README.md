# AI-Agentic-RAG-and-Workflows-with-No-Code Activity Guide

### Activity 1: Apply OpenAI API Key
- In order to run your AI Agent, you need an OpenAI API Key, go to below link, create a new account (if you do not have one yet), and API Key
- Note down your API Key and save it in the notepad for later use.
```
https://auth.openai.com/create-account
```
- Download the Docker Desktop, and install in your laptop.
```
https://docs.docker.com/desktop/setup/install/windows-install/
```
> [!TIP]
> Docker Desktop will be use for langflow, n8n and flowise application later.

### Activity 2: Reasoning
- Go to below link:
```
https://agentgpt.reworkd.ai/ 
```
- Ask the the question, observe the reasoning and steps of thinking in the background.
```
Create a comprehensive report of the Coca-Cola company
```
> [!TIP]
> Observe the LLM thinking, tasks and actions.

### Activity 3: Agentic AI Automation Using n8n
- Go to command prompt, run below commands
```
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

- Setup the n8n Agent as below
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/n8n_1.png" width="600">

- Setup your OpenAI API Key in the OpenAI Chat Model
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/n8n_2.png" width="600">

- Test your agent.
> [!TIP]
> Is your agent response to you?
> Ask him some questions? Check if he has memory/history?

### Activity 4: Create a Memory Chatbot
- Go to command prompt, run below commands
```
docker run -p 7860:7860 langflowai/langflow:latest
```
- Setup the LangFlow Agent as below
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/langflow_1.png" width="600">
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/langflow_2.png" width="600">

- Setup your OpenAI API Key
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/langflow_3.png" width="600">

> [!TIP]
> Memory Chatbot
> https://docs.langflow.org/memory-chatbot

### Activity 5: Create a Document Q&A

- Setup the LangFlow Agent as below
- Setup your OpenAI API Key, and upload the "Microwave_Manual.pdf"
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/langflow_4.png" width="600">
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/langflow_5.png" width="600">

> [!TIP]
> What is the highest temperature during grilling?
> How to grill a chicken?
> How to clean up the microwave?

### Activity 6: Create a Chatbot with AgentX
- Setup AgentX account and login
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/agenx_0.png" width="600">

- Create an Agent
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/agenx_1.png" width="600">

- Choose OpenAI model and setup the OpenAI API Key
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/agenx_2.png" width="600">

- Website Embedding, copy the code to embed
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/agenx_3.png" width="600">

- Use the "mock_index.html", paste the embedded code in the body
<img src="https://github.com/twming/AI-Agentic-RAG-and-Workflows-with-No-Code/blob/main/img/agenx_4.png" width="600">

- Test the agent by loading the "mock_index.html"

> [!TIP]
> What is the highest temperature during grilling?
> How to grill a chicken?
> How to clean up the microwave?

### Activity 7:
### Activity 8:
### Activity 9:
### Activity 10:
### Activity 11:
### Activity 12:
### Activity 13:
### Activity 14:
### Activity 15:
### Activity 16:
