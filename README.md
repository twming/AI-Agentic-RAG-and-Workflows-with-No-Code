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
<img src="https://github.com/twming/AI-Agentic-RAG-Workflows-with-No-Code/blob/main/img/n8n_1.png" width="600">
- Setup your OpenAI API Key in the OpenAI Model
<img src="https://github.com/twming/AI-Agentic-RAG-Workflows-with-No-Code/blob/main/img/n8n_2.png" width="600">
- Test your agent.

### Activity 4:

### Activity 5:
### Activity 6:
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
