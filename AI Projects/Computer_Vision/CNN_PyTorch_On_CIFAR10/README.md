# CNN PyTorch On CIFAR10
## Abstract
This project aims to create a CNN for image classification with evaluation being done on the [CIFAR10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html). It was done as a course project for CSE 5368 Neural Networks.
## Data
The data used to train and test the model is the [CIFAR10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html).  
The dataset consists of 60,000 32x32 color images in 10 classes, evenly distributed.  
Ten thousand images are test images.
## Other Tasks In This Notebook
This notebook also covers plotting the training accuracy and training loss of each model.  
Other models/methods used are also covered at the end of the notebook.
## Conclusions
The third model's architecture provided better accuracy results. It used BatchNorm2D in lieu of LayerNorm. The number of out_channels in each conv layer were also increased from previous models.
```Citations:
Learning Multiple Layers of Features from Tiny Images, Alex Krizhevsky, 2009.```