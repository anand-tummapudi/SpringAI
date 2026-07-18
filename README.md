# Spring AI

### What is Spring AI
- Framework for integrating AI into Spring applications.
- Simplifies adding generative AI using Spring's modular, POJO-based design.
- Connects enterprise data and APIs wit AI models seamlessly. 

### Core Features
- **Multi-Provider Support** : Integrates with openAI, Anthropic, AWS, Google, Hugging Face for chat, embedding, text-to-image, audio and moderation.
- **MCP(Model COntext Protocol) Support** : Allows building MCP clients and servers easily. 
- **Vector Store Integration** : Supports RAG with Pinecone, Redis, PostgreSQL/pgVector, MongoDB, etc.
- **Advanced Patterns** : Chat Memory, tool/function calling, and advisors API for reusable AI logic.
- **Observability and Guardrails** : Monitors AI operations and evaluate outputs to ensure reliability.

### Interfaces in Spring AI
There are 2 main interfaces in Spring AI to leverage AI features **ChatClient** and **ChatModel**.
- **ChatModel** : Is an interface,which has all the important contract details to interact with an LLM model. It provides low level api using which we can interac with the LLM models. 
- **ChatClient** : Chatclient is a high level fluent api model using which we can send requests to our chat models. It is going to pass the request to the chat models. High level api gives flexibility to the developer.

# Langchain4J