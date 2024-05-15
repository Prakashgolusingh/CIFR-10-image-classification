# CIFR-10-image-classification
In this project i have used CIFAR image dataset of 50k for training and 10k for testing trained using ANN, CNN and transfer learning.

With ANN(Artificial Neural Network) i got low accuracy of around 48.75%. Which is quite low

Then With CNN( Convolutional Neural Network) I got quit satisfactory accuracy of 79.62% which is close to 80%.

Now then I used transfer learning and got a quit impressive accuracy of 93.08 which is most accurate model among all three.

So with transfer learning approach used a pre-trained CNN model Resnet-50 with dataset "ImageNet", with excluded connected layer then trained it using my dataset CIFR-10 and got accuracy of 93.08%.

## Dimension of Image used = (32, 32, 3)

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
    
optimizer used - 'RMSprop' in transfer leaning and 'adam' in CNN and ANN

Loss function used - 'sparse_categorical_crossentropy'
