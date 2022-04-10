<h1 align = "center">Latte</h1>

## Introduction

**Latte** (**L**et's **A**bsorb **T**orch **T**echnology **E**legantly) is a self-designed deep learning framework working on CPU, the package name shows tribute to Caffe while the inner structure is inspired by the PyTorch framework.

```
.
├── latte
│   ├── __init__.py
│   ├── functional.py
│   ├── nn.py
│   ├── optim.py
│   ├── tensor.py
│   └── utils
│       ├── __init__.py
│       └── data.py
└── lattevision
    ├── __init__.py
    ├── datasets.py
    └── transforms.py
```

Latte packages some basic modules, like **tensor** defines the basic data structure, **nn** together with functional provides necessary classes and functions for neural network, **optim** includes some classical optimization methods, and **utils.data** is for dataset and data loader. All the interfaces are referred to the official documentation of PyTorch.

Furthermore, what torchvision is to torch, lattevision is to latte. It includes some requisite modules for computer vision tasks. To be more specific, **transforms** contains some transformation functions for image processing, **datasets** implements the downloading and loading of MNIST dataset for now.

All the features above are implemented using **numpy** package.

## Reference

1. [mytorch](https://github.com/SimonMcDonnell/mytorch) : A small library for creating deep learning models from scratch.
2. [Computational Graph](https://pub.towardsai.net/nothing-but-numpy-understanding-creating-neural-networks-with-computational-graphs-from-scratch-6299901091b0) : Understanding & Creating Neural Networks with Computational Graphs from Scratch.

