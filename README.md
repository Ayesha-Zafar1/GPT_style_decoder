# Implementing GPT_style_decoder and Llama style decoder
In this assignment, I implemented components of two well-known Large Language Model (LLM) architectures:  Additionally, I implemented the Byte-Pair Encoding (BPE) algorithm, an essential text processing technique for tokenization in language models. You will see how its different from a typical naive tokenizer.

# GPT-style & LLaMA Decoder Architectures
This project implements core components of large language models (LLMs) inspired by GPT and LLaMA. It focuses on decoder-only transformer architectures and includes a custom Byte-Pair Encoding (BPE) tokenizer for subword-level text processing. The goal is to provide a transparent and educational look into how modern generative AI systems process and generate human language.

By building these models from scratch, the project offers a deeper understanding of how LLMs work beyond the use of pre-trained APIs. It can serve as a learning tool or a foundation for research and development in natural language processing (NLP) and generative AI.

# Features

- Implementation of decoder blocks inspired by GPT and LLaMA.

- Manual construction of key components: self-attention, multi-head attention, and feedforward networks.

- Custom implementation of Byte-Pair Encoding (BPE) for subword tokenization.

- Lightweight, modular, and built with readability and experimentation in mind.

# Motivation

Transformer-based LLMs are central to many applications in AI, from chatbots to summarization tools. However, these models are often used without a clear understanding of their internal mechanics. This project addresses that gap by reconstructing the essential parts of LLM decoders and their tokenization logic in a simplified and interpretable way.

# Technologies Used

- Python

- PyTorch

- NumPy

- Custom-built BPE tokenizer (no external libraries)

# Example Use Cases

- Understanding how decoder-only LLMs like GPT and LLaMA process text.

- Building educational tools or research prototypes for NLP tasks.

- Customizing or optimizing transformer-based models for specific domains.
