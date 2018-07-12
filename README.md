# MNIST-Classification

## Perceptron : 1 layer and multi-layer :

Using a 1 layer perceptron first and then a multi layer perceptron to see the improvements in the task execution.
They both take few seconds to train (on 2000 training steps).

Explanations of the code are in the notebook.

Few twists could be made to make the model more accurate :
- first by increasing the number of layers or neurons (this help but going too far can be useless and cost heavy in training time : everything is about balance )
- decreasing the learning rate and increasing the number of training iterations but one again it's about balance : if the learning rate is lower the model will be more accurate but it'll take longer to train because you will have too make more training iterations.
- Changing the cost function or the optimizer (RMSprop, Adam..)
- Add drop out to force the layer to use other neurons path and prevent overfitting

But to really get higher accuracy : a convolutionnal network would be a good way to go since it's known to best extract features in image classification task ("Inception", "VGGnet" and others have shown great results in the image classification competition called "ImageNet").




