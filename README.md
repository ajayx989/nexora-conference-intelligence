# nexora-conference-intelligence
AI-powered conference intelligence agent built with Microsoft Copilot Studio, Power Automate, Tavily Search API and SharePoint for automated opportunity discovery, research orchestration and structured data management.
# NEXORA – AI-Powered Conference Intelligence Agent

An AI-powered research and opportunity discovery system built using Microsoft Copilot Studio, Power Automate, Tavily Search API and SharePoint.

NEXORA automates the discovery and structured tracking of academic conferences, Calls for Papers (CFPs), industry events, hackathons, speaking opportunities and sponsorship prospects across Artificial Intelligence, Agentic AI, Financial Technology, Banking and Auditing.

The system prioritises UK-based opportunities while retaining relevant international and online events for further evaluation.

## 1. Problem Statement

Identifying relevant academic and industry conferences involves extensive manual research across multiple websites, organisers, publishers and event platforms.

Traditional research processes often result in:
- Fragmented information across multiple sources.
- Repetitive searches and duplicate records.
- Difficulty tracking conference editions and opportunities.
- Limited source traceability.
- Time-consuming research and data consolidation.

NEXORA addresses these challenges through an AI-powered discovery workflow that combines web search, information processing, workflow orchestration and persistent data storage.

## 2. Key Features

- **AI-Powered Discovery:** Identifies conferences, CFPs, industry events, hackathons, speaking and sponsorship opportunities.
- **Live Web Research:** Integrates Tavily Search API for programmatic web discovery.
- **Workflow Automation:** Uses Power Automate to connect search services, agent interactions and data operations.
- **Persistent Data Storage:** Uses SharePoint to maintain discovery runs, query records, approval records and research observations.
- **Source Traceability:** Captures source URLs, organiser details, event information and discovery metadata.
- **Duplicate-Request Prevention:** Implements execution controls to reduce repeated discovery requests.
- **State-Aware Workflows:** Tracks run status and manages workflow execution.
- **Error Handling:** Incorporates execution-level error handling and validation controls.
- **Evidence-Oriented Research:** Records missing information and distinguishes unverified findings from confirmed information.

## 3. Technology Stack

| Component | Technology |
|---|---|
| AI Agent Platform | Microsoft Copilot Studio |
| Workflow Orchestration | Microsoft Power Automate |
| Web Search | Tavily Search API |
| Data Persistence | Microsoft SharePoint |
| API Integration | REST APIs |
| Automation | Power Automate Flows |
| Agent Instructions | Prompt Engineering |

## 4. System Architecture

User Request  
↓  
Microsoft Copilot Studio  
↓  
Power Automate Workflow  
↓  
Tavily Search API  
↓  
Research Results and Information Processing  
↓  
SharePoint Data Persistence  
↓  
Discovery Records and Review Workflow

## 5. Discovery Workflow

**Stage 1 – Universe Discovery**

- Discover potentially relevant events and opportunities.
- Execute focused searches across multiple research categories.
- Collect source links and available event information.
- Preserve potentially relevant candidates for further evaluation.

**Stage 2 – Screening and Validation (Planned Extension)**

- Review event eligibility and relevance.
- Validate dates, organisers and submission requirements.
- Identify incomplete or conflicting information.

**Stage 3 – Strategic Prioritisation (Planned Extension)**

- Evaluate opportunities against strategic criteria.
- Assess relevance to research and business objectives.
- Support submission and participation decisions.

**Stage 4 – Execution and Tracking (Planned Extension)**

- Track submission deadlines and event progress.
- Maintain opportunity records.
- Support follow-up and reporting workflows.

## 6. Data Management

SharePoint provides persistent storage for structured research information, including:

- Discovery run records.
- Query execution records.
- Approval records.
- Raw research observations.
- Source URLs and event metadata.
- Run status and discovery information.

## 7. Reliability and Data Integrity

The system incorporates design controls for:

- Run-status validation.
- Query execution controls.
- Duplicate-request prevention.
- Execution-level error handling.
- Source traceability.
- Missing-information identification.
- Separation of discovery from final verification and approval.

## 8. Current Scope and Limitations

The current implementation focuses on Stage 1: Universe Discovery.

Discovery results are preliminary research leads and should not be interpreted as verified conference opportunities.

Final eligibility screening, strategic prioritisation and submission decisions are outside the current discovery stage.

Automated execution and persisted approval capabilities depend on their configured integrations and permissions.

## 9. Future Enhancements

- Advanced duplicate detection across different source URLs.
- Automated event-date and CFP validation.
- AI-based relevance scoring and prioritisation.
- Research quality and source reliability evaluation.
- Dashboard for conference pipeline monitoring.
- Automated deadline notifications and follow-ups.
- Extended multi-stage opportunity management.

## 10. Project Objective

NEXORA demonstrates how conversational AI, external search APIs and workflow automation can be combined to transform a research-intensive business process into a structured, traceable and scalable intelligence workflow.

**Built with:** Microsoft Copilot Studio | Power Automate | Tavily API | SharePoint
