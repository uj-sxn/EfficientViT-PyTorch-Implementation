# EfficientViT: Memory Efficient Vision Transformer 🧠

## 📖 Overview
This project is a custom implementation of the **EfficientViT** architecture, designed to perform high-accuracy image classification on resource-constrained devices. Unlike traditional Vision Transformers (ViTs) that suffer from quadratic complexity, this model utilizes **Cascaded Group Attention (CGA)** to maintain computational efficiency without sacrificing spatial resolution.

## ⚙️ Tech Stack
* **Framework:** PyTorch 2.x
* **Dataset:** CIFAR-100 
* **Tools:** Google Colab, `thop` (for FLOPs counting), Matplotlib.

## 🚀 Key Features Implemented
* **Patch Embedding Layer:** Custom 2D convolutional projection for tokenization.
* **Cascaded Group Attention (CGA):** Hierarchical attention mechanism to reduce FLOPs.
* **Efficiency Metrics:** Achieved ~1.5 GFLOPs per forward pass with only ~21M parameters.

## 📊 Results
The model was trained from scratch on CIFAR-100 and evaluated using ROC curves and Attention Maps.

* **Macro-Average AUC:** 0.85 (demonstrating strong class discrimination).
* **Inference Speed:** ~1651 images/sec on CPU.



## 🔧 How to Run

Clone the repository, install the folders and run the project code.
