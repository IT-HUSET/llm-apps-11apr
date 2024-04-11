# Workshop LLM-apps April 11

![Wanna chat](images/wannachat.png)

# Welcome!

## Sample code to get started

### Using the Open AI API

#### 1. [OpenAI basics](openai/1-openai-basics.ipynb)
#### 2. [Classification](openai/2-classification-example.ipynb)
#### 3. [Function calling](openai/3-How_to_call_functions_with_chat_models.ipynb)

### LangChain

#### 1.1. [Prompts and parsers](langchain/1.1-prompts-and-parsers.ipynb)
#### 1.2. [LCEL](langchain/1.2-LCEL.ipynb)
#### 1.3. [Function calling / tool use + tagging](langchain/1.3-Tagging.ipynb)

#### 2.1. [Document loading](langchain/2.1-document_loading.ipynb)
#### 2.2. [Document splitting](langchain/2.2-splitting.ipynb)
#### 2.3. Indexing 
* [Indexing part 1](langchain/2.3-indexing1.ipynb)
* [Indexing part 2](langchain/2.3-indexing2.ipynb)

#### 2.4. [Retrieval & RAG](langchain/2.4-retrieval.ipynb)
#### 2.5. [Q&A chains](langchain/2.5-qa.ipynb)
#### 2.6. [Chat with memory](langchain/2.6-chat-with-memory.ipynb)
#### 2.7. [Conversational Agent](langchain/2.7-conversational-agent.ipynb)


## Challenges

### 1. Use your own data and build a simple RAG/LLM-app with the learnings from above
* Potentially use another Vector DB, such as [Pinecode](https://www.pinecone.io)

### 2. Add Self-query (initial classification step) to your LLM-app
* https://python.langchain.com/docs/modules/data_connection/retrievers/self_query/

### 3. Add Agent behaviour to your LLM-app (see sample 2.7 above)
* https://python.langchain.com/docs/use_cases/tool_use/agents/

### 4. Include use of other types of models, such as CLIP
* https://python.langchain.com/docs/integrations/text_embedding/open_clip/

### 5. Use local models
* https://python.langchain.com/docs/use_cases/question_answering/local_retrieval_qa/
* https://python.langchain.com/docs/integrations/text_embedding/self-hosted/



## References, docs and courses


### Prompting

* **[Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)** - see for instance:

    - [Strategy: Split complex tasks into simpler subtasks](https://platform.openai.com/docs/guides/prompt-engineering/strategy-split-complex-tasks-into-simpler-subtasks)
    - [Strategy: Give models time to "think"](https://platform.openai.com/docs/guides/prompt-engineering/strategy-give-models-time-to-think)

* **[OpenAI Cookbok](https://cookbook.openai.com)**

* **[OpenAI API Playground](https://platform.openai.com/playground)**
 
* **[Anthropic Prompt Library](https://docs.anthropic.com/claude/prompt-library)**

* **[Prompt Engineering Guide](https://www.promptingguide.ai/techniques)** - Good overview of prompting techniques

### Langchain

![LangChain](/images/langchain.png)

**[Chat with the Docs](https://chat.langchain.com)**

#### **Python**

* [Introduction](https://python.langchain.com/docs/get_started/introduction)

* [Use cases](https://python.langchain.com/docs/use_cases)

* [Cookbook](https://github.com/langchain-ai/langchain/tree/master/cookbook)

#### **JS/TS**

* [Introduction](https://js.langchain.com/docs/get_started/introduction)

* [Use cases](https://js.langchain.com/docs/use_cases)

* [Cookbook](https://github.com/langchain-ai/langchainjs/tree/main/cookbook)


### Tutorials

* LangChain 101 - https://github.com/IvanReznikov/DataVerse/tree/main/Courses/LangChain
    * Cheatsheet: https://pub.towardsai.net/langchain-cheatsheet-all-secrets-on-a-single-page-8be26b721cde

* https://github.com/gkamradt/langchain-tutorials
   * Good starting point: https://github.com/gkamradt/langchain-tutorials/blob/main/LangChain%20Cookbook%20Part%201%20-%20Fundamentals.ipynb


### DeepLearning.AI

![Wanna chat](/images/deeplearning.png)

#### Intro courses

* **[ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)**

* **[LangChain for LLM Application Development](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)**
  (uses older API)

#### Little deeper

* **[Building Systems with the ChatGPT API](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/)**

* **[LangChain: Chat with Your Data](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/)**
  (also partiall using older API)
 
* **[Functions, Tools and Agents with LangChain](https://www.deeplearning.ai/short-courses/functions-tools-agents-langchain/)**
  (Most up-to-date course on LangChain)
