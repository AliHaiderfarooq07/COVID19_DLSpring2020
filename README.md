# MSEE19006_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

![Comparision](https://user-images.githubusercontent.com/64313566/80291414-c9c89080-8766-11ea-8727-6f5de222b6bc.PNG)


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

   True Positive  531    &nbsp;&nbsp;&nbsp;   False Positive  84 

   True Negative  868    &nbsp;&nbsp;&nbsp;   False Negative  17

F1 score :  0.9145019052803484

######Validation Dataset

Accuracy of the network: 86 %

   True Positive  458   &nbsp;&nbsp;&nbsp;   False Positive  157 
   
   True Negative 833    &nbsp;&nbsp;&nbsp;   False Negative  52

F1 score :  0.8885333333333333

###### Training Dataset

Accuracy of the network: 90 %

   True Positive  4087   &nbsp;&nbsp;&nbsp;    False Positive  832 

   True Negative  6739   &nbsp;&nbsp;&nbsp;    False Negative  342

F1 score : 0.8744

## VGG with Drop Out 
Trained Model download Link is here,https://drive.google.com/open?id=1WIoyq0GaFuVgrYdMW7BcEDihBfvfk9sS
The confusion matrox and accuracy of the dataset are as followed,
##### Test Dataset

Accuracy of the network: 93 %

   True Positive  545  &nbsp;&nbsp;&nbsp;  False Positive  70 

   True Negative  864  &nbsp;&nbsp;&nbsp;  False Negative  21

F1 score : 0.9229725

###### Validation Dataset

Accuracy of the network: 87 %

   True Positive  493  &nbsp;&nbsp;&nbsp;   False Positive  122
 
   True Negative  818  &nbsp;&nbsp;&nbsp;  False Negative  67

F1 score :0.8391

###### Training Dataset

Accuracy of the network: 90 %

   True Positive  4215 &nbsp;&nbsp;&nbsp;   False Positive  704 

   True Negative  6585  &nbsp;&nbsp;&nbsp;  False Negative  496

F1 score : 0.8754

## Resnet with only FC layers trained
The trained model can be downloaded from the link https://drive.google.com/open?id=1nSSnk1mMBG4UXbmIMyFOdQ12MiLV3pqr,
The confusion matrix and accuracy for Network is as followed,

#### Test data

Accuracy of the network: 91 %

   True Positive  522  &nbsp;&nbsp;&nbsp;  False Positive  93 

   True Negative  843  &nbsp;&nbsp;&nbsp;  False Negative  42

F1 score :  0.8854961832061069

#### Validation data

Accuracy of the network: 83 %

   True Positive  465  &nbsp;&nbsp;&nbsp;  False Positive  150 

   True Negative  788   &nbsp;&nbsp;&nbsp; False Negative  97

F1 score :  0.7901444350042481

#### Training Data

Accuracy of the network: 86 %

   True Positive  3884  &nbsp;&nbsp;&nbsp;  False Positive  1035 

   True Negative  6452  &nbsp;&nbsp;&nbsp;  False Negative  629

F1 score :  0.823579304495335
# Task 2
## VGG16 Last convolution + FC layer
The task is trained using trainable last convolution layer and fully connected layers.
The link to model is https://drive.google.com/open?id=1-DI0iQS6bselNcS5d-SnRTvQxeCt3cnQ
The confusion matrix for the model is 
#### Test Dataset

Accuracy of the network: 95 %

   True Positive  581  &nbsp;&nbsp;&nbsp;  False Positive  34 

   True Negative  857  &nbsp;&nbsp;&nbsp;  False Negative  28

F1 score :  0.9493464052287581

#### Validation dataset

Accuracy of the network: 90 %

   True Positive  550 &nbsp;&nbsp;&nbsp;   False Positive  65 

   True Negative  805  &nbsp;&nbsp;&nbsp;  False Negative  80

F1 score :  0.8835341365461847


#### Training Dataset

Accuracy of the network: 97 %

   True Positive  4724  &nbsp;&nbsp;&nbsp;  False Positive  195 

True Negative  6924   &nbsp;&nbsp;&nbsp; False Negative  157

F1 score :  0.9640816326530612





## Resnet Last convolution ( Single) + FC layer
The ResNet network last convolutional layer and the FC layer trained. The network is trained using Adam optimizer with a batch size of 128 for Epochs. The network shows superior results in comparison to the previous model. 
Link https://drive.google.com/open?id=1XtU1p5GMyeXfVUgpBWISHAVveqdsN1QA
The confusion matrix is as followed,

#### Test Dataset

Accuracy of the network: 92 %

   True Positive  584   &nbsp;&nbsp;&nbsp; False Positive  31 

   True Negative  803   &nbsp;&nbsp;&nbsp; False Negative  82

F1 score :  0.9117876658860266




#### Valdation Dataset

Accuracy of the network: 86 %

   True Positive  557  &nbsp;&nbsp;&nbsp;  False Positive  58 

   True Negative  737  &nbsp;&nbsp;&nbsp;  False Negative  148

F1 score :  0.843939393939394
Training Dataset
Accuracy of the network: 89 %
   True Positive  4561  &nbsp;&nbsp;&nbsp;  False Positive  358 
   True Negative  6180  &nbsp;&nbsp;&nbsp;  False Negative  901
F1 score :  0.8787207398131202

## VGG16 Multiple Conv + FC layer
The Link Model https://drive.google.com/open?id=1-5zlNvgee9SfaCMngXVYzbgUBUl_-nmW

#### Testing dataset

Accuracy of the network: 97 %

   True Positive  591  &nbsp;&nbsp;&nbsp;   False Positive  24 

   True Negative  864  &nbsp;&nbsp;&nbsp;   False Negative  21

F1 score :  0.9633251833740831

#### Validation Dataset

Accuracy of the network: 90 %

   True Positive  549  &nbsp;&nbsp;&nbsp;   False Positive  66 

   True Negative  814   &nbsp;&nbsp;&nbsp;  False Negative  71

F1 score :  0.8890688259109312

#### Training Dataset

Accuracy of the network: 95 %

   True Positive  4580  &nbsp;&nbsp;&nbsp;   False Positive  339 

   True Negative  6842 &nbsp;&nbsp;&nbsp;    False Negative  239

F1 score :  0.9406448962826043
## Resnet18 with multiple convolution layer and FC layers
The Link to model https://drive.google.com/open?id=1IBxQKA0PEw1OvOh75LiuyOU1bTxJkUh6

#### Testing dataset

Accuracy of the network: 97 %

   True Positive  590  &nbsp;&nbsp;&nbsp;   False Positive  25 

   True Negative  866  &nbsp;&nbsp;&nbsp;   False Negative  19

F1 score :  0.9640522875816994


#### Validation Dataset

Accuracy of the network: 91 %

   True Positive  549  &nbsp;&nbsp;&nbsp;   False Positive  66 

   True Negative  824 &nbsp;&nbsp;&nbsp;    False Negative  61

F1 score :  0.8963265306122449





#### Training Dataset

Accuracy of the network: 96 %

   True Positive  4607 &nbsp;&nbsp;&nbsp;    False Positive  312 

   True Negative  6980  &nbsp;&nbsp;&nbsp;   False Negative  101

F1 score :  0.9570998234133167


## VGG16 Entire 

The model download link is https://drive.google.com/open?id=1_ieamuIhsDxSxXT2UxZB2SP_cDXRm41h


#### Test Dataset

Accuracy of the network: 96 %

   True Positive  595  &nbsp;&nbsp;&nbsp;   False Positive  20 

   True Negative  859 &nbsp;&nbsp;&nbsp;    False Negative  26

F1 score :  0.9627831715210357

#### Validation Dataset

Accuracy of the network: 91 %

   True Positive  543  &nbsp;&nbsp;&nbsp;   False Positive  72 

   True Negative  835  &nbsp;&nbsp;&nbsp;   False Negative  50

F1 score :  0.8990066225165563

#### Training Dataset

Accuracy of the network: 97 %

   True Positive  4728 &nbsp;&nbsp;&nbsp;     False Positive  191 
 
   True Negative  7024  &nbsp;&nbsp;&nbsp;   False Negative  57

F1 score :  0.9744435284418796

## ResNet Entire

The doanload link is https://drive.google.com/open?id=1Zrxn4SVdPNB94CH95FzaNhslafya5pIF


#### Test Dataset

Accuracy of the network: 95 %

   True Positive  548  &nbsp;&nbsp;&nbsp;   False Positive  67 
 
   True Negative  883 &nbsp;&nbsp;&nbsp;    False Negative  2

F1 score :  0.940878201634877

#### Validation Dataset

Accuracy of the network: 89 %

   True Positive  476   &nbsp;&nbsp;&nbsp;  False Positive  139 

   True Negative  869  &nbsp;&nbsp;&nbsp;   False Negative  16

F1 score :  0.8601200000

#### Training Dataset

Accuracy of the network: 94 %

   True Positive  4301  &nbsp;&nbsp;&nbsp;   False Positive  618 

   True Negative  6984  &nbsp;&nbsp;&nbsp;   False Negative  97

F1 score :  0.9235987777
