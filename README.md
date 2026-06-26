<div align="center">

# ⚡ n8n AI Workflow Automation

**A curated, import-ready library of 130+ AI automation workflows for [n8n](https://n8n.io).**

AI agents · LLM pipelines · RAG · vector search — built around OpenAI, Claude, Gemini, Ollama, DeepSeek, Mistral & LangChain.
Download a JSON, import it into n8n, plug in your keys, and ship.

<p align="center">
  <a href="https://github.com/Tayyab-Tahir1/n8n-workflow-automation/stargazers"><img src="https://img.shields.io/github/stars/Tayyab-Tahir1/n8n-workflow-automation?style=for-the-badge&logo=github&color=EA4B71&labelColor=14141F" alt="Stars" /></a>
  <a href="https://github.com/Tayyab-Tahir1/n8n-workflow-automation/network/members"><img src="https://img.shields.io/github/forks/Tayyab-Tahir1/n8n-workflow-automation?style=for-the-badge&logo=github&color=6E56CF&labelColor=14141F" alt="Forks" /></a>
  <img src="https://img.shields.io/badge/Workflows-132-EA4B71?style=for-the-badge&labelColor=14141F" alt="132 workflows" />
  <img src="https://img.shields.io/badge/License-CC--BY--4.0-6E56CF?style=for-the-badge&labelColor=14141F" alt="License CC-BY-4.0" />
  <a href="https://github.com/Tayyab-Tahir1/n8n-workflow-automation/commits"><img src="https://img.shields.io/github/last-commit/Tayyab-Tahir1/n8n-workflow-automation?style=for-the-badge&color=EA4B71&labelColor=14141F" alt="Last commit" /></a>
  <a href="https://github.com/Tayyab-Tahir1/n8n-workflow-automation/pulls"><img src="https://img.shields.io/badge/PRs-Welcome-6E56CF?style=for-the-badge&labelColor=14141F" alt="PRs welcome" /></a>
</p>

<p align="center">
  <a href="https://n8n.io"><img src="https://img.shields.io/badge/Try_n8n_Free-Start_Automating-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="Try n8n Free" /></a>
</p>

<a href="https://n8n.io"><img src="img/n8n.png" alt="n8n AI workflow automation" width="640" /></a>

</div>

---

## Table of Contents

- [Quick Start](#quick-start)
- [Why n8n for AI?](#why-n8n-for-ai)
- [What's Inside](#whats-inside)
- [🤖 AI Agents & LLMs](#-ai-agents--llms-89-workflows)
- [🔬 AI Research, RAG & Data Analysis](#-ai-research-rag--data-analysis-43-workflows)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License & Disclaimer](#license--disclaimer)
- [Author](#author)

---

## Quick Start

1. **[Get n8n](https://n8n.io)** — self-host it for free or use n8n Cloud.
2. **Pick a workflow** from the tables below and download its `.json` file.
3. In n8n, open **Workflows → Import from File** and select the JSON.
4. **Add your credentials** (OpenAI, Claude, Gemini, a vector DB, etc.) to each node.
5. **Activate** the workflow and you're automating with AI.

> 💡 Every workflow here is a real, importable n8n file — not a screenshot or a description. Treat it as a starting point and adapt the prompts, models, and nodes to your stack.

---

## Why n8n for AI?

[n8n](https://n8n.io) is an open-source, self-hostable workflow automation platform — and it has become one of the best places to build AI automations without gluing together a dozen SDKs.

- **AI-native nodes** — first-class support for OpenAI, Anthropic Claude, Google Gemini, Ollama, LangChain, and vector stores.
- **Agents & tools** — wire LLMs to tools, memory, and your own APIs to build real agents, not just one-shot prompts.
- **Self-hosted & private** — run models locally with Ollama and keep your data on your own infrastructure.
- **Visual + code** — drag-and-drop when you want speed, drop into JavaScript/Python when you need control.
- **Open-source** — no vendor lock-in, generous free tier, transparent platform.

This library exists to give you a head start: working AI patterns you can import and remix instead of building from a blank canvas.

---

## What's Inside

- **132 AI workflows** across 2 focused categories — no filler, no off-topic integrations.
- **Models & providers:** OpenAI (GPT-4o, DALL·E, Whisper), Anthropic Claude, Google Gemini, DeepSeek, Mistral, Ollama (local), Perplexity, ElevenLabs.
- **Vector & RAG:** Qdrant, Pinecone, Elasticsearch, Supabase, Baserow, NocoDB.
- **Patterns covered:** conversational agents with memory, RAG over documents, autonomous research & web scraping, data extraction, text-to-speech & image generation, sentiment analysis, and AI-driven reporting.

| Category | Workflows | Focus |
|---|:---:|---|
| [🤖 AI Agents & LLMs](#-ai-agents--llms-89-workflows) | 89 | Agents, chatbots, content/voice/image generation, LLM automation |
| [🔬 AI Research, RAG & Data Analysis](#-ai-research-rag--data-analysis-43-workflows) | 43 | RAG pipelines, vector search, research agents, analytics |

---

## 🤖 AI Agents & LLMs (89 workflows)

Conversational AI agents, assistants with memory, LLM-driven content and media generation, data extraction, and automation. Covers OpenAI, Claude, Gemini, DeepSeek, Mistral, LangChain, and local models via Ollama.

| Title | Description | Department | Link |
|---|---|---|---|
| AI Agent to Chat With Files in Supabase Storage | Chats with files stored in Supabase Storage through an AI agent that retrieves and answers questions about them. | AI/Database | [Link to Template](OpenAI_and_LLMs/AI%20Agent%20To%20Chat%20With%20Files%20In%20Supabase%20Storage.json) |
| AI Agent: Google Calendar Assistant Using OpenAI | Manages Google Calendar through an OpenAI-powered assistant that handles scheduling and calendar queries. | AI/Productivity | [Link to Template](OpenAI_and_LLMs/AI%20Agent%20_%20Google%20calendar%20assistant%20using%20OpenAI.json) |
| AI Agent for Realtime Insights on Meetings | Provides realtime AI insights and analysis during meetings. | AI/Productivity | [Link to Template](OpenAI_and_LLMs/AI%20Agent%20for%20realtime%20insights%20on%20meetings.json) |
| AI Agent to Chat With Supabase/PostgreSQL DB | Chats with a Supabase or PostgreSQL database using an AI agent that queries and explains the data. | AI/Database | [Link to Template](OpenAI_and_LLMs/AI%20Agent%20to%20chat%20with%20Supabase_PostgreSQL%20DB.json) |
| AI Agent to Chat With Your Search Console Data Using OpenAI and Postgres | Chats with Google Search Console data using an OpenAI agent backed by Postgres memory. | AI/Data Analysis | [Link to Template](OpenAI_and_LLMs/AI%20Agent%20to%20chat%20with%20you%20Search%20Console%20Data,%20using%20OpenAI%20and%20Postgres.json) |
| AI Agent with Ollama for Current Weather and Wiki | Answers questions about current weather and Wikipedia using an Ollama-powered AI agent. | AI/Productivity | [Link to Template](OpenAI_and_LLMs/AI%20Agent%20with%20Ollama%20for%20current%20weather%20and%20wiki.json) |
| AI Automated HR Workflow for CV Analysis and Candidate Evaluation | Analyzes CVs and evaluates job candidates automatically using AI. | HR/AI | [Link to Template](OpenAI_and_LLMs/AI%20Automated%20HR%20Workflow%20for%20CV%20Analysis%20and%20Candidate%20Evaluation.json) |
| AI Blog Writer Pipeline with Ollama | Uses Ollama local AI to research topics, create outlines, draft full blog posts, and edit them. Runs entirely locally with no API keys needed. | Content Creation/AI | [Link to Template](OpenAI_and_LLMs/AI%20Blog%20Writer%20Pipeline%20with%20Ollama.json) |
| AI Crew to Automate Fundamental Stock Analysis - Q&A Workflow | Stock analysis automation. | Finance/AI/Data Analysis | [Link to Template](OpenAI_and_LLMs/AI%20Crew%20to%20Automate%20Fundamental%20Stock%20Analysis%20-%20Q&A%20Workflow.json) |
| AI Customer feedback sentiment analysis | Sentiment analysis on customer feedback. | Customer Service/Marketing/Data Analysis | [Link to Template](OpenAI_and_LLMs/AI%20Customer%20feedback%20sentiment%20analysis.json) |
| AI Data Extraction with Dynamic Prompts and Airtable | AI-driven data extraction with Airtable integration. | AI/Data Extraction/Database | [Link to Template](OpenAI_and_LLMs/AI%20Data%20Extraction%20with%20Dynamic%20Prompts%20and%20Airtable.json) |
| AI Data Extraction with Dynamic Prompts and Baserow | AI-driven data extraction with Baserow integration. | AI/Data Extraction/Database | [Link to Template](OpenAI_and_LLMs/AI%20Data%20Extraction%20with%20Dynamic%20Prompts%20and%20Baserow.json) |
| AI Fitness Coach Strava Data Analysis and Personalized Training Insights | Fitness coaching via Strava data analysis. | Fitness/AI/Data Analysis | [Link to Template](OpenAI_and_LLMs/AI%20Fitness%20Coach%20Strava%20Data%20Analysis%20and%20Personalized%20Training%20Insights.json) |
| AI-Powered Web Scraping with Jina, Google Sheets and OpenAI: The Easy Way | Scrapes the web using Jina and OpenAI, then stores the extracted data in Google Sheets. | AI/Data Extraction | [Link to Template](OpenAI_and_LLMs/AI%20Powered%20Web%20Scraping%20with%20Jina,%20Google%20Sheets%20and%20OpenAI%20_%20the%20EASY%20way.json) |
| AI Social Media Caption Creator | Creates social media post captions with AI and saves them in Airtable. | Social Media/Content Creation | [Link to Template](OpenAI_and_LLMs/AI%20Social%20Media%20Caption%20Creator%20creates%20social%20media%20post%20captions%20in%20Airtable.json) |
| AI Voice Chat Using Webhook, Memory Manager, OpenAI, Google Gemini & ElevenLabs | Runs a voice chat assistant combining a webhook, memory manager, OpenAI, Google Gemini and ElevenLabs. | AI/Media | [Link to Template](OpenAI_and_LLMs/AI%20Voice%20Chat%20using%20Webhook,%20Memory%20Manager,%20OpenAI,%20Google%20Gemini%20&%20ElevenLabs.json) |
| AI Voice Chatbot with ElevenLabs & OpenAI for Customer Service and Restaurants | Handles customer service and restaurant inquiries through an AI voice chatbot built on ElevenLabs and OpenAI. | Customer Service/AI | [Link to Template](OpenAI_and_LLMs/AI%20Voice%20Chatbot%20with%20ElevenLabs%20&%20OpenAI%20for%20Customer%20Service%20and%20Restaurants.json) |
| AI YouTube Trend Finder Based on Niche | Finds trending YouTube topics for a given niche using AI. | Marketing/Social Media | [Link to Template](OpenAI_and_LLMs/AI%20Youtube%20Trend%20Finder%20Based%20On%20Niche.json) |
| AI agent chat | Basic AI chat agent. | AI/Customer Service | [Link to Template](OpenAI_and_LLMs/AI%20agent%20chat.json) |
| AI agent that can scrape webpages | AI agent for web scraping. | AI/Data Extraction | [Link to Template](OpenAI_and_LLMs/AI%20agent%20that%20can%20scrape%20webpages.json) |
| AI Chat With Any Data Source (Using the n8n Workflow Tool) | Chats with any data source using the n8n workflow tool as an AI agent tool. | AI/Data Analysis | [Link to Template](OpenAI_and_LLMs/AI%20chat%20with%20any%20data%20source%20(using%20the%20n8n%20workflow%20tool).json) |
| AI Chatbot That Can Search the Web | Answers questions through an AI chatbot that can search the web for current information. | AI/Productivity | [Link to Template](OpenAI_and_LLMs/AI%20chatbot%20that%20can%20search%20the%20web.json) |
| AI Web Researcher for Sales | Researches prospects and companies on the web using AI to support sales efforts. | Sales/AI | [Link to Template](OpenAI_and_LLMs/AI%20web%20researcher%20for%20sales.json) |
| AI-Driven Lead Management and Inquiry Automation with ERPNext & n8n | Lead management automation. | Sales/CRM/AI | [Link to Template](OpenAI_and_LLMs/AI-Driven%20Lead%20Management%20and%20Inquiry%20Automation%20with%20ERPNext%20&%20n8n.json) |
| AI-Generated Summary Block for WordPress Posts | Generates an AI summary block and adds it to WordPress posts. | Content Creation/AI | [Link to Template](OpenAI_and_LLMs/AI-Generated%20Summary%20Block%20for%20WordPress%20Posts.json) |
| AI-Powered Candidate Shortlisting Automation for ERPNext | Candidate shortlisting automation. | HR/AI/Recruitment | [Link to Template](OpenAI_and_LLMs/AI-Powered%20Candidate%20Shortlisting%20Automation%20for%20ERPNext.json) |
| AI-Powered Email Automation for Business: Summarize & Respond with RAG | Email automation with summarization and response. | Business Automation/AI/Communication | [Link to Template](OpenAI_and_LLMs/AI-Powered%20Email%20Automation%20for%20Business_%20Summarize%20&%20Respond%20with%20RAG.json) |
| AI-Powered RAG Workflow For Stock Earnings Report Analysis | Stock earnings report analysis with RAG. | Finance/AI/Data Analysis | [Link to Template](OpenAI_and_LLMs/AI-Powered%20RAG%20Workflow%20For%20Stock%20Earnings%20Report%20Analysis.json) |
| AI-Powered Social Media Amplifier | Amplifies social media presence using AI. | Marketing/AI/Social Media | [Link to Template](OpenAI_and_LLMs/AI-Powered%20Social%20Media%20Amplifier.json) |
| AI-powered WooCommerce Support-Agent | Creates an AI-powered support agent for WooCommerce stores. | E-commerce/AI/Customer Service | [Link to Template](OpenAI_and_LLMs/AI-powered%20WooCommerce%20Support-Agent.json) |
| AI: Ask questions about any data source (using the n8n workflow retriever) | Allows users to ask questions about various data sources using an n8n workflow retriever. | AI/Data Analysis/Workflow Automation | [Link to Template](OpenAI_and_LLMs/AI_%20Ask%20questions%20about%20any%20data%20source%20(using%20the%20n8n%20workflow%20retriever).json) |
| AI: Summarize podcast episode and enhance using Wikipedia | Summarizes podcast episodes and enhances the summary with information from Wikipedia using AI. | Content Creation/AI/Data Analysis | [Link to Template](OpenAI_and_LLMs/AI_%20Summarize%20podcast%20episode%20and%20enhance%20using%20Wikipedia.json) |
| Actioning Your Meeting Next Steps Using Transcripts and AI | Extracts action items and next steps from meeting transcripts using AI. | Productivity/AI | [Link to Template](OpenAI_and_LLMs/Actioning%20Your%20Meeting%20Next%20Steps%20using%20Transcripts%20and%20AI.json) |
| Advanced AI Demo (Presented at AI Developers #14 meetup) | Advanced AI capabilities demo. | AI/Development | [Link to Template](OpenAI_and_LLMs/Advanced%20AI%20Demo%20(Presented%20at%20AI%20Developers%20%2314%20meetup).json) |
| Ask a Human for Help When the AI Doesn't Know the Answer | Escalates to a human for help when the AI cannot answer a question. | AI/Customer Support | [Link to Template](OpenAI_and_LLMs/Ask%20a%20human%20for%20help%20when%20the%20AI%20doesn_t%20know%20the%20answer.json) |
| Automate Customer Support Issue Resolution Using AI Text Classifier | Automates customer support issue resolution by classifying incoming requests with an AI text classifier. | Customer Support/AI | [Link to Template](OpenAI_and_LLMs/Automate%20Customer%20Support%20Issue%20Resolution%20using%20AI%20Text%20Classifier.json) |
| Automate Image Validation Tasks Using AI Vision | Automates image validation tasks using AI vision to inspect and verify images. | AI/Automation | [Link to Template](OpenAI_and_LLMs/Automate%20Image%20Validation%20Tasks%20using%20AI%20Vision.json) |
| Automate Your RFP Process with OpenAI Assistants | Automates the RFP response process using OpenAI Assistants. | Sales/AI | [Link to Template](OpenAI_and_LLMs/Automate%20Your%20RFP%20Process%20with%20OpenAI%20Assistants.json) |
| Chat Assistant (OpenAI Assistant) with Postgres Memory and API Calling Capabilities | Runs an OpenAI assistant chat with Postgres-backed memory and the ability to call external APIs. | AI/Development | [Link to Template](OpenAI_and_LLMs/Chat%20Assistant%20(OpenAI%20assistant)%20with%20Postgres%20Memory%20And%20API%20Calling%20Capabalities.json) |
| Chat with OpenAI Assistant (by Adding a Memory) | Chats with an OpenAI Assistant enhanced with persistent memory. | AI/Productivity | [Link to Template](OpenAI_and_LLMs/Chat%20with%20OpenAI%20Assistant%20(by%20adding%20a%20memory).json) |
| Chat with Local LLMs Using n8n and Ollama | Chats with locally hosted LLMs using n8n and Ollama. | AI/Development | [Link to Template](OpenAI_and_LLMs/Chat%20with%20local%20LLMs%20using%20n8n%20and%20Ollama.json) |
| Claude AI Content Generator | HTTP POST with a topic and content type triggers Claude to write a full blog post, newsletter, or social media content draft. Returns content via API and notifies via Slack. | Content Creation/AI/Marketing | [Link to Template](OpenAI_and_LLMs/Claude%20AI%20Content%20Generator.json) |
| Claude AI LINE Chatbot | Connects LINE messaging to Anthropic Claude AI. Receives LINE webhook, generates contextual reply with Claude, and sends response back to LINE user. | AI/Customer Service | [Link to Template](OpenAI_and_LLMs/Claude%20AI%20LINE%20Chatbot.json) |
| Claude AI Morning Brief | Runs daily at 8:00 AM, compiles a personalized briefing with Claude AI, and delivers it via LINE or email. | Productivity/AI/Automation | [Link to Template](OpenAI_and_LLMs/Claude%20AI%20Morning%20Brief.json) |
| Claude Smart Webhook AI Router | Routes incoming webhook requests by Anthropic Claude AI classification. Claude analyzes each payload and routes to support, technical, sales, or general handler. | AI/DevOps/Automation | [Link to Template](OpenAI_and_LLMs/Claude%20Smart%20Webhook%20AI%20Router.json) |
| Configure Your Own Image Creation API Using OpenAI DALL-E 3 | Exposes a custom image creation API powered by OpenAI DALL-E 3. | AI/Content Creation | [Link to Template](OpenAI_and_LLMs/Configure%20your%20own%20Image%20Creation%20API%20Using%20OpenAI%20DALLE-3.json) |
| Convert Text to Speech with OpenAI | Converts text into spoken audio using OpenAI. | AI/Media | [Link to Template](OpenAI_and_LLMs/Convert%20text%20to%20speech%20with%20OpenAI.json) |
| Create a Branded AI-Powered Website Chatbot | Builds a branded AI-powered chatbot for a website. | Customer Support/AI | [Link to Template](OpenAI_and_LLMs/Create%20a%20Branded%20AI-Powered%20Website%20Chatbot.json) |
| Custom LangChain Agent Written in JavaScript | Implements a custom LangChain agent written in JavaScript. | Development/AI | [Link to Template](OpenAI_and_LLMs/Custom%20LangChain%20agent%20written%20in%20JavaScript.json) |
| Daily Podcast Summary | Generates a daily summary of podcast episodes. | Media/AI | [Link to Template](OpenAI_and_LLMs/Daily%20Podcast%20Summary.json) |
| Daily Meetings Summarization with Gemini AI | Summarizes daily meetings using Gemini AI. | Productivity/AI | [Link to Template](OpenAI_and_LLMs/Daily%20meetings%20summarization%20with%20Gemini%20AI.json) |
| Detect Hallucinations Using Specialised Ollama Model bespoke-minicheck | Detects AI hallucinations using the specialised Ollama model bespoke-minicheck. | AI/Development | [Link to Template](OpenAI_and_LLMs/Detect%20hallucinations%20using%20specialised%20Ollama%20model%20bespoke-minicheck.json) |
| Dynamically Generate a Webpage from User Request Using OpenAI Structured Output | Generates a webpage dynamically from a user request using OpenAI structured output. | Development/AI | [Link to Template](OpenAI_and_LLMs/Dynamically%20generate%20a%20webpage%20from%20user%20request%20using%20OpenAI%20Structured%20Output.json) |
| Easy Image Captioning with Gemini 1.5 Pro | Generates captions for images using Gemini 1.5 Pro. | AI/Content Creation | [Link to Template](OpenAI_and_LLMs/Easy%20Image%20Captioning%20with%20Gemini%201.5%20Pro.json) |
| Enrich FAQ Sections on Your Website Pages at Scale with AI | Enriches FAQ sections across website pages at scale using AI. | Content Creation/AI | [Link to Template](OpenAI_and_LLMs/Enrich%20FAQ%20sections%20on%20your%20website%20pages%20at%20scale%20with%20AI.json) |
| Extract Personal Data with Self-Hosted LLM Mistral NeMo | Extracts personal data from text using the self-hosted LLM Mistral NeMo. | Data Extraction/AI | [Link to Template](OpenAI_and_LLMs/Extract%20personal%20data%20with%20self-hosted%20LLM%20Mistral%20NeMo.json) |
| Fetch Dynamic Prompts from GitHub and Auto-Populate n8n Expressions in Prompt | Fetches dynamic prompts from GitHub and auto-populates n8n expressions within them. | Development/Automation | [Link to Template](OpenAI_and_LLMs/Fetch%20Dynamic%20Prompts%20from%20GitHub%20and%20Auto-Populate%20n8n%20Expressions%20in%20Prompt.json) |
| Flux AI Image Generator | Generates images using the Flux AI model. | AI/Content Creation | [Link to Template](OpenAI_and_LLMs/Flux%20AI%20Image%20Generator.json) |
| Force AI to Use a Specific Output Format | Forces an AI model to return responses in a specific structured output format. | AI/Development | [Link to Template](OpenAI_and_LLMs/Force%20AI%20to%20use%20a%20specific%20output%20format.json) |
| GCF Token Optimization for LLM Tool Responses | Fetches GitHub contributors, batches into an array, encodes to GCF (Graph Compact Format) for 53-71% fewer tokens, then decodes back to JSON losslessly. Uses the n8n-nodes-gcf community node. | AI/DevOps/Optimization | [Link to Template](OpenAI_and_LLMs/GCF%20Token%20Optimization%20for%20LLM%20Tool%20Responses.json) |
| Generate 9:16 Images from Content and Brand Guidelines | Generates 9:16 images from content and brand guidelines. | Content Creation/Marketing | [Link to Template](OpenAI_and_LLMs/Generate%209_16%20Images%20from%20Content%20and%20Brand%20Guidelines.json) |
| Generate Text-to-Speech Using ElevenLabs via API | Generates text-to-speech audio using the ElevenLabs API. | AI/Media | [Link to Template](OpenAI_and_LLMs/Generate%20Text-to-Speech%20Using%20Elevenlabs%20via%20API.json) |
| Generate Audio from Text Using OpenAI and Webhook: Text to Speech Workflow | Generates audio from text using OpenAI, triggered through a webhook. | AI/Media | [Link to Template](OpenAI_and_LLMs/Generate%20audio%20from%20text%20using%20OpenAI%20and%20Webhook%20_%20Text%20to%20Speech%20Workflow.json) |
| Generating Image Embeddings via Textual Summarisation | Generates image embeddings by first producing textual summaries of the images. | AI/Data Analysis | [Link to Template](OpenAI_and_LLMs/Generating%20Image%20Embeddings%20via%20Textual%20Summarisation.json) |
| Narrating Over a Video Using Multimodal AI | Generates narration over a video using multimodal AI. | Media/AI | [Link to Template](OpenAI_and_LLMs/Narrating%20over%20a%20Video%20using%20Multimodal%20AI.json) |
| n8n + Local LLM (Ollama) Basic Setup | Connect n8n with local LLMs (Llama 3, Mistral, Phi-3) for 100% free AI automation. No API keys required. | AI/Automation | [Link to Template](OpenAI_and_LLMs/Ollama_Basic_Workflow.json) |
| OpenAI Assistant Workflow: Upload File, Create an Assistant, Chat with It! | Uploads a file, creates an OpenAI Assistant, and lets you chat with it. | AI/Development | [Link to Template](OpenAI_and_LLMs/OpenAI%20Assistant%20workflow_%20upload%20file,%20create%20an%20Assistant,%20chat%20with%20it%21.json) |
| OpenAI Assistant with Custom Tools | Runs an OpenAI Assistant equipped with custom tools. | AI/Development | [Link to Template](OpenAI_and_LLMs/OpenAI%20assistant%20with%20custom%20tools.json) |
| OpenAI Examples: ChatGPT, DALL-E 2, Whisper-1 – 5-in-1 | Demonstrates five OpenAI capabilities including ChatGPT, DALL-E 2, and Whisper-1 in one workflow. | AI/Development | [Link to Template](OpenAI_and_LLMs/OpenAI%20examples_%20ChatGPT,%20DALLE-2,%20Whisper-1%20%E2%80%93%205-in-1.json) |
| Organise Your Local File Directories with AI | Organises local file directories automatically using AI. | Productivity/Automation | [Link to Template](OpenAI_and_LLMs/Organise%20Your%20Local%20File%20Directories%20With%20AI.json) |
| Personal Shopper Chatbot for WooCommerce with RAG Using Google Drive and OpenAI | Acts as a personal shopper chatbot for WooCommerce using RAG over Google Drive and OpenAI. | E-commerce/AI | [Link to Template](OpenAI_and_LLMs/Personal%20Shopper%20Chatbot%20for%20WooCommerce%20with%20RAG%20using%20Google%20Drive%20and%20openAI.json) |
| Prompt-Based Object Detection with Gemini 2.0 | Detects objects in images from text prompts using Gemini 2.0. | AI/Data Extraction | [Link to Template](OpenAI_and_LLMs/Prompt-based%20Object%20Detection%20with%20Gemini%202.0.json) |
| Proxmox AI Agent with n8n and Generative AI Integration | Manages Proxmox infrastructure through an n8n AI agent with generative AI integration. | DevOps/AI | [Link to Template](OpenAI_and_LLMs/Proxmox%20AI%20Agent%20with%20n8n%20and%20Generative%20AI%20Integration.json) |
| Query n8n Credentials with AI SQL Agent | Queries n8n credentials using an AI SQL agent. | AI/Database | [Link to Template](OpenAI_and_LLMs/Query%20n8n%20Credentials%20with%20AI%20SQL%20Agent.json) |
| Suggest Meeting Slots Using AI | Suggests available meeting slots using AI. | Productivity/AI | [Link to Template](OpenAI_and_LLMs/Suggest%20meeting%20slots%20using%20AI.json) |
| Summarize YouTube Videos from Transcript | Summarizes YouTube videos using their transcripts. | AI/Media | [Link to Template](OpenAI_and_LLMs/Summarize%20YouTube%20Videos%20from%20Transcript.json) |
| SupportFlow Lite - Simple AI Customer Support Chatbot | A lightweight AI chatbot that answers customer questions using company info and OpenAI gpt-4o-mini. Easy single-workflow setup with Google Sheets knowledge base. | Customer Support/AI | [Link to Template](OpenAI_and_LLMs/SupportFlow%20Lite%20-%20Simple%20AI%20Customer%20Support%20Chatbot.json) |
| Transform Image to Lego Style Using Line and DALL-E | Transforms an image into Lego style using Line and DALL-E. | AI/Content Creation | [Link to Template](OpenAI_and_LLMs/Transform%20Image%20to%20Lego%20Style%20Using%20Line%20and%20Dall-E.json) |
| Translate Audio Using AI | Translates spoken audio into another language using AI. | AI/Media | [Link to Template](OpenAI_and_LLMs/Translate%20audio%20using%20AI.json) |
| Use OpenRouter in n8n Versions <1.78 | Enables using OpenRouter in n8n versions below 1.78. | Development/AI | [Link to Template](OpenAI_and_LLMs/Use%20OpenRouter%20in%20n8n%20versions%20_1.78.json) |
| lemlist & GPT-3: Supercharge Your Sales Workflows | Supercharges sales workflows by combining lemlist with GPT-3. | Sales/AI | [Link to Template](OpenAI_and_LLMs/lemlist%20__%20GPT-3_%20Supercharge%20your%20sales%20workflows.json) |
| AI-Powered YouTube Video Summarization & Analysis | Summarizes and analyzes YouTube videos using AI. | Content Creation/AI/Data Analysis | [Link to Template](OpenAI_and_LLMs/%E2%9A%A1AI-Powered%20YouTube%20Video%20Summarization%20&%20Analysis.json) |
| 🎨 Interactive Image Editor with FLUX.1 Fill Tool for Inpainting | Edits images interactively using the FLUX.1 Fill tool for inpainting. | AI/Content Creation | [Link to Template](OpenAI_and_LLMs/%F0%9F%8E%A8%20Interactive%20Image%20Editor%20with%20FLUX.1%20Fill%20Tool%20for%20Inpainting.json) |
| 🐋 DeepSeek V3 Chat & R1 Reasoning Quick Start | Provides a quick-start setup for chatting with DeepSeek V3 and R1 reasoning models. | AI/Development | [Link to Template](OpenAI_and_LLMs/%F0%9F%90%8BDeepSeek%20V3%20Chat%20&%20R1%20Reasoning%20Quick%20Start.json) |
| 📚 Auto-Generate Documentation for n8n Workflows with GPT and Docsify | Auto-generates documentation for n8n workflows using GPT and Docsify. | Development/AI | [Link to Template](OpenAI_and_LLMs/%F0%9F%93%9A%20Auto-generate%20documentation%20for%20n8n%20workflows%20with%20GPT%20and%20Docsify.json) |
| 🔐🦙🤖 Private & Local Ollama Self-Hosted AI Assistant | Runs a private, self-hosted AI assistant locally using Ollama. | AI/Development | [Link to Template](OpenAI_and_LLMs/%F0%9F%94%90%F0%9F%A6%99%F0%9F%A4%96%20Private%20&%20Local%20Ollama%20Self-Hosted%20AI%20Assistant.json) |
| 🔥📈🤖 AI Agent for n8n Creators Leaderboard - Find Popular Workflows | Finds popular n8n workflows by querying the n8n creators leaderboard with an AI agent. | AI/Data Analysis | [Link to Template](OpenAI_and_LLMs/%F0%9F%94%A5%F0%9F%93%88%F0%9F%A4%96%20AI%20Agent%20for%20n8n%20Creators%20Leaderboard%20-%20Find%20Popular%20Workflows.json) |
| 🚀 Local Multi-LLM Testing & Performance Tracker | Tests multiple local LLMs and tracks their performance. | AI/Development | [Link to Template](OpenAI_and_LLMs/%F0%9F%9A%80%20Local%20Multi-LLM%20Testing%20&%20Performance%20Tracker.json) |
| 🤖🧑‍💻 AI Agent for Top n8n Creators Leaderboard Reporting | Reports on the top n8n creators leaderboard using an AI agent. | AI/Data Analysis | [Link to Template](OpenAI_and_LLMs/%F0%9F%A4%96%F0%9F%A7%91_%F0%9F%92%BB%20AI%20Agent%20for%20Top%20n8n%20Creators%20Leaderboard%20Reporting.json) |

<div align="right"><a href="#-n8n-ai-workflow-automation">⬆ Back to top</a></div>

---

## 🔬 AI Research, RAG & Data Analysis (43 workflows)

Retrieval-augmented generation, vector databases, autonomous research and scraping agents, document assistants, and AI-driven analytics. Built with Qdrant, Pinecone, Elasticsearch, and models from OpenAI, Mistral, Gemini, DeepSeek, and Perplexity.

| Title | Description | Department | Link |
|---|---|---|---|
| Analyze tradingview.com charts with Chrome extension, N8N and OpenAI | Analyzes TradingView charts using a Chrome extension, n8n, and OpenAI for automated insights. | Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Analyze%20tradingview.com%20charts%20with%20Chrome%20extension,%20N8N%20and%20OpenAI.json) |
| Automated Hugging Face Paper Summary Fetching & Categorization Workflow | Automates fetching, summarizing, and categorizing research papers from Hugging Face. | AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Automated%20Hugging%20Face%20Paper%20Summary%20Fetching%20&%20Categorization%20Workflow.json) |
| Autonomous AI crawler | An autonomous AI-powered web crawler for data collection and analysis. | AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Autonomous%20AI%20crawler.json) |
| Bilig WorkPaper MCP formula engine for n8n agents | Calls Bilig's public MCP endpoint from n8n to write a spreadsheet formula, calculate the result, and verify restored readback without Excel UI automation. | Engineering, AI Automation | [Link to Template](AI_Research_RAG_and_Data_Analysis/Bilig%20WorkPaper%20MCP%20formula%20engine%20for%20n8n%20agents.json) |
| Build Your Own Image Search Using AI Object Detection, CDN and ElasticSearch | Builds an image search engine using AI object detection, CDN, and Elasticsearch for efficient image retrieval. | AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Build%20Your%20Own%20Image%20Search%20Using%20AI%20Object%20Detection,%20CDN%20and%20ElasticSearch.json) |
| Build a Financial Documents Assistant using Qdrant and Mistral.ai | Creates an AI assistant for financial document analysis using Qdrant for vector search and Mistral.ai for language processing. | Finance, AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Build%20a%20Financial%20Documents%20Assistant%20using%20Qdrant%20and%20Mistral.ai.json) |
| Build a Tax Code Assistant with Qdrant, Mistral.ai and OpenAI | Develops an AI assistant for tax code queries using Qdrant, Mistral.ai, and OpenAI for comprehensive responses. | Finance, AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Build%20a%20Tax%20Code%20Assistant%20with%20Qdrant,%20Mistral.ai%20and%20OpenAI.json) |
| Building RAG Chatbot for Movie Recommendations with Qdrant and Open AI | Constructs a RAG-based chatbot for movie recommendations, leveraging Qdrant for retrieval and OpenAI for generation. | AI Research, Entertainment | [Link to Template](AI_Research_RAG_and_Data_Analysis/Building%20RAG%20Chatbot%20for%20Movie%20Recommendations%20with%20Qdrant%20and%20Open%20AI.json) |
| Chat with GitHub API Documentation: RAG-Powered Chatbot with Pinecone & OpenAI | Implements a RAG-powered chatbot for interacting with GitHub API documentation using Pinecone and OpenAI. | Development, AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Chat%20with%20GitHub%20API%20Documentation_%20RAG-Powered%20Chatbot%20with%20Pinecone%20&%20OpenAI.json) |
| Create a Google Analytics Data Report with AI and sent it to E-Mail and Telegram | Generates Google Analytics data reports using AI and sends them via email and Telegram. | Data Analysis, Marketing | [Link to Template](AI_Research_RAG_and_Data_Analysis/Create%20a%20Google%20Analytics%20Data%20Report%20with%20AI%20and%20sent%20it%20to%20E-Mail%20and%20Telegram.json) |
| Customer Insights with Qdrant, Python and Information Extractor | Extracts customer insights using Qdrant, Python, and an information extraction module. | Data Analysis, Customer Service | [Link to Template](AI_Research_RAG_and_Data_Analysis/Customer%20Insights%20with%20Qdrant,%20Python%20and%20Information%20Extractor.json) |
| DataForge Lite - AI URL Data Extractor | POST any URL and extract structured data using OpenAI. Returns clean JSON output for easy integration with other workflows. | Data Extraction, AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/DataForge%20Lite%20-%20AI%20URL%20Data%20Extractor.json) |
| Deduplicate Scraping AI Grants for Eligibility using AI | Automates the deduplication and eligibility assessment of scraped AI grant data using AI. | AI Research, Data Management | [Link to Template](AI_Research_RAG_and_Data_Analysis/Deduplicate%20Scraping%20AI%20Grants%20for%20Eligibility%20using%20AI.json) |
| Enrich Property Inventory Survey with Image Recognition and AI Agent | Enhances property inventory surveys with image recognition and AI agents for automated data enrichment. | Real Estate, AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Enrich%20Property%20Inventory%20Survey%20with%20Image%20Recognition%20and%20AI%20Agent.json) |
| Extract insights & analyse YouTube comments via AI Agent chat | Extracts insights and analyzes YouTube comments through an AI agent chat interface. | Social Media, Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Extract%20insights%20&%20analyse%20YouTube%20comments%20via%20AI%20Agent%20chat.json) |
| Generate SEO Seed Keywords Using AI | Generates SEO seed keywords using AI to optimize content for search engines. | Marketing, AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Generate%20SEO%20Seed%20Keywords%20Using%20AI.json) |
| Hacker News Job Listing Scraper and Parser | Scrapes and parses job listings from Hacker News for job seekers or recruiters. | Data Collection, HR | [Link to Template](AI_Research_RAG_and_Data_Analysis/Hacker%20News%20Job%20Listing%20Scraper%20and%20Parser.json) |
| Hacker News to Video Content | Converts Hacker News articles into video content automatically. | Content Creation, Media | [Link to Template](AI_Research_RAG_and_Data_Analysis/Hacker%20News%20to%20Video%20Content.json) |
| Host Your Own AI Deep Research Agent with n8n, Apify and OpenAI o3 | Sets up a self-hosted AI deep research agent using n8n, Apify, and OpenAI. | AI Research, Automation | [Link to Template](AI_Research_RAG_and_Data_Analysis/Host%20Your%20Own%20AI%20Deep%20Research%20Agent%20with%20n8n,%20Apify%20and%20OpenAI%20o3.json) |
| Intelligent Web Query and Semantic Re-Ranking Flow using Brave and Google Gemini | Performs intelligent web queries and semantic re-ranking using Brave browser and Google Gemini AI. | AI Research, Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Intelligent%20Web%20Query%20and%20Semantic%20Re-Ranking%20Flow%20using%20Brave%20and%20Google%20Gemini.json) |
| Learn Anything from HN - Get Top Resource Recommendations from Hacker News | Extracts top resource recommendations from Hacker News to facilitate learning on any topic. | Education, Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Learn%20Anything%20from%20HN%20-%20Get%20Top%20Resource%20Recommendations%20from%20Hacker%20News.json) |
| Live Web Research Agent with Superhighway | Search the live web, get AI-ready results (title, URL, snippet) using Superhighway's free search API. No browser required — pure HTTP. | Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Live%20Web%20Research%20Agent%20with%20Superhighway.json) |
| Make OpenAI Citation for File Retrieval RAG | Generates citations for file retrieval in RAG systems using OpenAI. | AI Research, Documentation | [Link to Template](AI_Research_RAG_and_Data_Analysis/Make%20OpenAI%20Citation%20for%20File%20Retrieval%20RAG.json) |
| Open Deep Research - AI-Powered Autonomous Research Workflow | An AI-powered autonomous workflow for conducting deep research. | AI Research, Automation | [Link to Template](AI_Research_RAG_and_Data_Analysis/Open%20Deep%20Research%20-%20AI-Powered%20Autonomous%20Research%20Workflow.json) |
| Query Perplexity AI from your n8n workflows | Integrates Perplexity AI into n8n workflows for advanced querying capabilities. | AI Research, Automation | [Link to Template](AI_Research_RAG_and_Data_Analysis/Query%20Perplexity%20AI%20from%20your%20n8n%20workflows.json) |
| Recipe Recommendations with Qdrant and Mistral | Provides recipe recommendations using Qdrant for vector search and Mistral AI for content generation. | Food, AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Recipe%20Recommendations%20with%20Qdrant%20and%20Mistral.json) |
| Reconcile Rent Payments with Local Excel Spreadsheet and OpenAI | Reconciles rent payments by comparing local Excel spreadsheets with data processed by OpenAI. | Finance, Data Management | [Link to Template](AI_Research_RAG_and_Data_Analysis/Reconcile%20Rent%20Payments%20with%20Local%20Excel%20Spreadsheet%20and%20OpenAI.json) |
| Scrape Trustpilot Reviews with DeepSeek, Analyze Sentiment with OpenAI | Scrapes Trustpilot Reviews using DeepSeek and analyzes sentiment with OpenAI. | Marketing, Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Scrape%20Trustpilot%20Reviews%20with%20DeepSeek,%20Analyze%20Sentiment%20with%20OpenAI.json) |
| Scrape and summarize posts of a news site without RSS feed using AI and save them to a NocoDB | Scrapes and summarizes news posts without RSS feeds using AI, saving the output to NocoDB. | Content Curation, Data Management | [Link to Template](AI_Research_RAG_and_Data_Analysis/Scrape%20and%20summarize%20posts%20of%20a%20news%20site%20without%20RSS%20feed%20using%20AI%20and%20save%20them%20to%20a%20NocoDB.json) |
| Scrape and summarize webpages with AI | Scrapes and summarizes content from webpages using AI. | Content Curation, Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Scrape%20and%20summarize%20webpages%20with%20AI.json) |
| Send Google analytics data to A.I. to analyze then save results in Baserow | Sends Google Analytics data to AI for analysis and saves the results in Baserow. | Data Analysis, Marketing | [Link to Template](AI_Research_RAG_and_Data_Analysis/Send%20Google%20analytics%20data%20to%20A.I.%20to%20analyze%20then%20save%20results%20in%20Baserow.json) |
| SocialPulse Lite - Reddit Trend Monitor | Monitors Reddit subreddits for trending topics and analyzes them with OpenAI. Saves insights to Google Sheets for tracking emerging trends. | Data Analysis, Marketing | [Link to Template](AI_Research_RAG_and_Data_Analysis/SocialPulse%20Lite%20-%20Reddit%20Trend%20Monitor.json) |
| Spot Workplace Discrimination Patterns with AI | Identifies patterns of workplace discrimination using AI-driven analysis. | HR, AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Spot%20Workplace%20Discrimination%20Patterns%20with%20AI.json) |
| Summarize SERPBear data with AI (via Openrouter) and save it to Baserow | Summarizes SERPBear data using AI (via Openrouter) and saves the insights to Baserow. | SEO, Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Summarize%20SERPBear%20data%20with%20AI%20(via%20Openrouter)%20and%20save%20it%20to%20Baserow.json) |
| Summarize Umami data with AI (via Openrouter) and save it to Baserow | Summarizes Umami analytics data using AI (via Openrouter) and saves the insights to Baserow. | Data Analysis, Marketing | [Link to Template](AI_Research_RAG_and_Data_Analysis/Summarize%20Umami%20data%20with%20AI%20(via%20Openrouter)%20and%20save%20it%20to%20Baserow.json) |
| Survey Insights with Qdrant, Python and Information Extractor | Extracts and analyzes insights from survey data using Qdrant, Python, and an information extractor. | Data Analysis, Market Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Survey%20Insights%20with%20Qdrant,%20Python%20and%20Information%20Extractor.json) |
| Ultimate Scraper Workflow for n8n | A comprehensive scraping workflow for n8n to extract data from various sources. | Data Collection, Automation | [Link to Template](AI_Research_RAG_and_Data_Analysis/Ultimate%20Scraper%20Workflow%20for%20n8n.json) |
| Vector Database as a Big Data Analysis Tool for AI Agents [1/3 anomaly][1/2 KNN] | Utilizes a vector database for big data analysis, focusing on anomaly detection and KNN classification for AI agents. | AI Research, Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Vector%20Database%20as%20a%20Big%20Data%20Analysis%20Tool%20for%20AI%20Agents%20[1_3%20anomaly][1_2%20KNN].json) |
| Vector Database as a Big Data Analysis Tool for AI Agents [2/2 KNN] | Continues the use of a vector database for big data analysis, focusing on KNN classification for AI agents. | AI Research, Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Vector%20Database%20as%20a%20Big%20Data%20Analysis%20Tool%20for%20AI%20Agents%20[2_2%20KNN].json) |
| Vector Database as a Big Data Analysis Tool for AI Agents [2/3 - anomaly] | Explores the use of a vector database for big data analysis, focusing on anomaly detection for AI agents. | AI Research, Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Vector%20Database%20as%20a%20Big%20Data%20Analysis%20Tool%20for%20AI%20Agents%20[2_3%20-%20anomaly].json) |
| Vector Database as a Big Data Analysis Tool for AI Agents [3/3 - anomaly] | Concludes the use of a vector database for big data analysis, focusing on anomaly detection for AI agents. | AI Research, Data Analysis | [Link to Template](AI_Research_RAG_and_Data_Analysis/Vector%20Database%20as%20a%20Big%20Data%20Analysis%20Tool%20for%20AI%20Agents%20[3_3%20-%20anomaly].json) |
| Visual Regression Testing with Apify and AI Vision Model | Performs visual regression testing using Apify and an AI vision model to detect UI changes. | QA, AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/Visual%20Regression%20Testing%20with%20Apify%20and%20AI%20Vision%20Model.json) |
| 🔍 Perplexity Research to HTML: AI-Powered Content Creation | Transforms Perplexity AI research into HTML content for AI-powered content creation. | Content Creation, AI Research | [Link to Template](AI_Research_RAG_and_Data_Analysis/%F0%9F%94%8D%20Perplexity%20Research%20to%20HTML_%20AI-Powered%20Content%20Creation.json) |

