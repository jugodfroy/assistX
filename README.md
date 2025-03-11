# ML/LLM Engineer Technical Test - Free

## Overview
This test is designed for applicants to ML/LLM Engineer positions within Free. In this repository, you'll find a python chatbot-like webapp soucring answer from Free knowledge base. Your goal is to adopt this project, improve the actual basic implementation, to showcase your ability to understand a small project and build on top of it.

## Assignment Instructions
1. Follow the Requirements section to setup this projet
2. Pick at least 2 user stories (tickets) from the kanban (ticket board) and implement them. You can also add or implement other user stories you think relevant.

## Deliverables
1. Access to your private repository
2. Brief PDF abstract explaining what you've done, and why.

## Context
Free has local technical support teams operating in various regions across the country. They primarily use a chat interface to address client issues.

## Requirements
### Project Setup
1. Create a private fork of this repository
   - Click "Make a copy" of [this project board](https://github.com/users/jugodfroy/projects/1)
   - Fork the repository and set it as private
   - Grant access to project reviewers (jugodfroy, YohannZe, Ashitaka06)
   - Link the copied project board to your private repository

### Environment Setup
1. Install Ollama
   - Follow the installation guide at [ollama.ai/download](https://ollama.ai/download)
   - Download the text embedding model: `ollama pull nomic-embed-text`

2. Configure Groq API
   - Generate a free API key from [Groq Console](https://console.groq.com/keys)
   - Add your API key to the `server.py` file

3. Application Setup
   - Install dependencies: `pip install -r requirements.txt`
   - Start the server: `python server.py`
   - Access the application at `http://localhost:8888/`

In the repository Project, you'll find a kanban board with several user stories in backlog. Pick several user stories and implement them. You can also add or implement other user stories you think relevant.

## Computing Resources
If you need computing resources, we can provide a Node with GPU access for a 3-hour block. Send your SSH public key to:
- jgodfroy@iliad-free.fr
- yzerbib@iliad-free.fr
- nlamarque@iliad-free.fr


## Timeline and Contact
- Deadline: One week
- To schedule the interview, contact:
  - jgodfroy@iliad-free.fr
  - yzerbib@iliad-free.fr
  - nlamarque@iliad-free.fr

