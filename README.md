# Agentic AI Automation Workflows with n8n

Two practical Agentic AI workflows built using **n8n and OpenAI-powered AI Agents** to automate enterprise account research, ICP qualification, and technical content repurposing.

## Projects

### 1. Autonomous Enterprise ICP Qualifier & Research Agent

An autonomous AI workflow that researches a target company and evaluates its fit against an Enterprise Ideal Customer Profile (ICP).

#### Workflow

Company Domain  
↓  
Webhook Trigger  
↓  
Company Website Research  
↓  
About Page Research  
↓  
Serper API – Search & Recent News  
↓  
OpenAI-Powered ICP Agent  
↓  
Structured Output Parser  
↓  
Google Sheets

#### Key Capabilities

- Accepts a company domain through a webhook
- Researches the company's website and About page
- Searches for recent company news using Serper API
- Evaluates the company against an Enterprise ICP matrix
- Identifies business pain points
- Generates an outbound pitch angle
- Produces structured account intelligence
- Stores the final account dossier in Google Sheets

#### Sample Output

The workflow was tested on enterprise accounts including **Stripe and Microsoft**.

Generated account intelligence includes:

- ICP score
- ICP tier
- Employee count
- Business model
- Pain points
- Recent news
- Funding information
- Outbound pitch angle

---

### 2. Autonomous Technical Content Repurposer & Social Multi-Poster

An autonomous AI workflow that converts technical blog posts or whitepapers into structured social media content.

#### Workflow

Blog / Whitepaper URL  
↓  
Postman API Trigger  
↓  
Article Content Extraction  
↓  
OpenAI-Powered Content Repurposing Agent  
↓  
Structured Output Parser  
↓  
Google Sheets Content Calendar

#### Key Capabilities

- Accepts a technical content URL through a Postman API request
- Extracts the core insights from long-form technical content
- Generates LinkedIn carousel scripts
- Generates 5-post Twitter/X threads
- Uses structured output parsing for consistent formatting
- Stores generated content in Google Sheets
- Creates a repeatable multi-channel content workflow

#### Sample Output

The workflow was tested on **3 technical content sources** and generated:

- 3 LinkedIn carousel scripts
- 3 five-post Twitter/X threads
- 6 content deliverables in total

---

## Technology Stack

### AI & Automation
- n8n
- Agentic AI
- OpenAI
- Generative AI

### APIs & Integrations
- Serper API
- Postman API
- Webhooks
- Google Sheets

### Workflow Components
- AI Agents
- Structured Output Parser
- Webhook Triggers
- API Integrations
- Automated Data Processing

## What I Learned

Through these projects, I gained hands-on experience in:

- Designing Agentic AI workflows
- Connecting AI agents with external APIs
- Automating multi-step research processes
- Applying AI to enterprise account qualification
- Structuring LLM outputs for downstream applications
- Building automated content-generation pipelines
- Integrating AI workflows with Google Sheets
- Testing and iterating end-to-end automation workflows

## Project Purpose

These projects demonstrate practical applications of Agentic AI for:

- Enterprise prospect research
- ICP qualification
- Account intelligence
- Pain-point discovery
- Personalized outbound messaging
- Technical content repurposing
- Multi-channel content creation

## Screenshots

### Enterprise ICP Qualifier
Add workflow and sample-output screenshots here.

### Content Repurposer
Add workflow and sample-output screenshots here.

## Disclaimer

These projects are personal implementations created for learning and demonstration purposes. API credentials and other sensitive information are not included in this repository.
