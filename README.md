# Simple Transformer

Learning and understanding transformers by building one from scratch.

## What We Built

A transformer encoder based on DistilBERT, built from scratch in PyTorch. Currently used for sentiment classification (positive / negative).

## Topics Covered

- Tensors, gradients, `nn.Module` in PyTorch
- Tokenization with HuggingFace
- Word and positional embeddings
- Self-attention and multi-head attention
- Feed-forward network, layer normalization, residual connections
- Loading pretrained weights
- Visualizing attention weights

## Setup

```bash
pip install torch transformers jupyterlab matplotlib numpy
```

Download the pretrained weights:

```bash
wget "https://tubcloud.tu-berlin.de/s/GfEoq4r8Sgb2727/download/distilbert.pt" -O distilbert.pt
```

## Notebook

`test.ipynb` — full transformer built step by step.
