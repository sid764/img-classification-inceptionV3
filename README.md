TensorFlow Keras model which uses Inception-V3 convolutional neural network(48 layers) to classify rock, paper, scissor images. 
Model is trained by moving training_set images to separate directories for each class. Images are rescaled and augmented(horizontal flip, rotation, height-width shift, zooming are considered). Used reguralization technique Dropout to prevent overfitting.
Training is cancelled on reaching 99% test accuracy using Callback; maximum 20 epochs.
This model gave test accuracy of 99.17% and validation accuracy of 95.16%.
