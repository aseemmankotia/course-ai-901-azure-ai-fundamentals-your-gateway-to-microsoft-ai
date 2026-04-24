## Chapter 5: Teaching Machines to Understand Language: NLP Workloads — Quick Reference

### Core Concepts
| Concept | One-line explanation |
|---------|---------------------|
| Key Phrase Extraction | Identifies main talking points/important terms from unstructured text |
| Named Entity Recognition (NER) | Detects and categorizes entities like people, places, organizations, dates |
| Sentiment Analysis | Determines emotional tone (positive, negative, neutral) with confidence scores |
| Language Detection | Identifies which language text is written in |
| Text Translation | Converts text from one language to another |
| Utterances | What users say or type to interact with a language model |
| Entities | Specific items/data extracted from utterances (dates, names, locations) |
| Intents | The action or goal the user wants to accomplish |
| Azure AI Language | Unified service for NLP features including text analytics and CLU |
| Conversational Language Understanding (CLU) | Custom models to interpret natural language for conversational apps |

### Key Syntax / Commands
```
Azure AI Language Service Endpoint Pattern:
https://<resource-name>.cognitiveservices.azure.com/

CLU Project Components:
- Intents: Define user goals (e.g., "BookFlight", "CheckWeather")
- Entities: Define extractable data (e.g., "destination", "date")
- Utterances: Example phrases mapped to intents
```

### Common Patterns
**Pattern 1: Intent + Entity Extraction**
User says "Book a flight to Paris on Friday" → Intent: BookFlight, Entities: destination=Paris, date=Friday

**Pattern 2: Sentiment Pipeline**
Text input → Language Detection → Sentiment Analysis → Confidence scores (0-1)

### Things to Remember
✅ CLU requires training with sample utterances before deployment
✅ Sentiment returns scores for positive, neutral, AND negative (sum to 1)
✅ NER can identify pre-built categories OR custom entities
❌ Don't confuse intents (what user wants) with entities (data to extract)

### Quick Quiz
1. What extracts "Microsoft" as an organization from text? → Named Entity Recognition
2. What are the three CLU components? → Utterances, Intents, Entities