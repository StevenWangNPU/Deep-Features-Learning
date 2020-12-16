# Train Cifar10, ImageNet, STL10, Caltech101 with Pytorch
Learning some deep convolution features for classification and clustering.
## Installation
* Python 3.6 
* Pytorch 1.7

## Accuracy
* **Cifar10** 512-dimensional feature vectors in MATLAB format.

| Model         | Parameter                                                | Accuracy     |  KNN          | Downlaod     | 
| ------------- |:-------------:                                           | -----:       |  -----:       | -----:       | 
|  Resnet18     |bs = 128, Lr = 0.1, CosineAnnealingLR(Tmax = 200)         | 91.90%       |  91.90%       | [228_epoch.pth](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) \|  [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) | 
|  Resnet101    |bs = 128, Lr = 0.1, CosineAnnealingLR(Tmax = 200)         | 92.42%       |  92.42%       | [191_epoch.pth](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md), [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) |
|  星期三        | G1007                                                    | 18:30        |  18:30        |  18:30       |         

