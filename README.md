# PepperLeaves-DiseaseDetection-Classifier
### Classification Problem that either pepper leaves are healthy or affected by bacteria
In this problem we have to perform classification. Our objective is to classify the healthy and 
bacterial peeper leaves images. We have the provided dataset at kaggle .In order to achieve 
this goal we trained our models on two different architectures one is AlexNet and other is 
our own classifier. At first, we have trained both model on given input data. The input data 
is imbalanced that’s why we get some issues of overfitting and we didn’t get accurate 
results on unseen data. To solve this issue we modify the data to make it balance in such a 
way that both classes get the equal or same data samples. As a result our accuracy get 
improved and now we are having good results on unseen data as well.
## Overview
The nature of this project is classification problem. Our goal is to distinguish healthy peeper 
leaves and bacterial peeper leaves images. For this purpose we have used different 
classifier. As this is image classification problem so we are using AlexNet CNN architecture 
as AlexNet showed that deep convolutional neural network can be used for solving image 
classification. In addition to this AlexNet was first utilized in the public setting when it won 
the ImageNet Large Scale Visual Recognition Challenge (ILSSVRC 2012 contest) on 
classification 1.2 million images. Moreover we have also define our own classifier to solve 
this problem, our classifier was much simpler than the AlexNet. In the given dataset we have 
997 bacterial images and 1478 healthy images.
