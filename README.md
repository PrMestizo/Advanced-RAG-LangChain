# Advanced RAG control flow with LangGraph🦜🕸:
Implementation of Reflective RAG, Self-RAG & Adaptive RAG tailored towards production-oriented applications with LangGraph🦜🕸️.

![Arquitectura Advance-Rag](assets/langgraph_advance_rag.png)

## Features
* **Refactored Notebooks:** The original LangChain notebooks have been refactored to enhance readability, maintainability, and usability for developers.
* **Production-Oriented:** The codebase is designed with a focus on production readiness, allowing developers to seamlessly transition from experimentation to deployment.
* **Test Coverage:** Comprehensive test coverage ensures the reliability and stability of the application, enabling developers to validate their implementations effectively.
* **Documentation:** Detailed documentation and branches guides developers through setting up the environment, understanding the codebase, and utilizing LangGraph effectively.

## Environment Variables
To run this project, you will need to add the following environment variables to your .env file

```
PYTHONPATH=/{YOUR_PATH_TO_PROJECT}/Advanced-RAG-LangChain
```

```
OPENAI_API_KEY=<your-openai-api-key>
```
How to get you OpenAI API Key https://platform.openai.com/account/api-keys

```
TAVILY_API_KEY=<your-tavily-api-key>
```
How to get you Tavily API Key https://docs.mindmac.app/how-to.../internet-browsing/get-tavily-key

## Run Locally
Clone the project

```
git clone https://github.com/PrMestizo/Advanced-RAG-LangChain.git
```

Go to the project directory

```
cd Advanced-RAG-LangChain
```

Install dependencies

```
poetry install
```

Start the flask server

```
poetry run app.py
```



