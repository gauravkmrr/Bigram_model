NanoGPT-X: Custom Transformer Model
Overview
NanoGPT-X is a custom transformer model developed using PyTorch, designed for efficient text generation. It features multi-head attention, feedforward layers, and layer normalization, tailored to operate within the constraints of limited computational resources.

Features
Multi-head attention mechanism for capturing various aspects of context.
Integration of positional encodings with token embeddings to maintain sequence order.
Efficient handling of computational resources for model training and inference.
Getting Started
To use NanoGPT-X, clone this repository to your local machine and follow the setup instructions below.

Prerequisites
Python 3.8 or later
PyTorch 1.8 or later
CUDA toolkit (optional, for GPU acceleration)

Installation
Clone the repository and install the dependencies:
git clone [repo-link]
cd bigram_model
pip install -r requirements.txt

Usage
To train the model with your dataset, follow these steps:

Prepare your dataset in a similar format as input.txt.
Run the training script
python bigram.py

