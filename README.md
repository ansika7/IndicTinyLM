# **IndicTinyLM**

IndicTinyLM is a compact, sample-efficient language modeling project designed for **next-token prediction (causal language modelling)** in **Telugu and Marathi**, with support for extending to additional Indic languages. The project is optimized for **low-resource settings**, enabling strong performance even when labeled data is limited.

IndicTinyLM uses a shared **Indic subword tokenizer** to ensure efficient vocabulary coverage across multiple Indian languages. The repository provides a modular pipeline for tokenization, dataset preparation, training, and evaluation using perplexity on held-out test sets.

---

## **✨ Features**

* Lightweight decoder-only Transformer models
* Shared Indic tokenizer for efficient multilingual support
* Causal Language Modeling objective
* Fine-tuning and evaluation modules
* Designed for low-resource language scenarios
* Clean, modular, and extendable codebase

---

## **📊 Evaluation**

The primary evaluation metric is **perplexity** on held-out test sets.
Language-wise evaluation is supported for Telugu and Marathi.

---




