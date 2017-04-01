# About

SqueezeNet-complexByPass by chainer

# Paper

[160224 SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and <0.5MB model size](https://arxiv.org/abs/1602.07360)

# Model

squeezeNet with simple-bypass

# How to run
git clone git@github.com:amazarashi/squeeze-chainer.git

cd ./squeeze-complexByPass-chainer

python main.py -g 1

# Inspection

### dataset
Cifar10 [link](https://www.cs.toronto.edu/~kriz/cifar.html)

### Result

 - Optimizer momentumSGD (0.01[customized for batch normalization] ~ scheduling lineary )

![accuracy](https://github.com/amazarashi/squeeze-complexByPass-chainer/blob/develop/result/log/accuracy.png "")

![loss](https://github.com/amazarashi/squeeze-complexByPass-chainer/blob/develop/result/log/loss.png "")
