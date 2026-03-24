# NLP + GenAI Learning Guide

This document explains how to use the NLP + GenAI roadmap effectively. It is designed for learners who want to build strong foundations in Natural Language Processing while also becoming capable of developing modern Generative AI systems, including Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and AI agents.

The roadmap is structured into phases and day-wise topics. Each day focuses on a specific concept and its practical application.

---

## Duration and Expectations

- Total Duration: 4–5 weeks  
- Daily Effort: 2–4 hours  
- Daily Output: One Jupyter Notebook containing notes and implementation  

This roadmap is designed to be intensive and hands-on. Consistency and practical implementation are essential for achieving strong results.

---

## How to Use This Roadmap

Each day should be approached with the following workflow:

### Step 1: Study the Day’s Topic
Focus on understanding the concept from intuition to implementation. Do not rush through topics.

### Step 2: Learn Actively
Break down the topic into:
- What problem it solves
- How it works
- Where it is used in real systems

### Step 3: Implement in a Notebook
Create a Jupyter Notebook for each day and include:
- Clear explanations in your own words
- Clean and modular code
- Small experiments or variations

### Step 4: Build a Mini Task
Each day should include a small practical task or experiment to reinforce learning.

---

## Recommended Notebook Structure

Follow this structure for every notebook:

1. Intuition  
2. Core Concepts  
3. Interview Notes  
4. Implementation  
5. GenAI Mapping  
6. Mini Project  
7. Learnings  

---

## Roadmap

---

## Phase 1 — Text Processing and Tokenization

Goal: Understand how raw text is converted into machine-readable format and how modern systems process text.

### Day 1 — Text Preprocessing Basics
- Text normalization  
- Lowercasing, punctuation removal  
- Stopwords  
- When not to preprocess  

### Day 2 — Advanced Cleaning
- Unicode normalization  
- Handling emojis  
- URLs, numbers, special characters  
- Regex basics  

### Day 3 — Tokenization Fundamentals
- Word, sentence, and character tokenization  
- Token boundary challenges  
- Comparison of libraries such as spaCy and NLTK  

### Day 4 — Subword Tokenization
- Byte Pair Encoding (BPE)  
- WordPiece  
- SentencePiece  
- Why subword tokenization is used in LLMs  

### Day 5 — Vocabulary and OOV
- Vocabulary creation  
- Out-of-vocabulary problem  
- Token distribution  
- Zipf’s Law (intuitive understanding)  

### Day 6 — Practical Integration
- Comparing tokenizers  
- Inspecting tokenization in LLMs  
- Understanding token count and its impact  

---

## Phase 2 — Classical NLP

Goal: Build intuition for traditional NLP methods and understand when they are more efficient than LLMs.

### Day 7 — Bag of Words
- Concept  
- Limitations  

### Day 8 — TF-IDF
- Term Frequency  
- Inverse Document Frequency  
- Practical importance  

### Day 9 — Similarity and Search
- Cosine similarity  
- Document similarity systems  

### Day 10 — Naive Bayes
- Intuition  
- Use cases  

### Day 11 — Logistic Regression
- Core idea  
- Why it is a strong baseline  

### Day 12 — SVM and Comparison
- SVM intuition  
- Comparison with other models  

### Day 13 — Practical Project
- Spam classification system  
- Text similarity engine  

---

## Phase 3 — Embeddings

Goal: Understand how meaning is represented numerically and used in modern AI systems.

### Day 14 — Word2Vec
- CBOW and Skip-Gram  
- Semantic representations  

### Day 15 — GloVe and FastText
- Co-occurrence-based learning  
- Handling rare words  

### Day 16 — Embedding Applications
- Similarity  
- Clustering  
- Semantic search  

### Day 17 — Modern Embeddings
- Sentence transformers  
- Embedding APIs  
- Vector representations  

### Day 18 — Vector Search Systems
- FAISS and ChromaDB basics  
- Retrieval systems  

### Day 19 — Practical Project
- Build a semantic search engine  

---

## Phase 4 — Transformers

Goal: Develop a deep understanding of transformer architecture and LLM behavior.

### Day 20 — Attention Intuition
- Motivation behind attention  
- Context understanding  

### Day 21 — Self-Attention
- Query, Key, Value  
- Attention mechanism  

### Day 22 — Transformer Architecture
- Multi-head attention  
- Positional encoding  
- End-to-end flow  

### Day 23 — Model Types
- Encoder models (BERT)  
- Decoder models (GPT)  
- Encoder-decoder models (T5)  

### Day 24 — Training and Behavior
- Next token prediction  
- Masked language modeling  
- Model limitations  

### Day 25 — Fine-Tuning
- LoRA  
- Prompt tuning  
- Adapters  

### Day 26 — Practical Implementation
- Using transformer models  
- Running inference  
- Analyzing outputs  

---

## Phase 5 — GenAI Systems and AI Agents

Goal: Build real-world AI systems using LLMs, retrieval, and agents.

### Day 27 — Prompt Engineering
- Prompt structure  
- Few-shot and zero-shot learning  

### Day 28 — Retrieval-Augmented Generation
- Architecture  
- Workflow  

### Day 29 — Build RAG System
- Document processing  
- Embedding-based retrieval  
- LLM integration  

### Day 30 — AI Agents Basics
- Tool usage  
- Memory  
- Planning strategies  

### Day 31 — Build AI Agent
- Tool integration  
- Memory systems  

### Day 32 — Hybrid Systems
- Combining rules, ML, and LLMs  
- Decision strategies  

### Day 33 — Optimization
- Quantization  
- Distillation  
- Performance trade-offs  

### Day 34 — Final Project
- Build a complete AI system combining:
  - Retrieval  
  - Agents  
  - Fallback logic  

---

## Final Outcome

By completing this roadmap, you will be able to:

- Understand NLP from foundational concepts to modern LLMs  
- Build production-ready GenAI systems  
- Design retrieval-based and agent-based architectures  
- Optimize systems for performance and cost  
- Confidently approach NLP and GenAI interviews  

---