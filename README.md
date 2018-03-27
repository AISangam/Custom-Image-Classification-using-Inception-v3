# tensorflow-image-classifier
<img src="https://github.com/koflerm/tensorflow-image-classifier/blob/master/image.png?raw=true" />
Image Classification using google pretrained model inception v3 

Transfer learning is a machine learning algorithm which utilized pretrained neural network. This file contains some details about incepetion v3 model and how to run the code for training your own images with the pretrained model.

You can further refer this link to know more about Inception architecture https://arxiv.org/pdf/1512.00567.pdf

Inception-v3 consist of two parts

Part1: It deals with feature extraction part using a convolutional neural network
Part2: classification part (Fully connected and softmax layer)

The best of transfer learning lies in saving the computation cost. Training the new images (user images) with such model does not require training Part1 which is feature extraction as it is most complex part of the model.


Inception-v3 is trained for the ImageNet Large Visual Recognition Challenge using the data from 2012. You can visit the following link to visit ImageNet (http://image-net.org/) Where models try to classify entire images into 1000 classes like "Zebra", "Dalmatian", and "Dishwasher

Moreover the model is trained using numerical computation library TensorFlow. To know and read more about Tensor flow please visit this link https://www.tensorflow.org/

To get to know how to run the code, please visit the followink link. The best part of this link will be along with the instructions to run the file there is also beatutiful and understandable documentation of understanding the inception v3 model.

	


