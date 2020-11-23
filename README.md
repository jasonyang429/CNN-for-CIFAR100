# CNN-for-CIFAR100
Neural network for CIFAR100 fine class classification

This is an example of CIFAR 100 Image Classification Task using fine classes. I have used 2 different models where the first one is the model that I have personally designed, and the second model is using transfer leraning with ResNet50 architecture. 

For my own model, I have reached ~70% Training accuracy, ~55% validation accuracy after 120 epochs, where each epochs took about 38 seconds, running on GPU.

For the transfer learning model using ResNet50 where I got insights from another person [(link here)](https://github.com/balajikulkarni/The-one-with-Deep-Learning/blob/master/TransferLearning/TransferLearning.ipynb) have reached a ~65% training accuracy and ~45% validation accuracy. This model took me 1.5 hours just for 15 epochs, where each epochs took about 420 seconds.

The evaluation task I only carried out on the transfer learning model, where it reached about 70% accuracy.
