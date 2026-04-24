## Chapter 8: Building Smart Assistants: Agentic AI and Conversational AI — Practice Questions

### Multiple Choice

**Q1.** What is the primary characteristic that distinguishes Agentic AI from traditional AI systems?

A) It can only answer simple questions
B) It can perform multi-step tasks autonomously to achieve goals
C) It requires constant human supervision for every action
D) It only works with text-based inputs

<details>
<summary>Answer</summary>

**Correct: B**

Agentic AI is specifically designed to perform multi-step tasks autonomously to achieve goals, making decisions and taking actions without requiring human intervention at each step. Traditional AI systems typically handle single tasks or require more direct human guidance. Option A describes basic chatbots, C contradicts the autonomous nature of agentic AI, and D is incorrect as agentic AI can work with multiple input types.

</details>

---

**Q2.** Which Azure service is specifically designed for building conversational AI experiences like chatbots?

A) Azure Machine Learning
B) Azure Cognitive Services
C) Azure Bot Service
D) Azure Data Factory

<details>
<summary>Answer</summary>

**Correct: C**

Azure Bot Service is Microsoft's dedicated platform for building, testing, and deploying intelligent bots that can interact naturally with users across multiple channels. Azure Machine Learning is for building custom ML models, Azure Cognitive Services provides pre-built AI capabilities, and Azure Data Factory is for data integration and ETL processes.

</details>

---

**Q3.** What does "tool use" refer to in the context of AI agents?

A) The physical hardware required to run AI systems
B) An AI agent's ability to access and utilize external services, APIs, or functions
C) The programming languages used to build AI
D) The user interface for interacting with AI

<details>
<summary>Answer</summary>

**Correct: B**

Tool use refers to an AI agent's ability to access and utilize external services, APIs, databases, or functions to complete tasks. This capability allows agents to go beyond simple text generation to actually perform actions like searching the web, querying databases, or calling external services. The other options describe unrelated concepts in AI development.

</details>

---

**Q4.** When building an FAQ bot, which Azure capability would you primarily use to match user questions with appropriate answers?

A) Computer Vision
B) Speech Recognition
C) Question Answering
D) Face Detection

<details>
<summary>Answer</summary>

**Correct: C**

Question Answering is the Azure capability specifically designed to match user questions with appropriate answers from a knowledge base. It uses natural language understanding to find the best response even when questions are phrased differently. Computer Vision and Face Detection are for image analysis, and Speech Recognition converts spoken words to text but doesn't provide answers.

</details>

---

**Q5.** What is orchestration in the context of multi-agent AI solutions?

A) Playing music through AI systems
B) Coordinating multiple AI agents to work together on complex tasks
C) Converting speech to text
D) Storing data in databases

<details>
<summary>Answer</summary>

**Correct: B**

Orchestration in multi-agent solutions refers to coordinating multiple AI agents to work together effectively on complex tasks. An orchestrator manages the workflow, determines which agent should handle which part of a task, and ensures smooth communication between agents. This enables solving problems that would be too complex for a single agent.

</details>

---

### True / False

**Q6.** Conversational AI can only communicate through text-based chat interfaces. — **True / False**

*False. Conversational AI can communicate through multiple channels including text chat, voice interfaces, messaging platforms, and even video. Azure Bot Service, for example, allows bots to be deployed across channels like Microsoft Teams, web chat, Slack, and voice-enabled devices.*

---

**Q7.** An AI agent in a multi-step workflow can make decisions and adjust its approach based on the results of previous steps. — **True / False**

*True. This is a fundamental characteristic of agentic AI. AI agents can evaluate the outcomes of their actions, learn from results, and adapt their approach to achieve their goals. This decision-making capability is what enables them to handle complex, multi-step tasks without requiring human intervention at each stage.*

---

### Short Answer

**Q8.** Explain the difference between a simple chatbot and an AI agent.

<details>
<summary>Answer</summary>

A simple chatbot typically follows predefined scripts or rules to respond to user inputs, handling straightforward question-and-answer interactions without taking real-world actions. An AI agent, however, can autonomously plan and execute multi-step tasks, use external tools and services, make decisions based on context, and adapt its approach to achieve specific goals. While a chatbot might tell you the weather, an AI agent could check the forecast, compare flight prices, and book a trip for you.

</details>

---

**Q9.** What is a knowledge base in the context of building FAQ bots, and why is it important?

<details>
<summary>Answer</summary>

A knowledge base is a structured collection of question-answer pairs that serves as the information source for an FAQ bot. It contains the questions users might ask along with their corresponding answers. The knowledge base is important because it allows the Question Answering service to find relevant responses to user queries, even when users phrase their questions differently than the exact questions stored. A well-designed knowledge base ensures the bot can provide accurate, helpful responses to a wide range of user inquiries.

</details>

---

### Scenario-Based

**Q10.** A healthcare company wants to build an intelligent assistant that can: answer common patient questions about clinic hours and services, schedule appointments by checking doctor availability in their calendar system, and send confirmation emails to patients. Which combination of capabilities and services would you recommend, and why?

<details>
<summary>Answer</summary>

This scenario requires a combination of Conversational AI and Agentic AI capabilities:

1. **Azure Bot Service** - To create the conversational interface where patients can interact naturally through text or voice.

2. **Question Answering** - To handle the FAQ portion about clinic hours, services, and common questions by creating a knowledge base with this information.

3. **Agentic AI with Tool Use** - To enable the multi-step appointment scheduling process. The agent would need to:
   - Understand the patient's scheduling request
   - Use a tool/API to check the calendar system for doctor availability
   - Use another tool to book the appointment
   - Use an email service tool to send confirmations

4. **Orchestration** - To coordinate between the FAQ-answering component and the appointment-scheduling agent, routing requests to the appropriate capability based on user intent.

This architecture combines simple conversational responses for basic questions with agentic capabilities for the more complex, action-oriented tasks like scheduling and sending emails.

</details>