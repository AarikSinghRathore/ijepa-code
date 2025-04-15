#  i-JEPA — Image Joint Embedding Predictive Architecture

> A clean and educational implementation of Meta AI’s self-supervised learning framework: **i-JEPA**  
> Predicting latent image representations — not pixels — for scalable, efficient learning.

[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

##  What is i-JEPA?

**i-JEPA** (Image Joint Embedding Predictive Architecture) is a self-supervised learning model developed by **Meta AI** that predicts **latent representations** of masked image regions using context from the visible parts. Unlike pixel reconstruction models (e.g., MAE, BEiT), i-JEPA operates purely in **embedding space**, making it efficient and scalable.

>  **Paper**: [Self-supervised Learning from Images with a Joint-Embedding Predictive Architecture](https://arxiv.org/abs/2301.08243)

---

##  Core Ideas

- Learns image representations via **masked latent prediction**
- Uses a **Vision Transformer (ViT)** encoder
- No pixel-level loss — predictions happen in **representation space**
- Encourages better performance in **transfer learning**, **linear probing**, and **fine-tuning**

---

## Requirements
### 1. Python 3.8+

### 2. PyTorch ≥ 1.10

### 3. torchvision

### 4. timm

### 5. einops

---

##  Results (Demo)

| Task             | Accuracy (Top-1) | Backbone |
|------------------|------------------|----------|
| CIFAR-10 (probe) | 95.6%            | ViT-S    |
| STL-10 (probe)   | 89.2%            | ViT-B    |

---

##  References

- Original i-JEPA Paper: [arXiv:2301.08243](https://arxiv.org/abs/2301.08243)
- Meta AI Blog: [https://ai.facebook.com/blog/ijepa-self-supervised-learning](https://ai.facebook.com/blog/ijepa-self-supervised-learning)

---

## Author

Made with  by [Gourav Gangwar](https://github.com/AarikSinghRathore)

