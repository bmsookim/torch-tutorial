Torch-Tutorial
===================================================================================================
Basic Torch Tutorials for Deep Learning

Torch is a scientific computing framework based on Lua[JIT] with strong CPU and CUDA backends.

This repository will handle basic Torch implementations of FFNN(Feed Forward Neural Network), CNN(Convolutional Neural Network), RNN(Recurrent Neural Network), and fine-tuning pre-trained models from scratch.

![alt_tag](Torch/logo.png)

# Environments
This tutorial is based on
- One Titan-X(Pascal) local setting for single-GPU handling
- Two Titan-X(Pascal) server setting for multi-GPU handling

# Requirements
See the [installation instruction](INSTALL.md) for a step-by-step installation guide.
See the [server instruction](SERVER.md) for server setup.
- Install [Torch](http://torch.ch/docs/getting-started.html)
- Install [cuda-8.0](https://developer.nvidia.com/cuda-downloads)
- Install [cudnn v5.1](https://developer.nvidia.com/cudnn)

# Contents
- [Linear Regression](./01-LinearRegression/LinearRegression.ipynb)
- [Logistic Regression]()
- [Feedforward Neural Network]()
- [Convolutional Neural Network]()
- [Recurrent Neural Network]()
- [Fine-tuning pre-trained models]()
- [Basic GAN]()

# Getting Started
```bash
$ git clone https://github.com/meliketoy/Torch-Tutorial.git
$ luarocks install cutorch
$ luarocks install xlua
$ luarocks install optnet

# Install itorch notebook (Ubuntu)
$ sudo apt-get install libzmq3-dev libssl-dev python-zmq
$ git clone https://github.com/facebook/iTorch.git
$ cd iTorch
$ luarocks make
```
