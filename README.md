# 100 Days of Deep Learning

![Playlist](https://img.shields.io/badge/YouTube-84%20videos-red?logo=youtube)
![Framework](https://img.shields.io/badge/Framework-TensorFlow%20%7C%20Keras-orange)
![Language](https://img.shields.io/badge/Language-Python-blue)

My learning journey through CampusX's **100 Days of Deep Learning** playlist, from a single perceptron all the way to Transformers.

This repository is the Deep Learning stage of my path toward becoming an AI/ML Engineer:

**Machine Learning → Deep Learning → Generative AI → Agentic AI**

▶️ **Playlist:** [100 Days of Deep Learning by CampusX](https://www.youtube.com/playlist?list=PLKnIA16_RmvYuZauWaPlRTC54KxSNLtNn)

---

## The Learning Path

```
Perceptron → MLP & Backpropagation → Training & Optimization → CNN → RNN / LSTM / GRU → Attention & Transformers
```

The playlist has 84 videos. It starts from first principles and builds up one idea at a time, with code in Python using TensorFlow and Keras.

---

## What the Playlist Covers

### 1. Foundations and the Perceptron
- Course introduction and roadmap
- What is Deep Learning? Deep Learning vs Machine Learning
- Types of neural networks, history and applications of Deep Learning
- What is a Perceptron? Perceptron vs neuron, geometric intuition
- The Perceptron Trick: how to train a perceptron
- Perceptron loss function: hinge loss, binary cross-entropy, sigmoid
- The problem with the perceptron

*Why it matters:* every modern network is built from this one unit, and its limits explain why deeper networks were needed.

### 2. Multi-Layer Perceptron (MLP) and First ANN Projects
- MLP intuition and notation
- Forward propagation: how a neural network predicts an output
- **Project:** Customer Churn Prediction using ANN (Keras and TensorFlow)
- **Project:** Handwritten Digit Classification using ANN (MNIST)
- **Project:** Graduate Admission Prediction using ANN

*Why it matters:* MLPs can learn non-linear patterns, and these projects cover classification and regression end to end.

### 3. Loss Functions and Backpropagation
- Loss functions in Deep Learning
- Backpropagation Part 1 (The What), Part 2 (The How), Part 3 (The Why)
- MLP memoization
- Gradient Descent in neural networks: Batch vs Stochastic vs Mini-Batch
- Vanishing and exploding gradient problems

*Why it matters:* backpropagation is how a network learns, and understanding gradients explains why training sometimes fails.

### 4. Improving Neural Network Performance
- How to improve the performance of a neural network
- Early stopping
- Data and feature scaling in neural networks
- Dropout layers (theory and code for regression and classification)
- Regularization in Deep Learning
- Activation functions and ReLU variants
- Weight initialization techniques, including Xavier/Glorot and He
- Batch normalization
- Optimizers: Exponentially Weighted Moving Average, SGD with Momentum, Nesterov Accelerated Gradient, AdaGrad, RMSProp, Adam
- Hyperparameter tuning with Keras Tuner

*Why it matters:* this module is the practical toolbox for making networks train faster, more stably and with less overfitting.

### 5. Convolutional Neural Networks (CNN)
- What is a CNN? CNN vs the visual cortex
- The convolution operation
- Padding and strides
- Pooling layers
- Classic CNN architecture, end to end
- Comparing CNN vs ANN
- Backpropagation in CNN (two parts)
- **Project:** Cat vs Dog image classification
- Data augmentation
- Pretrained models in CNN, and what a CNN actually "sees"
- Transfer learning: feature extraction vs fine-tuning
- Keras Functional API

*Why it matters:* CNNs are the foundation of computer vision, and transfer learning makes strong image models possible with limited data.

### 6. Sequence Models: RNN, LSTM and GRU
- Why RNNs are needed, and the RNN architecture
- **Project:** Sentiment analysis with RNN
- Types of RNN
- Backpropagation Through Time (BPTT)
- Problems with RNN
- LSTM (three parts), including next-word prediction
- Gated Recurrent Unit (GRU)
- Deep RNNs: stacked RNNs, LSTMs and GRUs
- Bidirectional RNN

*Why it matters:* text, speech and time series are sequences, and LSTM/GRU solve the memory problems of the basic RNN.

### 7. Attention and Transformers
- A short history of Large Language Models
- Encoder-Decoder (sequence-to-sequence) architecture
- Attention mechanism, Bahdanau vs Luong attention
- Introduction to Transformers
- Self-attention: what it is, scaled dot-product attention, geometric intuition, why it is called "self"
- Multi-head attention
- Positional encoding
- Layer normalization
- Transformer architecture
- Masked self-attention
- Cross-attention
- Transformer decoder architecture
- Transformer inference

*Why it matters:* Transformers power today's Large Language Models, so this module is the bridge from Deep Learning to Generative AI.

---

## Key Ideas at a Glance

| Problem | Technique that addresses it |
|---|---|
| A single perceptron cannot learn non-linear patterns | Multi-Layer Perceptron |
| Networks must learn from their errors | Backpropagation and Gradient Descent |
| Gradients vanish or explode in deep networks | Better activations, weight initialization, batch normalization |
| The model overfits | Early stopping, dropout, regularization, data augmentation |
| Training is slow or unstable | Feature scaling, batch normalization, optimizers such as Adam |
| ANNs handle images poorly | Convolutional Neural Networks |
| Little data for an image task | Transfer learning |
| Data comes in sequences | RNN, then LSTM and GRU |
| Long-range context and parallel training | Attention and Transformers |

---

## Tools and Technologies

- Python
- TensorFlow and Keras
- Jupyter Notebook / Google Colab

---

## Acknowledgements

All lecture content and course structure belong to **Nitish Singh** and the **[CampusX](https://www.youtube.com/@CampusX-official)** team. This repository is my personal record of studying their playlist, and I recommend the original videos to anyone who wants to learn Deep Learning properly.

---

## About Me

I am **Hazrat Bilal**, a Computer Science student at the University of Engineering & Technology, Peshawar, building my path in AI, Machine Learning, Deep learning, Gen Ai and Agentic Ai.

🔗 GitHub: [BilalWazir033](https://github.com/BilalWazir033)

---

*Building Intelligence Today, Exploring the Future of AI Tomorrow.*
