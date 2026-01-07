# Transformers and Large Language Models

## Companion Repository

This repository is a **study companion and practical implementation guide** for the book ***Transformers and Large Language Models***.

The goal of this project is to bridge the gap between **transformer theory** and **hands-on implementation of large language models (LLMs)** by providing:

* Clear explanations of transformer architecture and attention mechanisms
* Step-by-step derivations and pseudocode
* Python implementations from scratch and with libraries
* Visualizations to build intuition for LLM behavior
* Original exercises with worked solutions

> 📌 **Important note**: This repository does **not** contain the book itself, nor does it reproduce copyrighted content. All explanations, code, and exercises are original and written as a learning aid.

---

## 🎯 Who This Repository Is For

This repo is designed for:

* Students learning **transformers, NLP, or AI**
* Practitioners who want to **strengthen LLM foundations**
* Engineers preparing for **interviews involving transformers and LLMs**
* Researchers who want runnable examples of transformer models and attention mechanisms

If you have ever thought *“I know LLM APIs, but I want to understand what’s happening inside a transformer”*, this repository is for you.

---

## 🧠 Core Topics Covered

The repository follows a structure aligned with standard transformer and LLM curricula:

* **Foundations of Transformers** (self-attention, multi-head attention, positional encoding)
* **Transformer Architectures** (encoder, decoder, encoder-decoder)
* **Training Large Language Models** (pretraining, fine-tuning, transfer learning)
* **Attention Mechanisms** (scaled dot-product, cross-attention)
* **Sequence Generation** (autoregressive decoding, beam search, sampling)
* **Evaluation & Metrics** (perplexity, BLEU, ROUGE, accuracy)
* **Practical Applications** (text generation, summarization, question answering)

Each topic is treated with:

* Mathematical and computational rigor
* Hands-on Python examples
* Practical relevance for real-world NLP applications

---

## 📂 Repository Structure

```text
transformers-large-language-models/
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── 01-transformer-foundations/
│   ├── README.md
│   ├── self_attention.ipynb
│   ├── multihead_attention.ipynb
│   └── positional_encoding.ipynb
│
├── 02-transformer-architectures/
│   ├── encoder.ipynb
│   ├── decoder.ipynb
│   └── encoder_decoder.ipynb
│
├── 03-training-llms/
│   ├── pretraining.ipynb
│   ├── fine_tuning.ipynb
│   └── transfer_learning.ipynb
│
├── 04-attention-mechanisms/
│   ├── scaled_dot_product.ipynb
│   └── cross_attention.ipynb
│
├── 05-sequence-generation/
│   ├── autoregressive.ipynb
│   ├── beam_search.ipynb
│   └── sampling.ipynb
│
├── 06-evaluation-metrics/
│   ├── perplexity.ipynb
│   ├── bleu_rouge.ipynb
│   └── accuracy_metrics.ipynb
│
├── 07-practical-applications/
│   ├── text_generation.ipynb
│   ├── summarization.ipynb
│   └── question_answering.ipynb
│
└── utils/
    └── plotting.py
