## Chapter 5: Teaching Machines to Understand Language: NLP Workloads — Practice Questions

### Multiple Choice

**Q1.** Which Azure AI Language feature would you use to automatically identify and categorize mentions of people, places, and organizations in a news article?

A) Sentiment analysis
B) Key phrase extraction
C) Named entity recognition
D) Language detection

<details>
<summary>Answer</summary>

**Correct: C**

Named entity recognition (NER) is specifically designed to identify and categorize entities such as people, places, organizations, dates, and quantities in text. Sentiment analysis determines emotional tone, key phrase extraction identifies important topics, and language detection identifies which language the text is written in.

</details>

---

**Q2.** A customer review states: "The product arrived quickly but the quality was disappointing." What would sentiment analysis most likely return for this text?

A) Positive
B) Negative
C) Neutral
D) Mixed

<details>
<summary>Answer</summary>

**Correct: D**

This review contains both positive elements ("arrived quickly") and negative elements ("quality was disappointing"), making it a mixed sentiment. Sentiment analysis can detect when text contains multiple emotional tones rather than forcing a single classification.

</details>

---

**Q3.** In Conversational Language Understanding (CLU), what term describes the action or goal that a user wants to accomplish?

A) Entity
B) Utterance
C) Intent
D) Key phrase

<details>
<summary>Answer</summary>

**Correct: C**

An intent represents the action or goal the user wants to achieve (such as "BookFlight" or "CheckWeather"). An utterance is the actual text input from the user, and an entity is a specific piece of information within that utterance (like a city name or date).

</details>

---

**Q4.** Which component of CLU would capture "Seattle" and "December 15th" from the utterance "Book a flight to Seattle on December 15th"?

A) Intents
B) Entities
C) Utterances
D) Key phrases

<details>
<summary>Answer</summary>

**Correct: B**

Entities are the specific pieces of relevant information extracted from an utterance. In this example, "Seattle" would be a destination entity and "December 15th" would be a date entity. The intent would be "BookFlight" and the entire sentence is the utterance.

</details>

---

**Q5.** What is the primary purpose of key phrase extraction in Azure AI Language?

A) To translate text between languages
B) To identify the main topics and important concepts in text
C) To determine if text is positive or negative
D) To detect which language the text is written in

<details>
<summary>Answer</summary>

**Correct: B**

Key phrase extraction analyzes text to identify the main talking points and important concepts. This helps summarize large amounts of text or categorize documents by topic. Translation, sentiment analysis, and language detection are separate features with different purposes.

</details>

---

### True / False

**Q6.** Language detection in Azure AI Language can only identify one language per document, even if the document contains text in multiple languages. — **True / False**

<details>
<summary>Answer</summary>

**False**

Azure AI Language's language detection can identify multiple languages within a single document. It can detect the predominant language and also identify sections written in different languages, returning confidence scores for each detected language.

</details>

---

**Q7.** When building a Conversational Language Understanding model, you must provide multiple example utterances for each intent to improve the model's accuracy. — **True / False**

<details>
<summary>Answer</summary>

**True**

Providing multiple varied example utterances for each intent helps the CLU model learn the different ways users might express the same goal. This improves the model's ability to correctly classify new utterances it hasn't seen before during training.

</details>

---

### Short Answer

**Q8.** Explain the difference between an utterance and an intent in Conversational Language Understanding.

<details>
<summary>Answer</summary>

An utterance is the actual text input that a user provides, such as "What's the weather like tomorrow?" or "Turn on the living room lights." An intent is the goal or action that the CLU model determines the user wants to accomplish based on that utterance, such as "GetWeather" or "ControlDevice." Multiple different utterances can map to the same intent.

</details>

---

**Q9.** Name three types of entities that Named Entity Recognition can identify in text.

<details>
<summary>Answer</summary>

Named Entity Recognition can identify entities such as: Person names, Organization names, Locations/Places, Dates and times, Quantities/Numbers, Email addresses, Phone numbers, URLs, and Events. Any three of these (or similar valid entity types) would be correct answers.

</details>

---

### Scenario-Based

**Q10.** A hotel chain wants to build an AI solution that analyzes customer reviews from their website. They need to: (1) understand what topics guests frequently mention, (2) determine if reviews are positive or negative, and (3) identify specific hotel locations mentioned in reviews. Which three Azure AI Language features should they use, and what would each feature accomplish?

<details>
<summary>Answer</summary>

The hotel chain should use:

1. **Key phrase extraction** - This will identify the main topics customers discuss in their reviews, such as "room cleanliness," "friendly staff," "breakfast buffet," or "parking availability." This helps the hotel understand what matters most to guests.

2. **Sentiment analysis** - This will classify each review as positive, negative, neutral, or mixed, allowing the hotel to quickly identify unhappy customers who may need follow-up and track overall customer satisfaction trends.

3. **Named entity recognition** - This will identify specific hotel locations mentioned in reviews (such as city names or hotel branch names), enabling the hotel to analyze feedback for individual properties and compare performance across locations.

</details>