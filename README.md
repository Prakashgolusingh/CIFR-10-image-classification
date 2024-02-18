# CIFR-10-image-classification
In this project i have used a image dataset of 50k , and trained using ANN with 40k dataset but i got low accuracy of around 40% .
So with transfer learning approach used a pre-trained CNN model Resnet-50 with dataset Imagenet, with excluded connected layer then trained it using my dataset CIFR-10 and got accuracy of 93.8%.

##Dimension of Image used = (32, 32, 3)

Different classes used-
1.  Airplane
2.  Automobile
3.  Bird
4.  Cat
5.  Deer
6.  Dog
7.  Frog
8.  Horse
9.  Ship
10.  Truck

    Input Dimesion of ResNet-50 model - (256, 256, 3)
    
optimizer used - 'RMSprop'

Loss function used - sparse_categorical_crossentropy
