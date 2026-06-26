# Contributing to n8n AI Workflow Automation

Thank you for your interest in contributing! This is a focused library of AI-powered n8n workflows — AI agents, LLM integrations, and RAG pipelines — and it grows thanks to contributors like you.

## Scope

This repository deliberately stays focused on **AI automation**. Workflows should center on at least one of:

- AI agents and assistants (OpenAI, Claude, Gemini, Ollama, DeepSeek, LangChain, etc.)
- LLM-driven automation (generation, classification, extraction, summarization)
- Retrieval-augmented generation (RAG) and vector databases
- AI research, web scraping, and data analysis

Non-AI integrations are out of scope to keep the collection sharp.

## How to Contribute a Workflow

1. **Fork** this repository
2. **Add your JSON workflow** to the matching folder:
   - `OpenAI_and_LLMs/` — AI agents, chatbots, LLM automation, image/audio generation
   - `AI_Research_RAG_and_Data_Analysis/` — RAG pipelines, vector search, research agents, data analysis
3. **Update README.md** by adding a new row to the appropriate category table:
   ```
   | Title | Brief description of what it does. | Department | [Link to Template](Folder/Workflow%20Name.json) |
   ```
4. **Submit a Pull Request** with a clear title and description of the workflow

## Workflow Requirements

- Must be a valid n8n workflow JSON file (exported from n8n)
- Must include a meaningful name and description
- Should be tested and working on a recent version of n8n
- Must **not** contain credentials, API keys, or any sensitive data
- File name should match the workflow title (spaces are fine)

## Reporting Issues

- If a template is broken or contains errors, open an issue with the template name and a description of the problem
- If a template contains credentials or sensitive data, please report it immediately

## Style Guide

| Column | Format |
|--------|--------|
| Title | Full template name as it appears in n8n |
| Description | 1-2 sentences explaining what the template does |
| Department | The business function (e.g., Marketing, Support, Engineering, HR, Ops) |
| Link | Relative path to the JSON file in the repository |

## Code of Conduct

- Be respectful and constructive in all interactions
- Give credit to original template authors where applicable
- Focus on quality over quantity — one well-documented template is better than many untested ones

## Questions?

Open an [Issue](https://github.com/Tayyab-Tahir1/n8n-workflow-automation/issues) and we'll be happy to help.
