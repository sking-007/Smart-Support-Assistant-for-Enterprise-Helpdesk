# Smart-Support-Assistant-for-Enterprise-Helpdesk
An intelligent multi-agent system that automates internal IT or HR support using LLMs, document search, and enterprise APIs — built using Azure OpenAI, LangChain, and Flowise, deployed with scalable architecture and orchestration logic.

## Project Goals
- Automate employee support using generative AI.
- Use Retrieval-Augmented Generation (RAG) for domain-specific knowledge.
- Integrate internal APIs (HR, IT) and escalate as needed.
- Enable observability and responsible AI governance.

## Architecture & Workflow Design
- **Input Layer**: MS Teams / Web Chatbot
- **Classification**: GPT-4 Turbo for identifying domain
- **Retrieval**: Azure Cognitive Search for document context
- **Action Layer**: APIs, logic routing, and user-specific logic
- **Output**: Natural language response with option to escalate

## Tools Used
| Category        | Tool/Service                          |
|----------------|----------------------------------------|
| LLM             | Azure OpenAI (GPT-4 Turbo)            |
| Orchestration   | LangChain, Flowise                    |
| Storage         | Azure Blob, Azure Cognitive Search    |
| Automation      | n8n / Zapier / Power Automate         |
| Monitoring      | Azure Monitor, LangSmith              |
| APIs            | MS Graph, HR REST API, Trello         |
| UI              | Streamlit or React + MS Bot Framework |

## Key Features
- Multi-agent routing and classification
- Prompt chaining with memory
- Integration with HR APIs and MS Graph
- Monitoring with Azure Monitor and LangSmith
- Responsible AI with redaction and fallback

## Evaluation & Observability
- Token usage monitoring
- Resolution success rates
- Latency tracking
- PII redaction and audit logs

## Documentation & Enablement
- Flowcharts (draw.io)
- Prompt templates
- User + developer onboarding guides
- GitHub repo with README and notebooks

## Governance
- GDPR simulated flows
- Confidence disclaimers for sensitive data
- Audit trails of user interactions

## Deployment Options
- Dev: Docker + ngrok for local testing
- Prod: Azure App Service or Kubernetes Service (AKS)

## Output
- GitHub repo
- PDF documentation
- Streamlit dashboard screenshots
