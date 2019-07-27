# Steamroll

Tool for losslessly compressing/decompressing images via dimension reduction.

## How it works 

Uses th <a href="https://github.com/tensorflow/tfjs-tsne">tfjs-tsne</a> library to do dimensionality reduction on the <a href="https://en.wikipedia.org/wiki/MNIST_database">MNIST data set</a>. Specifically, it takes 10000 images of digits, resize them to 10x10px and use T-SNE to organize them in two dimensions.

Note that tfjs-tsne requires WebGL 2 support and thus will not work on certain devices, mobile devices especially. Currently it best works on desktop devices.

## Usage
```sh
yarn
yarn watch
```
## Example
[Click here!](https://storage.googleapis.com/tfjs-examples/tsne-mnist-canvas/dist/index.html)
