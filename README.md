# CNN Transfer Learning and Image Retrieval

This repository contains Python programs of CNN Transfer Learning and Image Retrieval System similarly like the one on which Google Lens works.

**1.Image Retrieval System**
This is designed using Convolutional Neural Network VGG16. It displays four relevant images relevant to the input image. 

**2.Transfer Learning**
In this program, firstly AlexNet used for training and evaluation on the datset and then VGG16 used for trainig and evaluation of the same dataset.


Following are the trained plots for Alexnet having test accuracy of 99.14% achieved.
![image](https://github.com/Ramal-Abbas/cnntransferlearningimageretrieval/assets/86521852/3d7f8742-cfc0-47cd-b14c-898f6a3fc808)

The confusion matrix for Alexnet is as follows



![image](https://github.com/Ramal-Abbas/cnntransferlearningimageretrieval/assets/86521852/1c480d00-9a99-4c56-81a6-f46ac2bbce37)

Following are the trained plots for VGG16 having test accuracy of 97.53% achieved.
![image](https://github.com/Ramal-Abbas/cnntransferlearningimageretrieval/assets/86521852/ed0b22c0-f79a-40f0-b9aa-14681fbfa443)






The confusion matrix for VGG16 is as follows



![image](https://github.com/Ramal-Abbas/cnntransferlearningimageretrieval/assets/86521852/feae0b05-a7b6-4092-b163-950a9c5b393d)



These both Alexnet and VGG16 trained on 10 epochs.

# Parameters for Alexnet are as follows


Total params: 23994499 (91.53 MB)
Trainable params: 23994179 (91.53 MB)
Non-trainable params: 320 (1.25 KB)


# Parameters for VGG16 are as follows


Total params: 40932163 (156.14 MB)
Trainable params: 26217475 (100.01 MB)
Non-trainable params: 14714688 (56.13 MB)