<div align="right"><a href="#-n8n-ai-workflow-automation">⬆ Back to top</a></div>

---

## FAQ

### How do I import a workflow from this repository?

Download the `.json` file for the workflow you want, then in n8n go to **Workflows → Import from File** and select it. Add your credentials to each node and activate.

### Are these workflows free to use?

Yes. Every workflow is free to download, import, and adapt. n8n itself is open-source and free to self-host, and n8n Cloud has a free tier to get started.

### Which AI models and providers are supported?

The library spans OpenAI (GPT-4o, DALL·E, Whisper), Anthropic Claude, Google Gemini, DeepSeek, Mistral, Perplexity, ElevenLabs, and local models via Ollama. RAG workflows use vector stores like Qdrant, Pinecone, Elasticsearch, and Supabase.

### Do I need API keys?

Most workflows call a hosted model and need an API key for that provider. Several (Ollama-based) run entirely locally with no API keys at all — look for "Ollama" or "local LLM" in the title.

### Can I contribute my own workflow?

Absolutely — see [Contributing](#contributing). AI-focused workflows are welcome; off-topic integrations are intentionally out of scope to keep this library sharp.

---

## Contributing

Contributions are welcome. If you've built an AI workflow in n8n that others would find useful, open a pull request with the JSON file placed in the matching folder and a new row in the README table. See **[CONTRIBUTING.md](CONTRIBUTING.md)** for the full guidelines and scope.

---

## License & Disclaimer

Released under the [Creative Commons Attribution 4.0 International License](LICENSE) (CC-BY-4.0).

**Disclaimer:** These workflows were collected from publicly available community sources and are shared here for convenient access and learning. They are not all originally authored by the maintainer, and all rights to individual workflows remain with their respective creators. Use them at your own discretion — review each workflow and never commit credentials or API keys.

---

## Author

Built and maintained by **Tayyab Tahir** ([@Tayyab-Tahir1](https://github.com/Tayyab-Tahir1)).

If this library saves you time, consider giving it a ⭐ — it helps other builders find it.

<div align="center">

<a href="https://n8n.io"><img src="https://img.shields.io/badge/Build_with_n8n-Start_Free-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="Build with n8n" /></a>

</div>
