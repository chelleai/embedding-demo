---
title: Document Retrieval with Embeddings
author: Joshua Cook, Chelle AI
theme: "Berkeley"
---

# Introduction

![](img/xhibit.jpeg)

---

## Importance of Document Retrieval

- Powerful, cheap strategy for building new product features
- Here a **document** is any textual record
   - e.g. a Hotel in a travel context
   - e.g. a Job in a job search context
   - e.g. an Influencer 

Dirt-cheap recommender system. Use Document Retrieval to generate a list of candidates. Then use distance and metadata to rank them and then use. 

---

![](img/scribd.png)
https://tech.scribd.com/blog/2021/embedding-based-retrieval-scribd.html

---

![](img/linkedin.png)
https://engineering.linkedin.com/blog/2023/how-linkedin-is-using-embeddings-to-up-its-match-game-for-job-se

---

## Traditional Methods and Their Limitations

- **Keyword-based Searching**: Explicitly matching terms
- **Boolean Queries**: Using logical operators (AND, OR, NOT)

**Limitations**:

- Lack of semantic understanding
- Low relevance
- Manual optimization needed

---

## Retrieval-Augmented Generation

![](img/85i167.jpg)

---

![](img/rag.png)
https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview

---

## Retrieval-Augmented Generation

- for open-domain question answering (QA) e.g. "Chat" with GPT
- the benefits of:
  - traditional information retrieval (IR)
   - with the power of large language models (LLMs)
- RAG uses a pre-trained LLM (GPT4) to generate answers to a given question
- but first uses an IR system to retrieve relevant documents for context 

---

# The Basics of Embeddings

## What are Embeddings?

- Converting words to points
- Captures meaning in the math, especially distance and direction

# Classic Example

## Example: Man <-> Woman is similar to King <-> Queen

![](img/manwoman.png)

---

## Difference from Traditional Methods

- Understands semantic context
- Example: Differentiates "Apple" the company from "apple" the fruit

# Also

![](img/cheapest.png)

# Pricing

![](img/pricing.png)

# Demo 

# Brainstorming: Textual Datasets

(Three minutes, Groups of three)

Think of as many different textual datasets as you can three minutes.

# Brainstorming: Building Context

(Five minutes, Groups of three)

Pick one set.

- Think of a context you can build with that data
   - What field or area or discipline or topic can this data be used to support GPT in answering questions?
- Name that context.
- Come up with five questions that you think GPT could answer give that context.

# Brainstorming: Present

Share your context and questions with the cohort.