# About

Experiments in [sequence to sequence learning (seq2seq)](https://towardsdatascience.com/sequence-to-sequence-learning-e0709eb9482d) with [recurrent neural networks (RNN)](https://en.wikipedia.org/wiki/Recurrent_neural_network) for automated document conversion, in [pytorch](https://pytorch.org/), using [jupyter notebooks](https://jupyter.org/).

## Setup

Using [Anaconda](https://www.anaconda.com) makes things easy: use the `Python 3.x` [command line installer](https://www.anaconda.com/products/individual).

After downloading and [installing](https://docs.anaconda.com/anaconda/install/), execute these commands inside the `(base)` environment (the last one is optional, but useful if using [AWS](https://aws.amazon.com/)):

```sh
conda upgrade conda
conda update --all
conda install pytorch torchvision -c pytorch
conda install -c conda-forge awscli 
```
