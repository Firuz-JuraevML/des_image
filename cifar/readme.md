## Trained Models on CIFAR datasets
  
  ### CIFAR-10 
  | Model        | Accuracy | 
  | ------------ | ------------------ |
  | ResNet 18    | 94.79%     | 
  | ResNet 34    | 94.77%     | 
  | ResNet 50    | 95.30%     | 
  | ResNet 101   | 94.99%     | 
  | ResNet 152   | 94.60%     | 
  | DenseNet 121 | 95.06%     | 
  | DenseNet 161 | **95.43%** | 
  | DenseNet 169 | 95.10%     | 
  | DenseNet 201 | 95.17%     | 
  | VGG 11       | 91.94%     |
  | VGG 13       | 93.70%     | 
  | VGG 16       | 93.30%     | 
  | VGG 19       | 93.18%     | 
  | MobileNet V2 | 94.20%     | 
  | GoogLeNet    | 95.01%     | 
  | DLA          | 94.64%     |  
  | DPN 26       | 94.30%     | 
  | Inception V3 | 94.77%     | 
  | Xception     | 93.49%     | 
  
  Training parameters 
  | Parameter     | Value | 
  | ------------- | --------------- | 
  | epochs        | 200             | 
  | batch size    | 128             | 
  | learning rate | **0.01**        | 
  | image size    | 32x32           |  
  | device        | Tesla V100-SXM2-32GB | 
  
  ### The CIFAR-10 Dataset: 
  
  The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
  
  ---
  ### CIFAR-100  
  
  | Model        | Accuracy | 
  | ------------ | ------------------ | 
  | ResNet 18    | 75.94%   |
  | ResNet 34    | 76.72%   | 
  | ResNet 50    | 76.96%   |
  | ResNet 101   | 76.22%   | 
  | ResNet 152   | 74.88%   |
  | VGG 11       | 71.08%   | 
  | VGG 13       | 73.50%   | 
  | VGG 16       | 72.86%   | 
  | VGG 19       | 71.84%   | 
  | DenseNet 121 | 77.54%   |
  | DenseNet 161 | 79.05%   | 
  | DenseNet 169 | 78.67%   | 
  | DenseNet 201 | 78.63%   | 
  | MibileNet V2 | 69.44%   | 
  | Xception     | 74.67%   | 
  | Inception V3 | 77.12%   | 
  
  Training parameters 
  | Parameter     | Value | 
  | ------------- | --------------- | 
  | epochs        | 200             |
  | batch size    | 128             | 
  | learning rate | 0.01            |
  | image size    | 32x32           | 
  | device        | Tesla V100-SXM2-32GB |  
  
  ### The Papers of Implemented Networks 
  * VGG: [Very Deep Convolutional Networks for Large-Scale Image Recognition](https://arxiv.org/abs/1409.1556v6)
  * ResNet: [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385v1) 
  * DenseNet: [Densely Connected Convolutional Networks](https://arxiv.org/abs/1608.06993v5) 
  * MobileNetV2: [MobileNetV2: Inverted Residuals and Linear Bottlenecks](https://arxiv.org/abs/1801.04381) 
  * GoogLeNet: [Going Deeper with Convolutions](https://arxiv.org/abs/1409.4842v1)
  
