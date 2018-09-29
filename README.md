# Image Captioning


This is an image captioning project using 8k Flickr dataset and CNN-RNN (encoder-decoder) model.

First lets visualize a sample image of the Flickr 8K dataset. There are 8000 more images in the same dataset. The dataset is split into three parts i.e. training data, testing data and validation data.

Training data contains 6000 images Validation and testing data contains close to 1000 images each. For each image, there are five alternate captions provided in the dataset.

For building a prediction model, we use CNN-RNN model. For CNN, we use VGG-16 (pretrained) model. For RNN, we use LSTM cells.
