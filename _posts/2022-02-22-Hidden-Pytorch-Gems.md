---
layout: post
title: "Hidden Pytorch Gems"
date: 2022-02-22
---

Turns out that you can do a lot of cool stuff with forward and backward hooks in PyTorch! Some relevant examples can be found at this [https://medium.com/the-dl/how-to-use-pytorch-hooks-5041d777f904](Medium post).

Forward hooks are called during the forward pass of a layer. If you save the output of the forward pass, you get the intermediate feature ouput by that layer.

Backward hooks are called during the backward pass. These can help save or manipulate gradients (eg. gradient clipping).
