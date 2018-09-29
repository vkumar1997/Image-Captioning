# Image Captioning


This is an image captioning project using 8k Flickr dataset and CNN-RNN (encoder-decoder) model.

First lets visualize a sample image of the Flickr 8K dataset. There are 8000 more images in the same dataset. The dataset is split into three parts i.e. training data, testing data and validation data.

Training data contains 6000 images Validation and testing data contains close to 1000 images each. For each image, there are five alternate captions provided in the dataset.

For building a prediction model, we use CNN-RNN model. For CNN, we use VGG-16 (pretrained) model. For RNN, we use LSTM cells.


![alt text](https://github.com/vkumar1997/Image-Captioning/blob/master/test_images/3603116579_4a28a932e2.jpg)
startq the baseball player in the orange uniform is playing to the ball endq

![alt text](https://github.com/vkumar1997/Image-Captioning/blob/master/test_images/2469498117_b4543e1460.jpg)
startq greyhound greyhound racing on track endq

![alt text](https://github.com/vkumar1997/Image-Captioning/blob/master/test_images/3465606652_f380a38050.jpg)
startq boy in red shirt is holding her arms endq

![alt text](https://github.com/vkumar1997/Image-Captioning/blob/master/test_images/2293424366_7b5fcd2398.jpg)
startq boy in blue uniform is playing basketball endq

![alt text](https://github.com/vkumar1997/Image-Captioning/blob/master/test_images/1397923690_d3bf1f799e.jpg)
startq man is standing on snowy mountain endq


