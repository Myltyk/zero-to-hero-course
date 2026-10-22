# zero-to-hero-course

# Neural Networks: Zero to Hero (course)

This repository tracks my hands-on progress through Andrej Karpathy's masterclass **["Neural Networks: Zero to Hero"](https://karpathy.ai)**. 

## 🛠️ Personal Extensions (Lecture 1)
While replicating the core `micrograd` autograd engine, I extended the base `Value` class with my own implementations of:
* **ReLU** activation function and its custom backward pass.
* **Leaky ReLU** (`alpha=0.01`) to handle the dying neuron problem.
* **Gradient Accumulation** (`+=`) to properly compute derivatives for reused nodes.

## 📂 Project Structure
* `01_micrograd/` — Scalar autograd library & basic MLP (Completed with extensions)


## 🙏 Acknowledgments
Deepest gratitude to **Andrej Karpathy** for creating this incredible, bottom-up educational series. The core concepts and base architecture belong to him. This repository is my personal space for practicing, extending, and mastering the material.
