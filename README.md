# Image-Captioning using Pretrained InceptionV3 and Beam Search

Pretrained InceptionV3 trained on imagenet is use to get encodings or feature vector of image and vectors are fed to LSTM model to predict the captions of images.
Beam search is used with the beam size of 3, 5 and 7

Flickr dataset is used to train model
Download from: 
https://www.kaggle.com/hsankesara/flickr-image-dataset#results.csv


# Libraries used in python3
* Keras 1.2.2
* Tensorflow 0.12.1
* numpy
* pandas
* matplotlib
* pickle
* PIL
* glob
* tqdm
