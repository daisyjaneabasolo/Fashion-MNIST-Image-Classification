# Fashion-MNIST-Image-Classification

#1. What is the Fashion MNIST dataset? 

 - Fashion MNIST is a black-and-white images of clothes that we can use to train and test a model to recognize different clothing items.

#2. Why do we normalize image pixel values before training?

 -  We divide the pixel values by 255 so they are between 0 and 1. This makes it easier and faster for the model to learn.
   
#3. List the layers used in the neural network and their functions.
  
 -  The model has a Flatten layer to change the 2D image into a 1D array, a Dense layer with 128 neurons that helps learn patterns, and a Dense output layer with 10 neurons for the 10 classes.

#4. What does an epoch mean in model training?
  
 -  An epoch is when the model goes through all the training images one time.

#5. Compare the predicted label and actual label for the first test image.
  
-   The predicted label is what the model thinks the image is, and we check if it matches the actual label to see if it got it right.

#6. What could be done to improve the model’s accuracy?
 
-   We can make the model better by adding more layers, training it for more epochs, using convolutional layers, or changing some settings like the learning rate.


This is my Google Colab (https://colab.research.google.com/drive/10D-XRqZ4Ny3eRpGz96sdYGiKrnnbmQVN?usp=drive_link)

