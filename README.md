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

## Working Examples

![Screenshot 2024-10-22 at 21 18 26](https://github.com/user-attachments/assets/039202b5-9642-491e-b7d8-08a0f9c313d8)

![Screenshot 2024-10-22 at 21 16 56](https://github.com/user-attachments/assets/716f1b08-a156-482f-8fff-28bb942052b1)

![Screenshot 2024-10-22 at 21 11 17](https://github.com/user-attachments/assets/f968dee4-30f0-4152-8ef8-ef1a32843875)



https://github.com/user-attachments/assets/2a0708b7-d5f5-416b-8a89-1e6117e606e6



https://github.com/user-attachments/assets/70f3343e-55c7-4d4b-883c-f8ef89430360


