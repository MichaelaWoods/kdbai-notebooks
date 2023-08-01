# <img src="images/kdbai.png" height="60" width="159" > Notebooks

The example [KDB.AI](https://kdb.ai) notebooks provided aim to demonstrate examples of the use of the KDB.AI vector database in a number of scenarios ranging from getting started guides to industry specific use-cases.

> :warning: **Notebook Execution Environment**: Currently the notebooks presented here can only be used by users engaged in the [KDB.AI Early Access Program](https://kx.com/kdb-ai-early-access/). 


## What is KDB.AI?

KDB.AI is a time-based vector database that allows developers to build scalable, reliable and real-time applications by providing advanced search, recommendation and personalization for Generative AI applications. KDB.AI is a key component of full-stack Generative AI applications that use Retrieval Augmented Generation (RAG).

Built by KX the creators of kdb+, KDB.AI provides users with the ability to combine unstructured vector embedding data with structured time-series datasets to allow for hybrid use-cases which benefit from the rigor of conventional time-series data analytics and the usage patterns provided by vector databases within the Generative AI space.

## What does it support?

KDB.AI supports the following feature set:

- Multiple index types: Flat, IVF, IVFPQ and HNSW.
- Multiple distance metrics: Euclidean, Inner-Product, Cosine.
- Top-N and metadata filtered retrieval
- Python and REST Interfaces

Additionally for testing the following integrations are presently included

- [langchain](https://github.com/kxsystems/langchain)
- [chatgpt-retrieval-plugin](https://github.com/KxSystems/chatgpt-retrieval-plugin)

## Notebooks

The following notebooks and sections are included within this repository at this time:

### Getting Started

- [Quickstart](notebooks/getting-started/Quickstart.ipynb): A quick introduction to the KDB.AI APIs

### Use-Cases

- [Flight Climb Analysis](notebooks/use-cases/Flight_Climb_Analysis.ipynb): Analysis comparing temporal aircraft sensor data to identify optimizations and make informed decisions to enhance aircraft performance.
- [Crypto Semantic Search](notebooks/use-cases/Crypto_Semantic_Search.ipynb): Using KDB.AI to ask questions and get information across both financial data and unstructured Twitter data.
- [Crypto Sentiment Analysis](notebooks/use-cases/Crypto_Sentiment_Analysis.ipynb): Using KDB.AI to analysis the correlation between the sentiment of tweets and price movements of bitcoin.
- [Crypto Strategy](notebooks/use-cases/Crypto_Strategy.ipynb): Using KDB.AI to generate a momentum trading strategy.

### Integrations

- [ChatGPT Retrieval Plugin](notebooks/integrations/ChatGPT_Retrieval_Plugin_QA.ipynb): Example showing a question and answer session using a ChatGPT retrieval plugin using KDB.AI Vector Database.
- [Langchain](notebooks/integrations/LangChain_QABot.ipynb): Example showing a question and answer session using a Langchain integration with the KDB.AI Vector Database.
