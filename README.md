# Custom ResNet for Food-101 Classification

**PyTorch | Deep Learning Coursework**

This project implements a deep learning pipeline for image classification on the Food-101 dataset, using a custom-built ResNet architecture. All core layers, including Conv2D, MaxPool2D, Linear, and BatchNorm2D, were implemented from scratch using low-level PyTorch operations (e.g., `unfold`, `matmul`) without relying on high-level modules like `torch.nn.Conv2d`.

---

## 🔍 Highlights

- Implemented **Conv2D, MaxPool2D, Linear, and BatchNorm2D** layers using pure PyTorch
- Designed a **custom ResNet-style network** with six residual blocks and global average pooling
- Trained on the **Food-101** dataset with 101 diverse food categories
- Used **data augmentation**, **cosine annealing scheduler**, and **early stopping**
- Evaluated model on **out-of-distribution hotdog dataset** for robustness assessment

---

## 🧠 What I Learned

- Low-level implementation of deep learning layers
- Custom architecture design and training strategies
- Techniques for model regularization and learning rate scheduling
- Analyzing learned features and performance with visualization

