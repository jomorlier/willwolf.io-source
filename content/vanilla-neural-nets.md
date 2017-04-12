Title: Vanilla Neural Nets
Date: 2016-05-15 21:27
Author: admin
Category: Uncategorized
Tags: neural networks
Slug: vanilla-neural-nets
Status: published

To better understand neural networks, I've decided to implement several
from scratch.

Currently, this project contains a feedforward neural network with
sigmoid activation functions, and both mean squared error and
cross-entropy loss functions. Because everything is an object, adding
future activation functions, loss functions, and optimization routines
should be a breeze.

In addition to being highly compose-able, this project is highly
readable. Too often, data science code is a veritable circus of
variables named "wtxb", six-times-nested for loops, and 80-line
functions. The code within is both explicit and straightforward; few
readers should be left wondering: "what the f\*ck does that variable
mean?"

Code can be found
[here](https://github.com/cavaunpeu/vanilla-neural-nets). An example
[notebook](http://nbviewer.jupyter.org/github/cavaunpeu/vanilla-neural-nets/blob/master/examples/mnist.ipynb)
is included. This is an ongoing project: I intend to add more loss
functions, activation functions, convolutional and recurrent neural
networks, and other optimization improvements in due time.