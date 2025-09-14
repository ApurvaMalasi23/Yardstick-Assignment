# Conversation Management & Classification using Groq API

This repository contains an implementation of the **internship assignment**: - **Task 1**: Managing conversation history with summarization. - **Task 2**: JSON schema–based classification & information extraction. The project uses **Groq’s OpenAI-compatible API** (with the `groq` Python SDK) and runs in **Google Colab** without any frameworks.

## 🚀 Features
- Maintains running conversation history with truncation options (by number of turns or word/character limit).  
- Periodic summarization after every *k-th run* of the conversation.  
- Function calling with JSON schema for structured data extraction (name, email, phone, location, age) validated using `jsonschema`.
