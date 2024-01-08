---
draft: False
date: 2019-05-17
slug: curiosity-is-all-you-need
categories:
  - Reinforcement Learning
authors:
  - tshrjn
---

# RAG is more than just embedding search

With the advent of large language models (LLM), retrival augmented generation (RAG) has become a hot topic. However throught the past year of [helping startups](https://jxnl.co) integrate LLMs into their stack I've noticed that the pattern of taking user queries, embedding them, and directly searching a vector store is effectively demoware.

!!! note "What is RAG?"

    Retrival augmented generation (RAG) is a technique that uses an LLM to generate responses, but uses a search backend to augment the generation. In the past year using text embeddings with a vector databases has been the most popular approach I've seen being socialized.
