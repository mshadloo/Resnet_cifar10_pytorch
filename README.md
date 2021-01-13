# ResNet Implementation of CIFAR10 in Pytorch
In this repo, I implemented ResNet for CIFAR10 as described in the [original paper](https://arxiv.org/abs/1512.03385). I load and normalize CIFAR10 training and test datasets using torchvision. The training dataset contains 50K images and the test dataset contains 10K images.

I compare ResNet20 and ResNet32 with 20-layer and 32-layer plain networks on CIFAR10. As you can see in the plain network with increasing layers the performance dropped while in ResNet with increasing the layer, the network outperforms.

![test error on the plain network](/images/plain_test_error.png)


