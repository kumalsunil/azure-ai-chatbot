# 🤖 Building an AI Chatbot with Azure RAG

**Watch the full tutorial video below:**

<p align="center">
  <a href="https://www.youtube.com/watch?v=rWD_nqDT7rY">
    <img src="https://img.youtube.com/vi/rWD_nqDT7rY/hqdefault.jpg" alt="Click to watch the Azure AI Chatbot Tutorial" width="700">
  </a>
</p>

---

## 🛠️ Resources and Prerequisites

This guide outlines how to build an enterprise-style **Retrieval-Augmented Generation (RAG)** chatbot using the following tools and services:

* **💻 Operating System:** Windows 11
* **☁️ Cloud Platform:** Free **Microsoft Azure Subscription**
* **🧠 LLM Model:** **GPT-4o Mini** (via Azure OpenAI Service)
* **🌐 Key Azure Portal:** [ai.azure.com](https://ai.azure.com/)
---

## 1. Project Setup, Model Deployment, and Agent Creation

This combined section covers the initial steps: selecting the model to power your bot, naming the agent, and assigning its core responsibilities (instructions).

### 1.1 Deploy Model and Define Agent Role

1.  Navigate to **Azure AI Studio** (`ai.azure.com`) and log in.
2.  Start a new project or select an existing one.
3.  Go to the **'Agents'** section and click **'Create'** to start defining your custom chatbot.
4.  Select a powerful model for your deployment (e.g., `gpt-4o-mini`).
5.  Provide an **Agent name** (e.g., `customer service bot`) and define the scope of its job in the **Instructions** box.

| Description | Screenshot |
| :--- | :--- |
| **Model Selection** |<img width="1260" height="893" alt="1" src="https://github.com/user-attachments/assets/71077023-1813-41ca-aee8-8aac71c40dc2" /> |
| **Agent Name and Instructions** | <img width="425" height="588" alt="2" src="https://github.com/user-attachments/assets/537c84b1-6da8-49d4-9846-2e133976a8eb" />|

---

## 2. Test Persona and Verify Custom Knowledge

Once the agent is created, you must test its adherence to the instructions and confirm its ability to retrieve information from custom data sources (Knowledge).

### 2.1 Test Role and Instructions

1.  After saving the agent, navigate to the chat interface to test its initial configuration.
2.  Ask a question about its job to verify it adheres to the instructions and persona you provided.

| Description | Screenshot |
| :--- | :--- |
| **Testing Role Definition** |<img width="1045" height="276" alt="3" src="https://github.com/user-attachments/assets/a7517231-bc0f-417f-814d-e5e0a0be3806" />|

### 2.2 Verify Knowledge Retrieval

1.  Ask the chatbot a specific question that can only be answered by referencing the uploaded **Knowledge** file (e.g., a return policy document).

| Description | Screenshot |
| :--- | :--- |
| **Querying Custom Knowledge** |<img width="1060" height="338" alt="4" src="https://github.com/user-attachments/assets/743b2eaf-0faa-43c9-b775-82f2dabbedd7" /> |

Your custom AI chatbot is now deployed, instructed, and ready to be integrated into your application.
