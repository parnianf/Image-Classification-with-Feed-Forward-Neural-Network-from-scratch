# Image-Classification-with-Feed-Forward-Neural-Network-from-scratch


In this project, I implement a feed-forward neural network from scratch by using Numpy library to categorize images of `CIFAR-10` dataset. Each image is first flattened as a vector and then is given as the network input. Each element of this vector (equivalent to one image pixel) is a feature. Based on these features and by making nonlinear combinations, the network is supposed to adjust the weight of the connections between its layers so that its output, with the least error, correctly predicts the corresponding input image class.
### Objectives
- Data visualization and preprocessing, including min-max normalization and one-hot encoding of labels
- Implementation of Identical, Relu, LeakyRelu, Sigmoid, Softmax, and Tanh activation functions
- Implementation of CrossEntropy loss function
- Implementation of Layer and FeedForwardNN
- Test data classification and evaluate the impacts of network weighting methods, learning rate, activation function, and batch size
