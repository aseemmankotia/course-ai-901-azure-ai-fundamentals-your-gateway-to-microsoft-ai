## Chapter 1: Welcome to the World of AI: What Makes Machines Smart? — Practice Questions

### Multiple Choice

**Q1.** What is the best definition of Artificial Intelligence (AI)?

A) Software that can only perform calculations faster than humans
B) The simulation of human intelligence processes by computer systems
C) A type of robot that looks and acts exactly like a human
D) Any computer program that uses the internet

<details>
<summary>Answer</summary>

**Correct: B**

Artificial Intelligence refers to the simulation of human intelligence processes by computer systems, including learning, reasoning, and self-correction. Option A is too narrow as AI encompasses much more than calculations. Option C describes humanoid robots, which are just one possible application of AI. Option D is incorrect as internet connectivity has nothing to do with whether a system is considered AI.

</details>

---

**Q2.** Which of the following correctly describes the relationship between AI, Machine Learning, and Deep Learning?

A) They are three completely separate and unrelated technologies
B) Machine Learning is a subset of Deep Learning, which is a subset of AI
C) AI is a subset of Machine Learning, which is a subset of Deep Learning
D) Deep Learning is a subset of Machine Learning, which is a subset of AI

<details>
<summary>Answer</summary>

**Correct: D**

Deep Learning is a specialized subset of Machine Learning, which itself is a subset of the broader field of Artificial Intelligence. Think of it like nesting dolls: AI is the largest category encompassing all intelligent systems, Machine Learning is a specific approach within AI that learns from data, and Deep Learning is a particular technique within Machine Learning that uses neural networks with multiple layers.

</details>

---

**Q3.** A bank wants to identify unusual transactions that might indicate fraud. Which AI workload type is most appropriate for this use case?

A) Computer Vision
B) Generative AI
C) Anomaly Detection
D) Natural Language Processing

<details>
<summary>Answer</summary>

**Correct: C**

Anomaly Detection is specifically designed to identify patterns that deviate from expected behavior, making it ideal for fraud detection. Computer Vision analyzes images and video, not transaction data. Generative AI creates new content rather than detecting unusual patterns. Natural Language Processing deals with text and speech, not numerical transaction patterns.

</details>

---

**Q4.** Which Azure AI service would you use to build a chatbot that understands and responds to customer questions?

A) Azure Computer Vision
B) Azure Language Service
C) Azure Anomaly Detector
D) Azure Custom Vision

<details>
<summary>Answer</summary>

**Correct: B**

Azure Language Service provides Natural Language Processing capabilities including question answering and conversational AI features needed for building chatbots. Azure Computer Vision and Custom Vision are for image analysis, not text understanding. Azure Anomaly Detector identifies unusual patterns in data, not process conversations.

</details>

---

**Q5.** A retail company wants to automatically count customers entering their stores using security camera footage. Which AI workload type should they use?

A) Prediction
B) Natural Language Processing
C) Generative AI
D) Computer Vision

<details>
<summary>Answer</summary>

**Correct: D**

Computer Vision is the AI workload type that analyzes and interprets visual information from images and video. Counting people from camera footage requires detecting and tracking visual objects (people) in video streams. Prediction typically involves forecasting future values. NLP processes text and speech, not video. Generative AI creates new content rather than analyzing existing visual data.

</details>

---

### True / False

**Q6.** Machine Learning requires programmers to explicitly code every rule the system follows to make decisions. — **True / False**

<details>
<summary>Answer</summary>

**False**

Machine Learning is fundamentally different from traditional programming because the system learns patterns and rules from data rather than having them explicitly programmed. Instead of writing specific rules, developers provide training data and algorithms that allow the machine to discover patterns and make decisions based on what it has learned. This is what makes ML powerful for complex problems where writing explicit rules would be impractical.

</details>

---

**Q7.** Generative AI is a type of AI workload that creates new content such as text, images, or code based on patterns learned from training data. — **True / False**

<details>
<summary>Answer</summary>

**True**

Generative AI is indeed designed to create new, original content by learning patterns from large amounts of training data. Examples include AI systems that generate text (like ChatGPT), create images (like DALL-E), compose music, or write code. This differs from other AI workloads that analyze, classify, or predict based on existing data rather than generating new content.

</details>

---

### Short Answer

**Q8.** List three real-world applications of Natural Language Processing (NLP) that you might encounter in everyday life.

<details>
<summary>Answer</summary>

Common real-world NLP applications include:
- **Virtual assistants** (Siri, Alexa, Cortana) that understand spoken commands
- **Email spam filters** that analyze text to identify unwanted messages
- **Language translation services** (Google Translate, Microsoft Translator)
- **Sentiment analysis** on social media or product reviews
- **Autocomplete and predictive text** on smartphones
- **Customer service chatbots** on websites

Any three valid examples demonstrating text or speech processing by AI would be acceptable.

</details>

---

**Q9.** Explain the difference between a prediction workload and an anomaly detection workload in AI.

<details>
<summary>Answer</summary>

**Prediction workloads** use historical data patterns to forecast future values or outcomes. For example, predicting tomorrow's sales based on past sales trends, or estimating a customer's likelihood to purchase a product.

**Anomaly detection workloads** identify data points or patterns that deviate significantly from what is considered normal or expected. For example, detecting a fraudulent credit card transaction or identifying a machine malfunction based on unusual sensor readings.

The key difference is that prediction forecasts what will likely happen next, while anomaly detection identifies what is happening that is unusual or unexpected compared to normal patterns.

</details>

---

### Scenario-Based

**Q10.** A healthcare company wants to implement AI solutions for three different challenges:
1. Analyzing X-ray images to help doctors identify potential issues
2. Predicting which patients are at high risk for hospital readmission within 30 days
3. Automatically transcribing doctor-patient conversations into medical notes

For each challenge, identify the appropriate AI workload type and suggest which category of Azure AI services would be most relevant.

<details>
<summary>Answer</summary>

**Challenge 1: Analyzing X-ray images**
- **AI Workload Type:** Computer Vision
- **Azure AI Service Category:** Azure Computer Vision or Azure Custom Vision (if training on specific medical images)
- **Reasoning:** This requires analyzing visual/image data to identify patterns, which is the core purpose of computer vision AI.

**Challenge 2: Predicting patient readmission risk**
- **AI Workload Type:** Prediction
- **Azure AI Service Category:** Azure Machine Learning
- **Reasoning:** This involves using historical patient data to forecast future outcomes (readmission probability), which is a classic prediction task requiring machine learning models.

**Challenge 3: Transcribing conversations into notes**
- **AI Workload Type:** Natural Language Processing (NLP)
- **Azure AI Service Category:** Azure Speech Service (for transcription) combined with Azure Language Service (for understanding and structuring the content)
- **Reasoning:** This requires converting speech to text and potentially understanding medical terminology and context, which are NLP capabilities.

</details>

---