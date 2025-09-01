---
title: AutoMat
disableshare: true
summary: 
draft: false
hidemeta: false
weight: 15
---

The **AutoMat** project is a research effort focused on developing compressed neural representations of physically-based materials for real-time graphics applications. Its goal is to drastically reduce memory storage requirements for rendering while maintaining high visual fidelity, making it suitable for video games and interactive 3D graphics.

## Core Capabilities

- **Neural Texture Compression**: Learns compact material representations to replace dense texture maps.
  
- **Auto-Encoder Architectures**: Implements and compares VQ-VAE, convolutional, and MLP-based models for compression.
  
- **Compact Decoders**: Designs decoders smaller than encoders to enable real-time inference on graphics hardware.
  
- **Training Pipeline**: Provides scripts to train models from scratch (`train.py`) and evaluate reconstruction quality (`eval.py`).
  
- **Evaluation Metrics**: Benchmarks compression ratio, reconstruction fidelity, and inference speed.
  
- **Dataset Integration**: Supports multiple high-quality texture datasets (Hugging Face, AmbientCG, Disney Research).
  
- **Real-Time Integration**: Prepares decoders for use in real-time rendering engines and pipelines.

## Technologies Used

- **PyTorch**: Deep learning framework for model development and training.
  
- **Python**: Core programming language for experimentation and pipeline development.
  
- **NumPy & Matplotlib**: Tools for data preprocessing, visualization, and exploratory data analysis.
  
- **Hugging Face Datasets**: Provides open datasets for training and evaluation.
  
## Related Links

- [GitHub Repository](https://github.com/ChefSteveP/neural-texture-compression)
- [Weinreich et al. 2024 Paper](https://arxiv.org/2311.16121)
