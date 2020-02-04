# ImageClassifier_Apparels
Image Classification (or Image Identification) is one of the popular use cases for deep learning. The goal of the task is to train a model capable of identifying the main object of interest in an image. For this project, we will be training a model to predict 1 of the 10 classes of apparels. 

# Dataset
There are a total of 70,000 images (28 X 28) out of which 60,000 are training images with lables of the type of apparel (Classes = 10) and the rest 10,000 are unlabelled test images. 
The followinf is the label description:
0	T-shirt/top
1	Trouser
2	Pullover
3	Dress
4	Coat
5	Sandal
6	Shirt
7	Sneaker
8	Bag
9	Ankle boot


The metric of success is the multi-class accuracy

# Files
The "IdentifyTheApparels.ipynb" file contains the code for loading data set, training the model, running test on validation dataset and making prediction on the test data set. 

The "sample_cnn.csv" file contains the predicted labels for the 10,000 test dataset. 
