# corr_tf
An implementation of the FlowNetC correlation layer in tensorflow

The FlowNetC architecture (https://arxiv.org/abs/1504.06852) uses a novel cross correlation layer
This is an implementation of that cross correlation layer in tensorflow, with CUDA support.

REQUIRES: Tensorflow >= 1.1, CUDA >=  8.0, CMAKE >= 2.8

BUILDING:

$ mkdir build

$ cd build

$ cmake ..

$ make

TESTING:

$ python correlation_tests.py
