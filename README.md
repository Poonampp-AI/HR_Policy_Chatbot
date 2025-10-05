# HR_Policy_Chatbot

🚀 Overview

The HR Policy Assistant Chatbot is a Retrieval-Augmented Generation (RAG)–based conversational AI solution built using LangChain, OpenAI, and Python.
It enables employees to instantly query organizational HR policies, benefits, leave structures, and procedures in natural language — providing accurate, contextual, and up-to-date responses.

The chatbot reduces dependency on HR teams by automating policy clarifications and integrates with Zapier to escalate unresolved or complex cases via email or ticket creation.

🧩 Tech Stack

Frameworks: LangChain, Python

LLM Backend: Azure OpenAI (GPT-4 / GPT-4-Turbo)

Retrieval Engine: FAISS (Vector Store)

UI Layer: Streamlit (Interactive Web Interface)

Integrations: Zapier (for escalation and email automation)

Data Sources: HR Policy PDFs, DOCX, Internal Docs, FAQs

Deployment Options:  Docker Container

Version Control: GitHub

✨ Key Features

💬 Conversational RAG Engine: Combines retrieval and generation to provide grounded, policy-specific answers.

🧠 Hybrid Search: Uses both semantic and keyword-based matching to ensure contextually relevant responses.

🧾 Context Retention: Maintains conversation history across turns for natural dialogue flow.

📤 Escalation Automation: Unanswered or complex queries are routed via Zapier to HR email or ticketing systems.

⚙️ Dynamic Policy Ingestion: Automatically indexes new or updated policy documents.

🧑‍💼 Employee ID Recognition: Identifies and tracks users for personalized interaction.

🗂 Topic Categorization: Automatically classifies policies (leave, payroll, benefits, etc.) for better search precision.

📊 Response Tracking: Logs queries and escalations for HR analytics.

🧠 Prompt Optimization: Utilizes refined prompt templates for accuracy and consistent tone.

🔄 Easy Extensibility: Add-on capability for integrating with HRMS or Employee Portals.

🧠 Current Capabilities

Context-aware HR policy Q&A

Document-based RAG search

Automated escalation via Zapier (email/ticket creation)

Configurable HR data ingestion

Streamlit interface with real-time updates

🔮 Future Enhancements

🚢 Deployment on Azure Kubernetes Service (AKS): Scalable, secure deployment for large organizations.

🗣 Voice Query Support: Integration with speech-to-text for voice-based policy queries.

📊 Analytics Dashboard: View query frequency, popular topics, and unresolved queries.

🧩 Integration with HRMS/Teams: Directly accessible via Microsoft Teams or Slack bot interface.

🧾 Multi-Language Support: Handle HR policy documents in multiple regional languages.

🔐 SSO Authentication: Integrate with Azure AD for secure employee access.

🧠 Proactive HR Insights: Identify trending employee concerns through LLM-based clustering.

📦 Repository Structure
hr_policy_assistant_chatbot/
├── app.py
├── config/
│   └── settings.py
├── modules/
│   ├── document_loader.py
│   ├── embedder.py
│   ├── search.py
│   ├── summarizer.py
│   ├── escalation_handler.py
│   ├── human_feedback.py
│   └── utils.py
├── ui/
│   └── ui.py
├── data/
│   ├── hr_policies/
│   └── uploads/
└── vectorstore/

🧾 Example Query

“How many casual leaves am I eligible for in a year?”

Bot Response:
“As per the HR leave policy (v2.1, Jan 2024), employees are entitled to 12 casual leaves per calendar year. Carry-forward is not applicable.”
