# Train Cifar10, ImageNet, STL10, Caltech101 with Pytorch
Learning some deep convolution features for classification and clustering.
## Installation
* Python 3.6 
* Pytorch 1.7

## Accuracy
* **Cifar10:** 512-dimensional feature vectors in MATLAB format.  Fetch code: idea

| Model           | Parameter setting                                        | Accuracy     |  KNN          | Download     | 
| :-------------: |:-------------:                                           | :-----:      |  :-----:      | :-----:      | 
|  Resnet18       |bs = 256, Lr = 0.1, CosineAnnealingLR(Tmax = 300)         | 88.11%       |  82.82%       | [299_epoch.pth](https://pan.baidu.com/s/1axGz6wYNdW4u3QCDlx31sQ) \|  [128-D](https://pan.baidu.com/s/1QLYAzigv0oIq2p1yiAc4LQ) | 
|  Resnet101      |bs = 128, Lr = 0.1, CosineAnnealingLR(Tmax = 200)         | 92.42%       |  88.78%       | [191_epoch.pth](https://pan.baidu.com/s/1ZIE3Ujx1zfOtfUAf-QPVyw) \| [2048-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) |
|  VGG16          |bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)   | 90.49%        |  90.49%       | [253_epoch.pth](https://pan.baidu.com/s/1kCg4hUXcdB9Fj4ShL4BDKg) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) |      
|  VGG19          | bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 90.04%       | 90.04%        | [254_epoch.pth](https://pan.baidu.com/s/1XUbVcFKQuzXHqvTaSPql3g) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) |     
|  Senet18          | bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 91.93%      | 91.93%        | [291_epoch.pth](https://pan.baidu.com/s/1lvgOMXZpkbUh00wtL1PGdg) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) | 
|  Senet18          | bs = 128, Lr = 0.1, CosineAnnealingLR(Tmax = 300)  | 92.41%      | 92.41%        | [297_epoch.pth](https://pan.baidu.com/s/1ciaqaJ7VjBoxk4xei_eVvA) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) | 
|  Densenet121       | bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 91.88%     | 91.88%        | [284_epoch.pth](https://pan.baidu.com/s/1XUbVcFKQuzXHqvTaSPql3g) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) |  
|  Densenet121       | bs = 128, Lr = 0.1, CosineAnnealingLR(Tmax = 300)                       | 92.51%     | 92.51%        | [289_epoch.pth](https://pan.baidu.com/s/13gPpbmBSdYCJOJTPC3nrtw) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) |  

* **STL10:** 512-dimensional feature vectors in MATLAB format.

| Model           | Parameter setting                                        | Accuracy     |  KNN          | Download     | 
| :-------------: |:-------------:                                           | :-----:      |  :-----:      | :-----:      | 
|  Resnet18       |bs = 128, Lr = 0.1, CosineAnnealingLR(Tmax = 200)         | 91.90%       |  88.39%       | [228_epoch.pth](https://pan.baidu.com/s/1a8yZH5KrPVxt8j8dGCYhTw) \|  [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) | 
|  VGG16          |bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)   | 90.49%        |  90.49%       | [253_epoch.pth](https://pan.baidu.com/s/1kCg4hUXcdB9Fj4ShL4BDKg) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) |      
|  VGG19          | bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 90.04%       | 90.04%        | [254_epoch.pth](https://pan.baidu.com/s/1XUbVcFKQuzXHqvTaSPql3g) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) |     
|  Senet18          | bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 91.93%      | 91.93%        | [291_epoch.pth](https://pan.baidu.com/s/1lvgOMXZpkbUh00wtL1PGdg) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) | 
|  SVHN          | bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 91.93%      | 91.93%        | [291_epoch.pth](https://pan.baidu.com/s/1lvgOMXZpkbUh00wtL1PGdg) \| [256-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) | 

* **ImageNet:** 512-dimensional feature vectors in MATLAB format.

| Model           | Parameter setting                                        | Accuracy     |  KNN          | Download     | 
| :-------------: |:-------------:                                           | :-----:      |  :-----:      | :-----:      | 
|  Resnet18       |bs = 128, Lr = 0.1, CosineAnnealingLR(Tmax = 200)         | 91.90%       |  88.39%       | [228_epoch.pth](https://pan.baidu.com/s/1a8yZH5KrPVxt8j8dGCYhTw) \|  [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) | 
|  VGG16          |bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)   | 90.49%        |  90.49%       | [253_epoch.pth](https://pan.baidu.com/s/1kCg4hUXcdB9Fj4ShL4BDKg) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) |      
|  VGG19          | bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 90.04%       | 90.04%        | [254_epoch.pth](https://pan.baidu.com/s/1XUbVcFKQuzXHqvTaSPql3g) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) |     
|  Senet18          | bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 91.93%      | 91.93%        | [291_epoch.pth](https://pan.baidu.com/s/1lvgOMXZpkbUh00wtL1PGdg) \| [512-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) | 
|  SVHN          | bs = 128, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 91.93%      | 91.93%        | [291_epoch.pth](https://pan.baidu.com/s/1lvgOMXZpkbUh00wtL1PGdg) \| [256-D](https://github.com/StevenWangNPU/Deep-Features-Learning/edit/main/README.md) | 
