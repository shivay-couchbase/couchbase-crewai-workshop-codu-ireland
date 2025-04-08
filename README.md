# couchbase-crewai-workshop

# Workshop: Semantic AI Agents for Real-World Applications

In this session, we will explore how to build a powerful semantic search engine using **Couchbase** as the backend database and **CrewAI** for agent-based Retrieval-Augmented Generation (RAG) operations. This workshop is designed to provide hands-on experience with creating AI agents that collaborate to retrieve, analyze, and generate meaningful responses to user queries.

---

## Objectives

By the end of this workshop, you will:
1. Understand the fundamentals of Retrieval-Augmented Generation (RAG).
2. Learn how to set up and configure Couchbase for vector storage and semantic search.
3. Build and deploy AI agents using CrewAI to handle research and response generation tasks.
4. Create a scalable, real-world semantic search system.

---

## Prerequisites

Before starting, ensure you have the following:
- **Python 3.8+** installed on your system.
- A **Couchbase Capella** account with a free-tier operational cluster set up. [Sign up here](https://cloud.couchbase.com/sign-up).
- Basic knowledge of Python programming and AI concepts.
- Installed libraries: `datasets`, `langchain-couchbase`, `langchain-openai`, `crewai`, `python-dotenv`.

To install the required libraries, run:
```bash
pip install datasets langchain-couchbase langchain-openai crewai python-dotenv
```

## Workshop Agenda

1. **Introduction to RAG and Semantic Search**
   * Overview of RAG and its applications.
   * How semantic search differs from traditional keyword-based search.

2. **Setting Up Couchbase**
   * Deploying a Couchbase cluster on Capella.
   * Configuring buckets, scopes, and collections for vector storage.
   * Creating a vector search index for semantic queries.

3. **Building AI Agents with CrewAI**
   * Introduction to CrewAI and its agent-based architecture.
   * Creating specialized agents:
     * **Research Expert**: Retrieves and analyzes relevant documents.
     * **Technical Writer**: Structures and generates polished responses.
   * Defining agent roles, goals, and workflows.

4. **Integrating Couchbase with CrewAI**
   * Storing and retrieving vector embeddings in Couchbase.
   * Using CrewAI agents to perform semantic searches and generate responses.

5. **Testing and Deploying the System**
   * Running example queries to test the system.
   * Measuring performance and refining the workflow.