# MSEE19006_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# Dataset
The dataset can be downloaded from the following link,

https://drive.google.com/drive/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR

Models are trained on the Resnet 18 and VGG16.
The Each network's last FC layers were changed according to the roll number criteria.
# Task 1
## VGG model transfer learning using only FC layers,
the Link to the trained model is as followed,
https://drive.google.com/open?id=1YtRJDngj9ka42IJHaMB7xF9vUXe00EiG
The confusion Matrix and F1 score for model is as followed,

###### Test Dataset

Accuracy of the network: 93 %

   True Positive  531       False Positive  84 

   True Negative  868       False Negative  17

F1 score :  0.9145019052803484

######Validation Dataset

Accuracy of the network: 86 %

   True Positive  458      False Positive  157 
   
   True Negative 833       False Negative  52

F1 score :  0.8885333333333333

###### Training Dataset

Accuracy of the network: 90 %

   True Positive  4087       False Positive  832 

   True Negative  6739       False Negative  342

F1 score : 0.8744

## VGG with Drop Out 
Trained Model download Link is here,https://drive.google.com/open?id=1WIoyq0GaFuVgrYdMW7BcEDihBfvfk9sS
The confusion matrox and accuracy of the dataset are as followed,
##### Test Dataset

Accuracy of the network: 93 %

   True Positive  545    False Positive  70 

   True Negative  864    False Negative  21

F1 score : 0.9229725

###### Validation Dataset

Accuracy of the network: 87 %

   True Positive  493     False Positive  122
 
   True Negative  818    False Negative  67

F1 score :0.8391

###### Training Dataset

Accuracy of the network: 90 %

   True Positive  4215    False Positive  704 

   True Negative  6585    False Negative  496

F1 score : 0.8754

## Resnet with only FC layers trained
The trained model can be downloaded from the link https://drive.google.com/open?id=1nSSnk1mMBG4UXbmIMyFOdQ12MiLV3pqr,
The confusion matrix and accuracy for Network is as followed,

Test data

Accuracy of the network: 91 %

   True Positive  522    False Positive  93 

   True Negative  843    False Negative  42

F1 score :  0.8854961832061069

Validation data

Accuracy of the network: 83 %

   True Positive  465    False Positive  150 

   True Negative  788    False Negative  97

F1 score :  0.7901444350042481

Training Data

Accuracy of the network: 86 %

   True Positive  3884    False Positive  1035 

   True Negative  6452    False Negative  629

F1 score :  0.823579304495335
# Task 2
## VGG16 Last convolution + FC layer
The task is trained using trainable last convolution layer and fully connected layers.
The link to model is https://drive.google.com/open?id=1-DI0iQS6bselNcS5d-SnRTvQxeCt3cnQ
The confusion matrix for the model is 




## Resnet Last convolution ( Single) + FC layer
The ResNet network last convolutional layer and the FC layer trained. The network is trained using Adam optimizer with a batch size of 128 for Epochs. The network shows superior results in comparison to the previous model. The loss and accuracy plots for the models are as followed,
Link https://drive.google.com/open?id=1XtU1p5GMyeXfVUgpBWISHAVveqdsN1QA
The confusion matrix is as followed,

Test Dataset

Accuracy of the network: 92 %

   True Positive  584    False Positive  31 

   True Negative  803    False Negative  82

F1 score :  0.9117876658860266




Valdation Dataset

Accuracy of the network: 86 %

   True Positive  557    False Positive  58 

   True Negative  737    False Negative  148

F1 score :  0.843939393939394
Training Dataset
Accuracy of the network: 89 %
   True Positive  4561    False Positive  358 
   True Negative  6180    False Negative  901
F1 score :  0.8787207398131202

