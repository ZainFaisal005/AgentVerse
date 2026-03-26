# 🧠 InfoSolver AI

**InfoSolver AI** is a multi-tool intelligent agent built using **LangChain** and **Groq LLM**.  
It can answer general knowledge questions, perform calculations, search the web for current information, and remember previous interactions.  
The agent intelligently decides which tool to use for each query, making it a versatile and interactive assistant.

---

## 🚀 Project Overview

InfoSolver AI combines **three main tools**—Wikipedia, DuckDuckGo, and Calculator—along with **memory**, to provide accurate and context-aware answers.  
It is designed to handle **multi-step reasoning** and **real-time information retrieval** in a single conversation.

---

## 📚 Wikipedia Tool

**Purpose:** Provides reliable general knowledge and factual information.  
- Queries about historical events, famous personalities, scientific facts, and other encyclopedic knowledge are answered using this tool.  
- Example: "Who is Albert Einstein?"  

---

## 🌐 DuckDuckGo Tool

**Purpose:** Fetches **current and recent information** from the web.  
- Ideal for news, live updates, or information not available on Wikipedia.  
- Example: "Latest news about AI in 2026"  

---

## 🧮 Calculator Tool

**Purpose:** Handles mathematical operations.  
- Performs calculations using numeric inputs from queries or results retrieved from other tools.  
- Example: "The population of Germany divided by the number of states in Germany"  

---

## 🧠 Memory Feature

**Purpose:** Enables the agent to **remember previous user inputs and context**.  
- Makes the conversation more natural and allows follow-up questions.  
- Example:  
    ```
    You: My name is Zain
    Agent: Got it, your name is Zain.
    You: What is my name?
    Agent: Your name is Zain.
    ```

---

## 🔗 Multi-Tool Query Handling

**Purpose:** Demonstrates the agent's ability to **combine tools for complex queries**.  
- Example: "Compare the GDP of Pakistan with Bangladesh and tell me the difference."  
    - Wikipedia → Pakistan GDP  
    - DuckDuckGo → Bangladesh GDP  
    - Calculator → Difference  

---

## ⚡ Key Features

- Conversational and context-aware  
- Handles **knowledge, math, and web search**  
- Markdown-formatted answers for clean display in notebooks  
- Memory-enabled for follow-up queries  
- Uses Groq LLM for high-quality reasoning  

---

## 💡 Example Queries

- "The height of Mount Everest minus the height of K2"  
- "Latest stock price of Tesla divided by 10"  
- "Who is Elon Musk?"  
- "Population of Pakistan divided by 2"  

---

## 🏗️ Tech Stack

- **LangChain** – Agent orchestration  
- **Groq LLM** – Language model backend  
- **WikipediaAPI** – Knowledge retrieval  
- **DuckDuckGo / ddgs** – Web search  
- **LLMMathChain** – Calculations  
- **ConversationBufferMemory** – Memory for context  

---

## 📌 Conclusion

InfoSolver AI is a **versatile AI assistant** capable of handling a wide variety of queries by intelligently using multiple tools and maintaining conversation context.  
It’s a perfect showcase project for **multi-tool agents in LangChain**, demonstrating **knowledge retrieval, real-time web search, math computation, and memory** in one platform.