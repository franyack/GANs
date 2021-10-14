# GANs with Keras and TensorFlow

This project implement Generative Adversarial Networks (GANs) using Keras and Tensorflow.

Generative Adversarial Networks were first introduced by Goodfellow et al. in their 2014 paper, [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661). 
These networks can be used to generate synthetic (i.e., fake) images that are perceptually near identical to their 
ground-truth authentic originals.

All the understanding and scripts are based on <b>Adrian Rosebrock</b> and his website [pyimagesearch](https://www.pyimagesearch.com/). So, thanks Adrian!

## Index:

- [About project](#about-project)
- [Environment setup](#environment-setup)
- [References](#references)

## About project

![technology Python](https://img.shields.io/badge/technology-python-red.svg)

## Environment setup

- Configure your development environment. It is highly recommended to use pyenv, so you can manage your python projects easily. More information [here](https://github.com/pyenv/pyenv-virtualenv)

- Once you have your environment ready, you must install requirements. To do this, in the root of this project, execute:

    ```
    pip install -r requirements.txt
    ```

- That's all! Yoy could run a python script. For example:

    ```
    python dcgan_fashion_mnist.py --output output 
    ```

## References

- [Intro to Generative Adversarial Networks (GANs)](https://www.pyimagesearch.com/2021/09/13/intro-to-generative-adversarial-networks-gans/)
- [GANs with Keras and TensorFlow](https://www.pyimagesearch.com/2020/11/16/gans-with-keras-and-tensorflow/)


