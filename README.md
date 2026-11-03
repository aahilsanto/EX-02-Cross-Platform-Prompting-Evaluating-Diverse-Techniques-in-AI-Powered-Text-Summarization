# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (Zero-Shot, Few-Shot, Chain-of-Thought, and Role-Based Prompting) across different AI platforms such as ChatGPT, Gemini, Claude, and Copilot for the task of technical text summarization.

---

## Scenario
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on **“The Basics of Blockchain Technology”** using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

- Accuracy
- Coherence
- Simplicity
- Speed
- User Experience

---

# Algorithm

## Step 1: Select the Topic
Choose a technical article for summarization.

Selected Topic:
**“The Basics of Blockchain Technology”**

The article includes:
- Definition of blockchain
- Decentralized ledger concept
- Blocks and cryptographic hashing
- Consensus mechanisms
- Applications of blockchain
- Advantages and challenges

---

## Step 2: Choose AI Platforms
The following AI tools were selected for experimentation:

- ChatGPT
- Google Gemini
- Claude AI
- Microsoft Copilot

---

## Step 3: Prepare Prompting Techniques

Four prompting strategies were used:

### A. Zero-Shot Prompting
The AI is directly asked to summarize the article without examples.

**Example:**  
“Summarize the following blockchain article in simple language for undergraduate students.”

---

### B. Few-Shot Prompting
The AI is provided with sample summaries before the actual task.

**Example:**  
Providing 1–2 example technical summaries before asking for the blockchain summary.

---

### C. Chain-of-Thought Prompting
The AI is instructed to analyze the article step-by-step before generating the summary.

**Example:**  
“Identify the important concepts first and then generate a concise summary.”

---

### D. Role-Based Prompting
A role or persona is assigned to the AI.

**Example:**  
“Act as a university professor and summarize blockchain technology for students.”

---

## Step 4: Generate Responses
The same blockchain article was given to every AI platform.

Each prompting strategy was tested individually:
- Zero-Shot
- Few-Shot
- Chain-of-Thought
- Role-Based

The generated summaries were collected and analyzed.

---

## Step 5: Organize Results
The responses were compared based on:
- Accuracy
- Coherence
- Simplicity
- Speed
- User Experience

---

# Result

## ChatGPT + Zero-Shot Prompting

### Prompt Used
> “Summarize the 500-word technical article on "The Basics of Blockchain Technology" into a concise and easy-to-understand summary for undergraduate students. Highlight the key concepts, working principles, advantages, and applications of blockchain technology.”

### Summary Generated
Blockchain is a decentralized digital ledger that records transactions securely across multiple computers without requiring a central authority. It uses interconnected blocks, cryptographic hashing, and consensus mechanisms such as Proof of Work and Proof of Stake to verify and store data. Its key advantages include transparency, security, data integrity, and traceability. Blockchain is widely used in cryptocurrency, healthcare, supply chain management, digital identity, and smart contracts. However, scalability, energy consumption, and privacy remain major challenges.

### Evaluation
- Accuracy: High
- Coherence: Good
- Simplicity: Excellent
- Speed: Very Fast
- User Experience: Excellent

---

## Gemini + Few-Shot Prompting

### Prompt Used
> “You are an expert educational content summarizer.

Follow these examples:

Example 1:
Topic: Cloud Computing
Summary: Cloud computing provides on-demand access to computing resources over the internet.

Example 2:
Topic: Machine Learning
Summary: Machine learning enables computers to learn patterns from data and make predictions.

Now summarize the 500-word technical article on "The Basics of Blockchain Technology". Use simple language and highlight its important concepts, working principles, and applications.”

### Summary Generated
Topic: The Basics of Blockchain Technology

Summary: Blockchain is a decentralized, secure digital ledger that records transactions across a network of computers without a central authority. By using cryptographic hashes to chain blocks together and relying on consensus mechanisms (such as Proof of Work or Proof of Stake) to verify data, it ensures transparency and immutability, enabling applications in finance, supply chain management, healthcare, and smart contracts.

### Evaluation
- Accuracy: Very High
- Coherence: Excellent
- Simplicity: Moderate
- Speed: Fast
- User Experience: Good

---

## Claude AI + Chain-of-Thought Prompting

### Prompt Used
> “Analyze the 500-word technical article on "The Basics of Blockchain Technology" and prepare a structured summary for undergraduate students.

Organize the analysis into the following stages:
1. Identify the main topic and objective.
2. Extract the fundamental concepts.
3. Identify the blockchain architecture and working mechanism.
4. Highlight the major advantages and applications.
5. Summarize the important findings.

Present the final summary in clear, simple language without unnecessary technical complexity.”

### Summary Generated
Blockchain is a distributed ledger technology that stores and verifies information across many computers without a central authority. Data is kept in blocks, each holding transactions, a timestamp, and a hash that links it to the previous block, so tampering is easy to detect. Transactions are verified by nodes, grouped into blocks, and approved through consensus methods like Proof of Work or Proof of Stake. Its advantages include decentralization, transparency, and data integrity, with uses in finance, supply chains, healthcare, and smart contracts. Challenges include scalability, energy use, delays, regulation, and privacy. Traditional databases may suit cases with a trusted administrator.

### Evaluation
- Accuracy: Excellent
- Coherence: Excellent
- Simplicity: Good
- Speed: Moderate
- User Experience: Very Good

---

## Copilot + Role-Based Prompting

### Prompt Used
> “Act as an experienced technical writer and blockchain educator. Summarize the 500-word technical article on "The Basics of Blockchain Technology" for undergraduate students. Explain complex technical concepts in simple language while maintaining technical accuracy. Focus on the fundamental concepts, architecture, working mechanism, and real-world applications.”

### Summary Generated
Blockchain is a decentralized digital ledger that records and shares information across multiple computers without relying on a central authority. It consists of linked blocks containing transaction data, timestamps, and cryptographic hashes, which help ensure security and prevent tampering. Transactions are verified by network participants and added to the blockchain through consensus mechanisms such as Proof of Work (PoW) and Proof of Stake (PoS). Blockchain offers transparency, data integrity, and traceability. Its applications include cryptocurrencies, supply chain tracking, healthcare record management, and smart contracts. Despite challenges like scalability and energy consumption, blockchain remains a key technology for secure digital systems.

### Evaluation
- Accuracy: Good
- Coherence: Good
- Simplicity: Excellent
- Speed: Fast
- User Experience: Good

---

# Comparison Table

| Platform | Prompting Technique | Accuracy | Coherence | Simplicity | Speed | User Experience |
|---|---|---|---|---|---|---|
| ChatGPT | Zero-Shot | High | Good | Excellent | Very Fast | Excellent |
| Gemini | Few-Shot | Very High | Excellent | Moderate | Fast | Good |
| Claude AI | Chain-of-Thought | Excellent | Excellent | Good | Moderate | Very Good |
| Copilot | Role-Based | Good | Good | Excellent | Fast | Good |

---

# Final Result

Thus, different prompting strategies were tested across multiple AI platforms for summarizing a technical article on blockchain technology.

- **Claude AI + Chain-of-Thought Prompting** produced the most accurate and coherent summaries.
- **ChatGPT + Zero-Shot Prompting** provided the best balance between simplicity, speed, and readability.
- **Gemini + Few-Shot Prompting** generated structured and detailed summaries.
- **Copilot + Role-Based Prompting** created beginner-friendly and concise explanations.

Overall, **ChatGPT with Zero-Shot Prompting** was identified as the most suitable combination for undergraduate educational summaries because it offered clear, simple, fast, and user-friendly results.
