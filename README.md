# Image-caption-generator-using-deep-learning.

# Description

The objective of our project is to learn the concepts of a CNN and LSTM model and build a working model of Image caption generator by implementing CNN with LSTM.
In this Python project, we will be implementing the caption generator using CNN (Convolutional Neural Networks) and LSTM (Long short term memory). The image features 
will be extracted from Xception which is a CNN model trained on the imagenet dataset and then we feed the features into the LSTM model which will be responsible for 
generating the image captions.

# Requiremnets

1.Python 3
1.Tensorflow (Tested with tensorflow-gpu), Keras

# Dataset

For the image caption generator, we will be using the Flickr_8K dataset. There are also other big datasets like Flickr_30K and MSCOCO dataset but it can take weeks just to 
train the network so we will be using a small Flickr8k dataset. The advantage of a huge dataset is that we can build better models.

#Implementation

1.First, we import all the necessary packages
1.Getting and performing data cleaning
1.Extracting the feature vector from all images
1.Loading dataset for Training the model
1.Tokenizing the vocabulary
1.Create Data generator
1.Defining the CNN-RNN model
1.Training the model
1.Testing the model
