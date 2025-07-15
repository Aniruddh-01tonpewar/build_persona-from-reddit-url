# build_persona-from-reddit-url


This project extracts Reddit user content and generates a detailed *user persona* using a *Retrieval-Augmented Generation (RAG)* pipeline with LLMs.
Features

- Accepts a Reddit user profile URL
- Scrapes posts and comments using LangChain’s WebBaseLoader
- Splits content into chunks
- Embeds content using OpenAI Embeddings
- Stores vectors in ChromaDB
- Uses RAG to generate a user persona including:
 - Personal Information
 - Motivations
 - Personality
 - Behaviour and Habits
 - Goals and needs
 - Frustrations
