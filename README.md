# crop-classification
A crop classification model which uses  MobileNetV2 architecture to classify two types of crop field images "wheat" and "corn" to give a sigmoid output if the crop field is "wheat" crop field or a "corn" crop field.Instead of using the naive transfer-learning method of directly using the weights from a pre-trained model,we fine tune our model by freezing all the layers of the model except the last 5 layers whose weights only get updated.Binary crossentropy is used as the loss function with accuracy as the perfomance metric.

# About the data
The sample train and test data is a very small part of the original dataset which was used to train the model
