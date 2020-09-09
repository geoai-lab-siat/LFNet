# LFNet: Lightweight Fire and Smoke Detection for Uncertain Surveillance Environment

## 1. Training and Testing data

a). Download the dataset form https://pan.baidu.com/s/1OU0B0tQ6tsbI3oC2J6omDg password：dpkq, and the files are named as 'train.rar. and 'test.rar'.

Figure 1: Representative images of fire, smoke and normal from the proposed datasets with their descriptions.



## 2. The structure of LFNet

Figure 2: The architecture of LFNet. LFNet conceptually consists of three sequential modules (skeleton feature module, main feature extraction module and predicting module), which is constructed by common convolution layers, bottleneck building blocks, parametric rectified linear unit, group normalization.



## 3. Performance on testing data
|               |  map  | size (Mb) |
| ------------- |:-------------:| -------------:|
| LFNet   | 0.619  |      22.5 |
| SSD   | 0.411  |      91.6 |
| Yolo v3 | 0.553 | 235 |
| Yolo v4 | 0.379 | 245.3 |
| m2det | 0.264 | 227 |
| faster rcnn | 0.296 | 108 |


## 4. Contact
1. If you ask for related code or have any problems of this project, you can email to chuanshengw516@gmail.com or jinxing.hu@siat.ac.cn

