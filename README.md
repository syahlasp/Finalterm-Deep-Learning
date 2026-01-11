# Member :
1. Syahla Setia Pratiwi (1103220028)
2. Auldy Ranayu (1103223216)
   
# Finalterm-Deep-Learning
## Fine-Tuning Hugging Face Models: The Three Paradigms of Transformers

The primary objective of this project is to implement an end-to-end Deep Learning pipeline using state-of-the-art **Transformer-based architectures**. By working with the Hugging Face ecosystem, we explore how different model architectures (Encoder-only, Seq2Seq, and Decoder-only) are optimized for specific Natural Language Processing (NLP) challenges.

## Project Overview
This project is divided into three major tasks, each representing a core paradigm in modern NLP:

1.  **Task 1 (Encoder):** Fine-tuning **DistilBERT** for **Natural Language Inference (NLI)** using the MultiNLI dataset.
2.  **Task 2 (Seq2Seq):** Fine-tuning **T5-Small** for **Generative Question Answering** using the SQuAD dataset.
3.  **Task 3 (Decoder):** Fine-tuning **Phi-2** for **Abstractive Summarization** using the XSum dataset, implemented via **LoRA (Low-Rank Adaptation)**.

## Models and Matrix

### A. Task 1: Encoder Model (DistilBERT)
- **NLP Problem:** Text Classification / NLI.
- **Description:** Leverages bidirectional context to determine if a hypothesis is entailed, neutral, or contradictory to a premise.
- **Metric:** **Accuracy**.

### B. Task 2: Seq2Seq Model (T5-Small)
- **NLP Problem:** Generative Question Answering.
- **Description:** An encoder-decoder framework that transforms a context and question into a generated answer string.
- **Metric:** **Loss / Generative Evaluation**.

### C. Task 3: Decoder-Only LLM (Phi-2)
- **NLP Problem:** Abstractive Summarization.
- **Description:** A 2.7B parameter model fine-tuned using **FP16 precision** and **LoRA** to compress news articles into one-sentence summaries.
- **Metric:** **Training Loss / ROUGE**.

## Navigate the Repository
- [Notebook](./finalterm_deep_learning.ipynb)
