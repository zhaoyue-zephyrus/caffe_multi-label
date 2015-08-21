# caffe_multi-label
This is a multi-label version of Caffe which is developed by the Berkeley Vision and Learning Center ([BVLC](http://bvlc.eecs.berkeley.edu)) and community contributors.

The framework is based on the 2nd release candidate of Caffe 1.0.(See here: https://github.com/BVLC/caffe/releases), since the master branch of Caffe is under severe modification right now.

caffe.proto has been modified to allow multi-label.

A simple demo on MNIST:
1. Download mnist
 > ./data/mnist/get_mnist.sh
2. Convert mnist
 > ./examples/mnist/create_mnist.sh
3. Train the LeNet model
 > ./examples/mnist/train_lenet.sh
