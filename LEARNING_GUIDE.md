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

Goal: Understand how language is converted into structured input before any model processes it.

### Day 1 — Text Preprocessing Foundations
- Text normalization  
- Lowercasing  
- Removing punctuation  
- Stopwords  
- Stemming  
- Lemmatization  
- Why preprocessing matters  
- When NOT to preprocess  

### Day 2 — Advanced Cleaning and Regex
- Unicode normalization  
- Handling emojis  
- Handling URLs  
- Handling numbers  
- Handling special characters  
- Regex for text processing  
- Building a preprocessing pipeline  

### Day 3 — Tokenization Fundamentals
- Word tokenization  
- Sentence tokenization  
- Character tokenization  
- Token boundary problems  
- NLTK vs spaCy tokenization  

### Day 4 — Subword Tokenization (LLM Foundation)
- Byte Pair Encoding (BPE)  
- WordPiece  
- SentencePiece  
- Unigram Language Model tokenizer  
- Why LLMs use subword tokenization  

### Day 5 — Vocabulary and Text Statistics
- Vocabulary construction  
- OOV (Out-of-vocabulary problem)  
- Token distribution  
- Zipf’s Law  
- Vocabulary size trade-offs  

### Day 6 — N-grams and Language Modeling Basics
- Unigram, Bigram, Trigram  
- N-gram language models  
- Next word prediction  
- Basic probability estimation  
- Applications in search and correction  

### Day 7 — Practical Integration
- Compare tokenizers  
- Analyze token distribution  
- Tokenization impact on LLM cost  
- Build a preprocessing + tokenization pipeline  

---

## Phase 2 — Classical NLP Modeling

Goal: Learn how NLP systems worked before deep learning and understand when they are still useful.

### Day 8 — Bag of Words
- Representation  
- Sparse vectors  
- Limitations  

### Day 9 — TF-IDF (Important)
- Term Frequency  
- Inverse Document Frequency  
- Why TF-IDF works  
- Applications  

### Day 10 — Similarity Systems
- Cosine similarity  
- Euclidean distance  
- Document similarity systems  

### Day 11 — Text Classification Models
- Naive Bayes  
- Multinomial vs Bernoulli  
- Pipeline: TF-IDF → Classifier  

### Day 12 — Logistic Regression and SVM
- Logistic regression for text  
- Decision boundary intuition  
- SVM concept  
- Model comparison  

### Day 13 — Sequence Labeling Basics (Conceptual Understanding Only)
- POS tagging  
- Named Entity Recognition  
- Hidden Markov Models  
- CRF intuition  

### Day 14 — Classical NLP Project
- Spam classifier  
- Document similarity system  
- Intent classifier  

---

## Phase 3 — Embeddings and Representation Learning

Goal: Understand how models capture meaning numerically.

### Day 15 — Word2Vec
- CBOW  
- Skip-Gram  
- Vector space meaning  

### Day 16 — GloVe and FastText
- Co-occurrence matrices  
- Character n-grams  
- Handling rare words  

### Day 17 — Embedding Applications
- Semantic similarity  
- Clustering  
- Retrieval systems  

### Day 18 — Modern Embeddings
- Sentence embeddings  
- Embedding APIs  
- Embedding pipelines  

### Day 19 — Vector Databases
- FAISS  
- ChromaDB  
- Indexing and retrieval  

### Day 20 — Semantic Search Project
- Build semantic document search system  

---

## Phase 4 — Transformers and LLMs

Goal: Understand how modern language models actually work.

### Day 21 — Attention Mechanism
- Why attention was introduced  
- Context problem in NLP  

### Day 22 — Self-Attention
- Query  
- Key  
- Value  
- Attention calculation  

### Day 23 — Transformer Architecture
- Multi-head attention  
- Positional encoding  
- Feed-forward layers  
- Residual connections  
- Layer normalization  

### Day 24 — Transformer Model Types
- Encoder models (BERT)  
- Decoder models (GPT)  
- Encoder-decoder models (T5)  

### Day 25 — Training Objectives
- Masked Language Modeling  
- Next Token Prediction  
- Model behavior and hallucinations  

### Day 26 — Fine-Tuning Techniques
- Full fine-tuning  
- LoRA  
- Adapters  
- Prompt tuning  

### Day 27 — Practical Transformer Usage
- Running models  
- Understanding outputs  
- Model comparison  

---

## Phase 5 — Modern GenAI Systems and AI Agents

Goal: Build production-ready AI systems.

### Day 28 — Prompt Engineering
- Prompt design  
- Few-shot vs zero-shot  

### Day 29 — Retrieval-Augmented Generation
- Architecture  
- Retrieval pipeline  
- Chunking strategies  

### Day 30 — Build RAG System
- Documents → embeddings → retrieval → LLM  

### Day 31 — AI Agents
- Tool usage  
- Memory systems  
- Planning vs reactive agents  

### Day 32 — Agent Implementation
- Build tool-using AI agent  

### Day 33 — Hybrid NLP Systems
- Regex + ML + LLM pipelines  
- When not to use LLMs  

### Day 34 — Evaluation
- Precision  
- Recall  
- F1 score  
- BLEU  
- ROUGE  
- Perplexity (intuition)  

### Day 35 — Optimization and Production
- Quantization  
- Distillation  
- Cost optimization  
- System design decisions  

### Day 36 — Final System Project
- Build complete AI assistant system:
  - RAG  
  - Agent  
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