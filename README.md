# plant-rag
Retrieval Augmented Generation System for plant-related questions.

This system:
- loads a blog post's contents to a document object
- splits the document into chunks for storage
- embeds these chunks into a vector store
- asks user for question
- uses a vector store retriever to find relevant documents for the given question
- constructs a prompt and parses the output

Tutorial: https://python.langchain.com/docs/tutorials/rag/

### Example System Output
```
Question: Is there any plants that are toxic to pets? 
Answer: Yes, the String of Hearts plant is toxic to pets. It's important to keep such plants out of reach of animals. Always check the toxicity of any plant before bringing it into your home if you have pets. 
Context: 6 documents 
Example context: Take time to gently separate the stems of your String of Hearts, to avoid any tangling and damages.
```

## Tech Stack

- Framework: langchain
- Embedding: Open AI Embeddings
- Vector Store: Chroma
- LLM: OpenAI
  - model: `gpt-4o-mini`


