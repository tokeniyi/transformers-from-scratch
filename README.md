# Transformers from Scratch

> A complete educational implementation of the Transformer architecture built entirely from first principles using PyTorch.

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-1.9+-red)
![Status](https://img.shields.io/badge/Status-Active%20Development-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## Overview

This repository contains a ground-up implementation of the Transformer architecture introduced in the landmark paper:

**“Attention Is All You Need” — Vaswani et al. (2017)**

The primary goal of this project is to deeply understand how Transformers work internally by rebuilding every major component manually instead of relying on high-level abstractions.

This project focuses on:

* Understanding self-attention mathematically and programmatically
* Recreating encoder-decoder architectures from scratch
* Building reusable Transformer components
* Experimenting with modern optimization techniques
* Providing educational and production-quality implementations

Whether you're learning deep learning, studying NLP systems, or researching Transformer architectures, this repository is designed to serve as both a learning resource and an experimentation playground.

---

# Features

* ✨ Clean and highly readable codebase
* 🧠 Transformer implementation from first principles
* 🔧 Modular and extensible architecture
* 📚 Educational comments and explanations throughout the code
* 🚀 Production-style project structure
* ⚡ PyTorch-based implementation
* 🧪 Designed for experimentation and research
* 📈 Future support for benchmarking and optimization experiments

---

# Current Implementations

The repository currently includes implementations of:

* Multi-Head Self Attention
* Scaled Dot-Product Attention
* Positional Encoding
* Token Embeddings
* Feed-Forward Networks
* Residual Connections
* Layer Normalization
* Encoder Blocks
* Decoder Blocks
* Full Transformer Architecture

---

# Project Status

🚧 **Actively Under Development**

This project is continuously evolving with ongoing improvements, refactoring, experiments, and additional model implementations.

Current development includes:

* Training pipelines
* Better modularization
* Optimization experiments
* Research tooling
* Improved testing coverage
* Performance benchmarking

---

# Installation

Clone the repository:

```bash
git clone https://github.com/tokeniyi/transformers-from-scratch.git
cd transformers-from-scratch
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Requirements

* Python 3.8+
* PyTorch 1.9+
* NumPy

Optional (recommended):

* CUDA-compatible GPU
* Jupyter Notebook

---

# Quick Start

Example usage:

```python
from models.transformer import Transformer

model = Transformer(
    vocab_size=10000,
    d_model=512,
    num_heads=8,
    num_layers=6,
    d_ff=2048,
    max_seq_length=512
)

print(model)
```

Run an example training/demo script:

```bash
python examples/train_demo.py
```

---

# Project Structure

```bash
transformers-from-scratch/
│
├── models/               # Core transformer models
├── components/           # Reusable transformer building blocks
├── examples/             # Example scripts and demos
├── tests/                # Unit and integration tests
├── notebooks/            # Research and experimentation notebooks
├── utils/                # Helper utilities
├── README.md
└── requirements.txt
```

---

# Transformer Architecture

The implementation follows the original Transformer encoder-decoder architecture.

## Multi-Head Attention

Allows the model to attend to different parts of the sequence simultaneously using parallel attention heads.

## Feed Forward Networks

Position-wise fully connected neural networks applied independently to each token representation.

## Positional Encoding

Injects sequence-order information into token embeddings since Transformers lack recurrence.

## Residual Connections & Layer Normalization

Improves gradient flow, stabilizes training, and enables deeper architectures.

## Encoder & Decoder Stacks

Full stacked Transformer blocks implementing attention, normalization, and feed-forward operations.

---

# Learning Objectives

This repository is designed to help developers:

* Understand how self-attention works internally
* Learn the mathematics behind Transformers
* Build deep learning architectures from scratch
* Explore NLP sequence modeling
* Experiment with Transformer optimizations
* Gain practical PyTorch experience

---

# Roadmap

Planned additions include:

* [ ] Training loop implementation
* [ ] Dataset preprocessing utilities
* [ ] GPT-style autoregressive models
* [ ] BERT-style encoder models
* [ ] Flash Attention experiments
* [ ] KV Cache implementation
* [ ] Mixed precision training
* [ ] Attention visualization tools
* [ ] Distributed training support
* [ ] Model benchmarking suite
* [ ] Tokenizer implementations
* [ ] Inference optimization

---

# Future Goals

Long-term goals for this project include:

* Reimplementing modern Transformer variants
* Building efficient inference systems
* Exploring scaling laws
* Experimenting with memory-efficient attention
* Implementing research papers from scratch
* Creating educational deep learning resources

---

# Contributing

Contributions are welcome and greatly appreciated.

If you'd like to contribute:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Commit your updates
5. Submit a pull request

Bug reports, suggestions, discussions, and improvements are all encouraged.

---

# References

* *Attention Is All You Need* — Vaswani et al., 2017
* *The Illustrated Transformer* — Jay Alammar
* PyTorch Documentation
* Stanford CS224N
* Hugging Face Transformers Documentation

---

# License

This project is licensed under the MIT License.

```text
MIT License
```

---

# Author

Developed and maintained by **Okeniyi Treasure Olubori**

### GitHub

https://github.com/tokeniyi

I actively work on AI engineering, machine learning systems, and software engineering projects focused on building practical and educational technologies.

Some repositories are still actively being developed locally and may not yet be publicly available.

---

# Support & Feedback

If you find this project useful:

* ⭐ Star the repository
* 🍴 Fork the project
* 🐛 Report issues
* 💡 Suggest improvements
* 🤝 Contribute to development

---

# Contact

For questions, collaborations, or discussions:

* Open an issue
* Submit a pull request
* Reach out through GitHub

---

*Last Updated: May 2026*
*Status: Active Development*
