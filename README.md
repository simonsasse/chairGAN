# DChairGAN

This is an educational project for the seminar "Cybersecuruty and AI" at the FU Berlin. The aim is to implement a GAN
and show the results in this README file.

- [ChairGAN](#chairgan)



## Overview

GANs are generative adversarial networks consisting of a discriminator and a generator network. This architecture was first
published by [Ian Goodfellow *et al* in 2014]( https://proceedings.neurips.cc/paper/2014/file/5ca3e9b122f61f8f06494c97b1afccf3-Paper.pdf).
Since then, GANs have been further researched and developed and are now state of the art in generative networks.
## Implementation
This implementation is implemented using the [tensorflow library](https://www.tensorflow.org) and is build along this
[tutorial by tensorflow](https://www.tensorflow.org/tutorials/generative/dcga). The MNIST dataset has been replaced with a
set of pictures of chaires taken from [kaggle](https://www.kaggle.com/arminajdehnia/antic-chairs). The pictures have a different
dimension and thus the code had to be adapted accordingly. 
## Results
The results are presented in a GIF shwoing the development of the generated images over time. Unfortunately, no results could be optained 
that showed chairs in any way.
## Discussion
GANs are hard to train, especially the vanilla GANs published by [Ian Goodfellow *et al* in 2014]( https://proceedings.neurips.cc/paper/2014/file/5ca3e9b122f61f8f06494c97b1afccf3-Paper.pdf). Reasons for this are modecollabs and XXXX. Additionally, it is very hard 
to keep the learning progress of the two networks balanced. If this is not the case, mode collabs or XXX can happen.
Furthermore, the DChairGAN was trained on an Macbook Air m1. There is no stable implementation of tensorflow or Pytorch
that uses the GPU of the m1 chip. So the training had to be done on the CPU only and thus was not very fast. 