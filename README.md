# Understanding Deep Learning: Notebook Solutions

> My worked solutions to the companion notebooks of Simon J. D. Prince's [**Understanding Deep Learning**](https://udlbook.github.io/udlbook/) (MIT Press, 2023). They cover the mathematics behind neural networks, from shallow networks and loss functions to backpropagation, regularisation and convolutional networks.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

Coursework for **Matemáticas para el Aprendizaje de Máquina** (Mathematics for Machine Learning), Universidad Nacional de Colombia.

## Contents

All notebooks are in [`Solution_Notebooks_understandingDL/`](Solution_Notebooks_understandingDL/).

| Chapter | Topic | Notebooks |
|---|---|---|
| 1–2 | Background maths, supervised learning | `1_1_BackgroundMathematics`, `2_1_Supervised_Learning` |
| 3 | Shallow neural networks | Shallow networks I & II, network regions, activation functions |
| 4 | Deep neural networks | Composing networks, clipping functions, deep networks |
| 5 | Loss functions | Least squares, binary cross-entropy, multiclass cross-entropy |
| 6 | Fitting models | Line search, gradient descent, SGD, momentum, Adam |
| 7 | Gradients & initialisation | Backpropagation in a toy model, backpropagation, initialisation |
| 8 | Measuring performance | MNIST-1D performance, bias–variance trade-off, double descent, high-dimensional spaces |
| 9 | Regularisation | L2, implicit regularisation, ensembling, Bayesian approach, data augmentation |
| 10 | Convolutional networks | 1D convolution, convolution for MNIST-1D, 2D convolution, down/upsampling, convolution for MNIST |

## How to run

```bash
git clone https://github.com/bermudez05/Understanding-DL---MPAM.git
cd Understanding-DL---MPAM
pip install numpy matplotlib torch jupyter
jupyter notebook
```

The notebooks also run directly in Google Colab.

## Related

These exercises supported the team project [Foundation Models in Medical Imaging (CheXzero & MI-Zero)](https://github.com/bermudez05/FM-s).

## Credits

The original notebooks are by Simon J. D. Prince ([udlbook](https://github.com/udlbook/udlbook)). The solutions are by **Laura Nicole Bermúdez Santa**.
