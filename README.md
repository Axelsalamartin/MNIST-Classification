# MNIST-Classification

## Perceptron : 1 layer and multi-layer :

Using a 1 layer perceptron first and then a multi layer perceptron to see the improvements in the task execution.
They both take few seconds to train (on 2000 training steps).

Explanations of the code are in the notebook.

Few twists could be made to make the models more accurate :
- first by increasing the number of layers or the number of neurons (this helps but going too far can be useless and cost heavy in training time : everything is about balance )
- decreasing the learning rate and increasing the number of training iterations but once again it's about balance : if the learning rate is low the model should be more accurate but it'll take longer to train because you will have to make more training iterations. And if it's really too low the model could never converge.
- Changing the cost function or the optimizer (RMSprop, Adam..)
- Add drop out to force the layers to use other neurons path and prevent overfitting





