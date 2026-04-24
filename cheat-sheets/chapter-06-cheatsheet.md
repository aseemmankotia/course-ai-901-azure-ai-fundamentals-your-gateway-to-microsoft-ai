## Chapter 6: The AI Revolution: Generative AI and Azure OpenAI — Quick Reference

### Core Concepts
| Concept | One-line explanation |
|---------|---------------------|
| Generative AI | AI that creates new content (text, images, code) rather than just analyzing existing data |
| Large Language Models (LLMs) | Massive neural networks trained on vast text data to understand and generate human language |
| Transformer Architecture | Neural network design using attention mechanisms that powers GPT and modern LLMs |
| GPT (Generative Pre-trained Transformer) | OpenAI's family of LLMs that generate human-like text responses |
| Prompt Engineering | Crafting effective inputs to guide AI models toward desired outputs |
| Azure OpenAI Service | Microsoft's enterprise platform providing secure access to OpenAI models |
| Copilot | AI assistants embedded in Microsoft products (M365, GitHub, etc.) |
| Multimodal AI | Models that process and generate multiple content types (text, images, audio) |

### Key Syntax / Commands
```
# Azure OpenAI REST API Call Structure
POST https://{endpoint}/openai/deployments/{deployment-id}/chat/completions?api-version=2024-02-01

# Basic Prompt Template
System: [Define AI role/behavior]
User: [Your specific request]
Assistant: [AI response]
```

### Common Patterns
**Pattern 1: Zero-Shot Prompting**
Ask directly without examples — relies on model's training knowledge

**Pattern 2: Few-Shot Prompting**
Provide 2-3 examples before your request to guide output format/style

**Pattern 3: Chain-of-Thought**
Ask model to "think step by step" for complex reasoning tasks

### Things to Remember
✅ Temperature controls randomness (0=deterministic, 1=creative)
✅ Azure OpenAI includes enterprise security, compliance, and content filtering
✅ System messages set context and constraints for the entire conversation
❌ Don't assume AI outputs are factually accurate — always verify critical information

### Quick Quiz
1. What makes generative AI different from traditional AI? → Creates new content vs. classifies/predicts existing data
2. What is prompt engineering? → Designing effective inputs to get optimal AI responses
3. Which architecture powers GPT models? → Transformer with self-attention mechanisms