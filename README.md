# 🤖 Building an AI Chatbot with Azure RAG

## 🛠️ Resources and Prerequisites

This guide outlines how to build an enterprise-style **Retrieval-Augmented Generation (RAG)** chatbot using the following tools and services:

* **💻 Operating System:** Windows 11
* **☁️ Cloud Platform:** Free **Microsoft Azure Subscription**
* **🧠 LLM Model:** **GPT-4o Mini** (via Azure OpenAI Service)
* **🌐 Key Azure Portal:** [ai.azure.com](https://ai.azure.com/)

---

## 🧠 Project Architecture Overview

This project uses the **RAG pattern**, grounding the AI model in your custom business data for accurate and reliable responses. The core services used are:

1.  **Service:** **Azure OpenAI Service** - Used for running the **GPT-4o Mini** model and generating conversational responses.
2.  **Data:** **Azure AI Search** - Used for creating the searchable **vector index** of your business documents.
3.  **Logic:** **Orchestration Layer** - A simple API to manage the retrieval of documents and prompt construction.

---

**Watch the full tutorial video here:**

<p align="center">
  <a href="https://www.youtube.com/watch?v=rWD_nqDT7rY">
    <img src="https://img.youtube.com/vi/rWD_nqDT7rY/hqdefault.jpg" alt="Click to watch the Azure AI Chatbot Tutorial" width="700">
  </a>
</p>
