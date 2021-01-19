# Train Cifar10, ImageNet, STL10, Caltech101 with Pytorch
Learning some deep convolution features for classification and clustering.
## Installation
* Python 3.6 
* Pytorch 1.7

## Accuracy
* **Cifar10:** 128-dimensional feature vectors in MATLAB format.  Fetch code: idea

| Model           | Parameter setting                                        | Accuracy     |  KNN          | Download     | 
| :-------------: |:-------------:                                           | :-----:      |  :-----:      | :-----:      | 
|  ResNet18       |bs = 256, Lr = 0.01, CosineAnnealingLR(Tmax = 300)        | 88.11%       |  82.82%       | [299_epoch.pth](https://pan.baidu.com/s/1axGz6wYNdW4u3QCDlx31sQ) \|  [128-D](https://pan.baidu.com/s/1QLYAzigv0oIq2p1yiAc4LQ) | 
|  VGG16          |bs = 256, Lr = 0.01, CosineAnnealingLR(Tmax = 300)        | 87.77%       |  80.16%      | [221_epoch.pth](https://pan.baidu.com/s/1t7CZvr_0_qwxwcOPKC8Sbg) \| [128-D](https://pan.baidu.com/s/1Vz8GpRzJQRNE1Xi9LKwgMQ) |          
|  SeNet18        | bs = 256, Lr = 0.01, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 91.09%      | 87.40%        | [241_epoch.pth](https://pan.baidu.com/s/193v8JTK6iOL2SSfwY0M8vw) \| [128-D](https://pan.baidu.com/s/1b4IWPsP8nIy7RQRct3C5mg) | 
| SVHN            | bs = 256, Lr = 0.01, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 84.95%      | 75.82%        | [297_epoch.pth](https://pan.baidu.com/s/1dSt4Qi4qaWYaFhYbeNFC1A) \| [128-D](https://pan.baidu.com/s/16RV1IioJANlpmswIs33ISg) | 
|  DenseNet121    | bs = 256, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)   | 91.88%     | 88.41%        | [232_epoch.pth](https://pan.baidu.com/s/1MzJtOeYIJEYWWrr7sWZ38A) \| [128-D](https://pan.baidu.com/s/1Rdj8RCTSWULPoz5M_rgDaA) |  
|  GoogleNet      | bs = 256, Lr = 0.01, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 92.51%     | 92.51%        | [165_epoch.pth](https://pan.baidu.com/s/1kpXTROa7cnLzWDRM4qLVRg) \| [128-D](https://pan.baidu.com/s/1wLymyPY8mLWqm39SrCVMCQ) |  

* **STL10:** 128-dimensional feature vectors in MATLAB format.

| Model           | Parameter setting                                        | Accuracy     |  KNN          | Download     | 
| :-------------: |:-------------:                                           | :-----:      |  :-----:      | :-----:      | 
|  ResNet18       |bs = 256, Lr = 0.01, CosineAnnealingLR(Tmax = 300)        | 88.11%       |  82.82%       | [299_epoch.pth](https://pan.baidu.com/s/1axGz6wYNdW4u3QCDlx31sQ) \|  [128-D](https://pan.baidu.com/s/1QLYAzigv0oIq2p1yiAc4LQ) | 
|  VGG16          |bs = 256, Lr = 0.01, CosineAnnealingLR(Tmax = 300)        | 87.77%       |  80.16%      | [221_epoch.pth](https://pan.baidu.com/s/1t7CZvr_0_qwxwcOPKC8Sbg) \| [128-D](https://pan.baidu.com/s/1Vz8GpRzJQRNE1Xi9LKwgMQ) |          
|  SeNet18        | bs = 256, Lr = 0.01, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 91.09%      | 87.40%        | [241_epoch.pth](https://pan.baidu.com/s/193v8JTK6iOL2SSfwY0M8vw) \| [128-D](https://pan.baidu.com/s/1b4IWPsP8nIy7RQRct3C5mg) | 
| SVHN            | bs = 256, Lr = 0.01, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 84.95%      | 75.82%        | [297_epoch.pth](https://pan.baidu.com/s/1dSt4Qi4qaWYaFhYbeNFC1A) \| [128-D](https://pan.baidu.com/s/16RV1IioJANlpmswIs33ISg) | 
|  DenseNet121    | bs = 256, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)   | 91.88%     | 88.41%        | [232_epoch.pth](https://pan.baidu.com/s/1MzJtOeYIJEYWWrr7sWZ38A) \| [128-D](https://pan.baidu.com/s/1RX3R0_ehhnbtSSL7tkTVLQ) |  
|  GoogleNet      | bs = 256, Lr = 0.01, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 92.51%     | 92.51%        | [165_epoch.pth](https://pan.baidu.com/s/1kpXTROa7cnLzWDRM4qLVRg) \| [128-D](https://pan.baidu.com/s/111Tf7gpTg55wTL60gwizqQ) | 

* **ImageNet-10:** 128-dimensional feature vectors in MATLAB format.

| Model           | Parameter setting                                        | Accuracy     |  KNN          | Download     | 
| :-------------: |:-------------:                                           | :-----:      |  :-----:      | :-----:      | 
|  ResNet18       |bs = 256, Lr = 0.01, CosineAnnealingLR(Tmax = 300)        | 88.11%       |  82.82%       | [299_epoch.pth](https://pan.baidu.com/s/1axGz6wYNdW4u3QCDlx31sQ) \|  [128-D](https://pan.baidu.com/s/1QLYAzigv0oIq2p1yiAc4LQ) | 
|  VGG16          |bs = 256, Lr = 0.01, CosineAnnealingLR(Tmax = 300)        | 87.77%       |  80.16%      | [221_epoch.pth](https://pan.baidu.com/s/1t7CZvr_0_qwxwcOPKC8Sbg) \| [128-D](https://pan.baidu.com/s/1Vz8GpRzJQRNE1Xi9LKwgMQ) |          
|  SeNet18        | bs = 256, Lr = 0.01, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 91.09%      | 87.40%        | [241_epoch.pth](https://pan.baidu.com/s/193v8JTK6iOL2SSfwY0M8vw) \| [128-D](https://pan.baidu.com/s/1b4IWPsP8nIy7RQRct3C5mg) | 
| SVHN            | bs = 256, Lr = 0.01, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 84.95%      | 75.82%        | [297_epoch.pth](https://pan.baidu.com/s/1dSt4Qi4qaWYaFhYbeNFC1A) \| [128-D](https://pan.baidu.com/s/16RV1IioJANlpmswIs33ISg) | 
|  DenseNet121    | bs = 256, Lr = 0.1, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)   | 91.88%     | 88.41%        | [232_epoch.pth](https://pan.baidu.com/s/1MzJtOeYIJEYWWrr7sWZ38A) \| [128-D](https://pan.baidu.com/s/1RX3R0_ehhnbtSSL7tkTVLQ) |  
|  GoogleNet      | bs = 256, Lr = 0.01, MultiStepLR(optimizer, [100, 200, 250], gamma=0.1)  | 92.51%     | 92.51%        | [165_epoch.pth](https://pan.baidu.com/s/1kpXTROa7cnLzWDRM4qLVRg) \| [128-D](https://pan.baidu.com/s/111Tf7gpTg55wTL60gwizqQ) |  
