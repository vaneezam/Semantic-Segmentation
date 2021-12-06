# Semantic-Segmentation
Cityscape dataset was used to perform Segmentation containing 11 classes namely, : Sky", "Building", “Pole", "Road", "Pavement", "Tree", "SignSymbol”, “Fence”, “Car", "Pedestrian”, “Bicyclist". The code Implements 2 CNN architectures as BACKBONE : </br>
1. VGG16 (16 layers)</br>
2. InceptionRestnetv2 </br>
U-Net was used as a baseline architecture in both cases. Python's Segmentation Model Library was used for the task, the link for which is : https://github.com/qubvel/segmentation_models

The models are compared in terms of Accuracy and Training Time. </br></br>

The code further includes:</br>
##### 1. Data Augmentation using https://github.com/nikhilroxtomar/Data-Augmentation-for-Semantic-Segmentation-Dataset

The accuracies achieved are as below: </br>
|       Model       | Train Accuracy| Test Accuracy |
| ----------------- | ------------- | ------------- |
|       VGG16       |     96.41%    |     97.59%    |
|InceptionRestnetv2 |     96.23%    |     97.37%    |

#### Conclusion
VGG16 and InceptionResnetv2 showed similar performance in terms of accuracy with 97.59% accuracy for VGG16 and 97.37% accuracy for InceptionResnetv2, 
however VGG16 had less number of parameters and it took less time to train than InceptionResnetv2, with 145 sec training time for VGG16 and 401 sec for InceptionResnetv2.
