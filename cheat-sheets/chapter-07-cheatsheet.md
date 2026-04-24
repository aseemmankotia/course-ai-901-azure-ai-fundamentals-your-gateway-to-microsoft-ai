## Chapter 7: Meet Microsoft Foundry: Your AI Development Hub — Quick Reference

### Core Concepts
| Concept | One-line explanation |
|---------|---------------------|
| Microsoft Foundry | Unified AI development platform (formerly Azure AI Studio) for building, deploying, and managing AI solutions |
| Foundry Portal | Web-based interface for navigating AI tools, models, and project resources |
| Model Catalog | Pre-built AI models library including Azure OpenAI, Meta Llama, Mistral, and more |
| Projects | Containers for organizing AI resources, deployments, and configurations |
| Model Deployment | Process of making AI models available as endpoints for applications |
| Foundry SDK | Python libraries for programmatically interacting with Foundry services |
| Azure Content Understanding | Service for extracting insights from documents, images, and unstructured data |

### Key Syntax / Commands
```python
# Install Foundry SDK
pip install azure-ai-projects azure-identity

# Initialize client
from azure.ai.projects import AIProjectClient
from azure.identity import DefaultAzureCredential

client = AIProjectClient(
    credential=DefaultAzureCredential(),
    endpoint="https://<your-project>.api.azureml.ms"
)

# Call deployed model
response = client.inference.chat_completions(
    model="gpt-4",
    messages=[{"role": "user", "content": "Hello!"}]
)
```

### Common Patterns
**Pattern 1: Project-Based Development**
Create project → Add models from catalog → Deploy endpoint → Integrate via SDK

**Pattern 2: Rapid Prototyping**
Use Foundry playground to test prompts → Refine → Export code → Build application

### Things to Remember
✅ Foundry consolidates Azure AI services into one unified development experience
✅ Model catalog offers both Microsoft and open-source models with one-click deployment
✅ Always create a project first—it organizes resources and manages access
❌ Don't deploy models without considering regional availability and quota limits

### Quick Quiz
1. What was Microsoft Foundry previously called? → Azure AI Studio
2. Where do you browse pre-built models? → Model Catalog
3. What authentication method does the SDK use? → DefaultAzureCredential (Azure Identity)