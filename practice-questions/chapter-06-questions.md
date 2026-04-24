## Chapter 6: The AI Revolution: Generative AI and Azure OpenAI — Practice Questions

### Multiple Choice

**Q1.** What is the primary characteristic that distinguishes Generative AI from traditional AI systems?

A) It can only analyze existing data
B) It creates new, original content based on learned patterns
C) It requires no training data
D) It only works with numerical data

<details>
<summary>Answer</summary>

**Correct: B**

Generative AI is specifically designed to create new, original content such as text, images, or code based on patterns learned during training. Option A describes analytical AI, not generative. Option C is incorrect because all AI requires training data. Option D is wrong because generative AI works with many data types including text and images.

</details>

---

**Q2.** What does the "T" in GPT stand for?

A) Training
B) Text
C) Transformer
D) Technology

<details>
<summary>Answer</summary>

**Correct: C**

GPT stands for Generative Pre-trained Transformer. The Transformer architecture is the foundational neural network design that enables these models to process and generate language effectively. Training describes the process, Text describes one type of input/output, and Technology is too generic.

</details>

---

**Q3.** Which of the following best describes prompt engineering?

A) Building physical hardware for AI systems
B) Crafting effective inputs to guide AI model outputs
C) Programming the underlying neural network
D) Deleting unwanted AI responses

<details>
<summary>Answer</summary>

**Correct: B**

Prompt engineering is the practice of designing and refining the text inputs (prompts) given to AI models to achieve desired outputs. It does not involve hardware (A), modifying the neural network code (C), or removing responses (D). It focuses on how you communicate with the model.

</details>

---

**Q4.** Which Azure service provides enterprise access to OpenAI's GPT models with added security and compliance features?

A) Azure Machine Learning
B) Azure Cognitive Services
C) Azure OpenAI Service
D) Azure Bot Service

<details>
<summary>Answer</summary>

**Correct: C**

Azure OpenAI Service is Microsoft's offering that provides access to OpenAI models like GPT with enterprise-grade security, compliance, and regional availability. Azure Machine Learning is for custom model development, Cognitive Services provides pre-built AI APIs, and Bot Service is for conversational interfaces.

</details>

---

**Q5.** What does "multimodal" mean in the context of generative AI?

A) The model can only process one type of input at a time
B) The model can understand and generate multiple types of content (text, images, audio)
C) The model runs on multiple computers simultaneously
D) The model requires multiple users to operate

<details>
<summary>Answer</summary>

**Correct: B**

Multimodal AI refers to models that can process and generate multiple types of content, such as understanding images and responding with text, or creating images from text descriptions. It is not about processing limitations (A), computing infrastructure (C), or user requirements (D).

</details>

---

### True / False

**Q6.** Large Language Models (LLMs) understand language the same way humans do, with true comprehension of meaning. — **True / False**

*False. LLMs process language through statistical patterns and mathematical relationships learned from massive datasets. While they can generate remarkably human-like text, they do not possess true understanding or consciousness. They predict likely word sequences based on training patterns rather than comprehending meaning the way humans do.*

---

**Q7.** Azure OpenAI Service includes content filtering to help prevent the generation of harmful or inappropriate content. — **True / False**

*True. Azure OpenAI Service includes built-in content filtering and safety systems as part of Microsoft's responsible AI commitment. These filters help detect and block potentially harmful inputs and outputs, providing an additional layer of protection for enterprise applications.*

---

### Short Answer

**Q8.** Name three types of content that generative AI can create.

<details>
<summary>Answer</summary>

Generative AI can create: (1) Text content such as articles, summaries, or conversational responses; (2) Programming code in various languages; (3) Images and visual artwork. Other valid answers include audio/music, video, translations, and data analysis reports.

</details>

---

**Q9.** What is a "Copilot" experience in the context of Microsoft AI?

<details>
<summary>Answer</summary>

A Copilot is an AI-powered assistant integrated into Microsoft products and services that helps users complete tasks more efficiently. Copilots use generative AI to provide suggestions, automate repetitive work, answer questions, and assist with content creation while keeping the human user in control of final decisions.

</details>

---

### Scenario-Based

**Q10.** A marketing team wants to use Azure OpenAI Service to generate product descriptions for their e-commerce website. They are concerned about the AI occasionally producing inaccurate product claims. What two responsible AI practices should they implement to address this concern?

<details>
<summary>Answer</summary>

The marketing team should implement: (1) Human review and oversight — establishing a process where team members review AI-generated descriptions before publishing to catch inaccuracies; (2) Clear prompting with constraints — providing specific product specifications and guidelines in prompts to reduce hallucinations and keep outputs factually grounded. Additional good practices include using content filtering, testing outputs thoroughly, and maintaining transparency with customers about AI-assisted content creation.

</details>