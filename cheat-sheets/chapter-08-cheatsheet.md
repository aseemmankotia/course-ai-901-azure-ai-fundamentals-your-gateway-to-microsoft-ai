## Chapter 8: Building Smart Assistants: Agentic AI and Conversational AI — Quick Reference

### Core Concepts
| Concept | One-line explanation |
|---------|---------------------|
| Agentic AI | AI systems that autonomously plan and execute multi-step tasks to achieve goals |
| AI Agents | Autonomous programs that perceive, decide, and act using AI capabilities and tools |
| Tool Use | Agents calling external APIs, databases, or services to complete tasks |
| Conversational AI | AI that enables natural language dialogue between humans and machines |
| Azure Bot Service | Microsoft platform for building, testing, and deploying intelligent bots |
| Question Answering | AI capability that extracts answers from knowledge bases and documents |
| FAQ Bots | Automated assistants that answer frequently asked questions |
| Multi-Agent Orchestration | Coordinating multiple specialized agents to solve complex problems |

### Key Syntax / Commands
```
Azure Bot Service Components:
├── Bot Framework SDK (C#, JavaScript, Python)
├── Bot Framework Composer (visual authoring)
├── Channels (Teams, Web, Slack, etc.)
└── Azure AI Language (QnA integration)

Question Answering Setup:
1. Create Language Resource → 2. Import Knowledge Base → 3. Train → 4. Deploy → 5. Connect to Bot
```

### Common Patterns
**Pattern 1: Agent Loop**
Perceive → Plan → Act → Observe → Repeat until goal achieved

**Pattern 2: Tool-Augmented Agent**
User request → Agent reasons → Selects tool → Executes → Returns result

**Pattern 3: Orchestrated Multi-Agent**
Orchestrator receives task → Delegates to specialist agents → Combines responses

### Things to Remember
✅ Agentic AI combines reasoning, planning, and tool use for autonomous task completion
✅ Azure Bot Service connects to 15+ channels with single bot deployment
✅ Question Answering requires a knowledge base (URLs, files, or manual QnA pairs)
❌ Don't confuse simple chatbots (scripted responses) with agentic AI (autonomous reasoning)

### Quick Quiz
1. What makes AI "agentic"? → Autonomous multi-step task execution with planning and tool use
2. Which Azure service hosts conversational bots? → Azure Bot Service