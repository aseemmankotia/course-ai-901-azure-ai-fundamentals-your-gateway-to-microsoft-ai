## Chapter 5: Teaching Machines to Understand Language: NLP Workloads — Flashcards

| # | Front (Question) | Back (Answer) |
|---|-----------------|---------------|
| 1 | What is Natural Language Processing (NLP)? | A branch of AI that enables machines to understand, interpret, and generate human language in a meaningful way |
| 2 | What is key phrase extraction in NLP? | The process of automatically identifying and extracting the most important words or phrases from a text that represent its main topics |
| 3 | What is Named Entity Recognition (NER)? | An NLP technique that identifies and categorizes entities in text into predefined categories like person names, organizations, locations, dates, and quantities |
| 4 | What does sentiment analysis determine? | Whether text expresses positive, negative, or neutral sentiment/opinion, often returning confidence scores for each category |
| 5 | What is language detection used for in Azure AI? | To automatically identify which language a given text is written in, returning a language code and confidence score |
| 6 | What are the three components of Language Understanding? | Utterances (what users say), Entities (specific data to extract), and Intents (the user's goal or purpose) |
| 7 | What is an utterance in Conversational Language Understanding? | An example phrase or sentence that a user might say, which the system uses to understand user requests |
| 8 | What is an intent in CLU? | The goal or action the user wants to accomplish, such as "BookFlight" or "CheckWeather" |
| 9 | What is an entity in CLU? | A specific piece of information to extract from an utterance, such as a city name, date, or product type |
| 10 | What Azure service provides NLP capabilities like sentiment analysis and key phrase extraction? | Azure AI Language service |
| 11 | What is Conversational Language Understanding (CLU)? | An Azure AI feature that lets you build custom natural language understanding models to interpret user intents and extract entities |
| 12 | How does text translation work in Azure AI? | It uses neural machine translation to convert text from one language to another while preserving meaning and context |
| 13 | What are common use cases for NLP workloads? | Chatbots, customer feedback analysis, document summarization, search enhancement, and automated support systems |
| 14 | What must you create before using CLU? | A Language resource in Azure, then define intents, entities, and provide example utterances for training |
| 15 | What is the relationship between NLP and chatbots? | NLP provides the language understanding foundation that allows chatbots to interpret user messages and respond appropriately |

### Key Terms

| Term | Definition |
|------|-----------|
| Natural Language Processing (NLP) | AI technology enabling computers to understand and process human language |
| Sentiment Analysis | Technique to determine emotional tone (positive, negative, neutral) in text |
| Named Entity Recognition (NER) | Extraction and classification of named entities like people, places, and organizations |
| Intent | The purpose or goal a user wants to achieve in a conversation |
| Entity | A specific data element extracted from user input (dates, names, locations) |
| Utterance | A sample phrase representing how users might express a request |
| Conversational Language Understanding (CLU) | Azure service for building custom language understanding models |
| Azure AI Language | Azure service providing pre-built NLP capabilities including text analytics |

### Memory Tricks
- **UIE for CLU**: Remember "**U**sers **I**ntend to **E**xtract" - Utterances show what users say, Intents show their goal, Entities are what you extract
- **SKLENT**: Sentiment, Key phrases, Language detection, Entities, NER, Translation - the main NLP capabilities (sounds like "skill-ent")
- **Pizza ordering analogy**: Utterance = "I want a large pepperoni pizza delivered at 7pm", Intent = OrderPizza, Entities = Size(large), Topping(pepperoni), Time(7pm)