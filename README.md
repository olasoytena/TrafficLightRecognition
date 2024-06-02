# TrafficLightRecognition

Trained a model to view and analyze images of traffic light to identify their color. Two models were created, one with TensorFlow's Keras and CNN, and the other with a KNN algorithm. The images were first preprocessed, turning the images pixels into RGB values to then be normalized. From there they were inserted into the models for training and testing. 
- The TensorFlow model achieved an accuracy of 1.0 or 100% with a loss of .0065. 

![alt text](https://github.com/olasoytena/TrafficLightRecognition/blob/main/model_accuracy.png)
![alt text](https://github.com/olasoytena/TrafficLightRecognition/blob/main/model_loss.png)

- The KNN model in turn only achieved an accuracy of .9862 misidentifying 4 of the images as seen in the following confusion matrix.

![alt text](https://github.com/olasoytena/TrafficLightRecognition/blob/main/confusion_matrix.png)
