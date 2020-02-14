# Steamroll &#x1F539;

Tool for losslessly compressing images via dimension reduction. 

![](https://github.com/lucylow/steamroll/blob/master/steamroll%20screens.png)
*Screenshot. From https://lucylow.github.io/steamroll/*
---

## How it works 

Uses the <a href="https://github.com/tensorflow/tfjs-tsne">tfjs-tsne</a> library to do dimensionality reduction on the <a href="https://en.wikipedia.org/wiki/MNIST_database">MNIST data set</a>. Specifically, it takes 10000 images of digits, resize them to 10x10px and use T-SNE to organize them in two dimensions.

---

## Usage

```sh
yarn
yarn watch
```
---
