# Transformers from Scratch

A comprehensive implementation of the Transformer architecture from first principles, built with educational clarity and production-quality code.

---

## Overview

This project provides a ground-up implementation of the Transformer model introduced in the paper *Attention Is All You Need* by Vaswani et al.

The goal of this repository is to:

* Understand how Transformers work internally
* Rebuild the architecture step-by-step from scratch
* Provide clean, modular, and reusable implementations
* Serve as both an educational resource and experimentation playground

---

## Features

* ✨ Clean and well-documented implementation of Transformer components
* 🔧 Modular architecture for easy customization and experimentation
* 📚 Educational focus with detailed comments and explanations
* 🚀 Production-quality code structure and organization
* 🧠 Built entirely from first principles without relying on high-level abstractions

---

## Project Status

🚧 **Currently Under Development**

This project is actively being improved with:

* Additional Transformer variants
* Training pipelines
* Optimization techniques
* Better documentation and examples
* Research experiment support

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

* Python 3.8+
* PyTorch 1.9+
* NumPy

---

## Installation

```bash
git clone https://github.com/tokeniyi/transformers-from-scratch.git
cd transformers-from-scratch
pip install -r requirements.txt
```

---

## Quick Start

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

Run an example script:

```bash
python examples/train_demo.py
```

---

## Architecture

The implementation includes:

### Multi-Head Attention

Parallel attention mechanisms that allow the model to focus on different parts of the input sequence simultaneously.

### Feed-Forward Networks

Position-wise fully connected neural networks applied after attention layers.

### Embeddings & Positional Encoding

Token embeddings combined with positional information to preserve sequence order.

### Encoder & Decoder Stacks

Full Transformer encoder and decoder layers with residual connections and layer normalization.

---

## Project Structure

```bash
transformers-from-scratch/
├── models/               # Core transformer implementations
├── components/           # Reusable building blocks
├── examples/             # Usage examples and demos
├── tests/                # Unit and integration tests
├── notebooks/            # Experimental notebooks
├── README.md
└── requirements.txt
```

---

## Learning Goals

This repository is designed to help developers:

* Understand self-attention mathematically and practically
* Learn how encoder-decoder architectures work
* Explore sequence modeling and NLP fundamentals
* Experiment with Transformer modifications and optimizations

---

## Roadmap

Planned additions include:

* [ ] Training loop implementation
* [ ] Dataset preprocessing utilities
* [ ] GPT-style autoregressive models
* [ ] BERT-style encoder models
* [ ] Flash Attention experiments
* [ ] Mixed precision training
* [ ] Model benchmarking
* [ ] Visualization tools for attention maps

---

## Contributing

Contributions are welcome!

If you'd like to contribute:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

Bug reports, suggestions, and discussions are also appreciated.

---

## License

This project is licensed under the MIT License.

```text
MIT License
```

---

## References

* *Attention Is All You Need* — Vaswani et al., 2017
* *The Illustrated Transformer* — Jay Alammar
* PyTorch Documentation

---

## Author

Developed by Okeniyi Treasure Olubori.

* GitHub: https://github.com/tokeniyi

---

## Contact

Questions, suggestions, or feedback?

Feel free to:

* Open an issue
* Submit a pull request
* Reach out through GitHub

---

**Last Updated:** May 2026
**Status:** Active Development
