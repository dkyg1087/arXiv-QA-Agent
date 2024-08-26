# arXiv QA Agent

This repository contains a QA agent that extracts information from arXiv papers and provides recommendations based on user queries. The agent utilizes the prequantized unslothed version LLaMA 3.1 8B instruct model with Retrieval-Augmented Generation (RAG) and a Chroma vector store to efficiently retrieve and recommend relevant papers. 

You can run it all on a Free Google Colab instance with a T4 GPU.

- Dataset: https://www.kaggle.com/datasets/Cornell-University/arxiv

- LLM: https://huggingface.co/unsloth/Meta-Llama-3.1-8B-Instruct-bnb-4bit

- llama-index: https://www.llamaindex.ai/

### Work in Progress

 - Make it a reAct Agent/Function calling agent.
 - Extend the reAct into a Structured Planning agent
 - Add tools to fetch actual pdf with the id.