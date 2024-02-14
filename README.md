Our research explores the effects of disconnecting connections in renowned DenseNet convolutional networks to reduce computational complexity while maintaining network performance. Our innovation introduced the "P" hyperparameter, defining the number of preceding layers that contribute their output feature maps as inputs to a given layer.

We found that as "P" value increase, the number of learned parameters and complexity rise, while the accuracy improvements become less significant. Hence, connecting a subset of prior layers offers a viable alternative to full DenseNet networks achieving comparable accuracies.

The repository contains three parts:
1. Input folder that contains all the images by divided into a training set and test set.
2. Python files with the algorithm code.
3. Article summarizes the research process, method and the results.
