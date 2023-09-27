
I completed the following tasks:

- I trained a ResNet18 on the Rotation task. Based on the CIFAR10 dataloader, I first generated the rotated images and labels for the rotation task. I trained a ResNet18 on the rotation task, reported the test performance, and stored the model for the fine-tuning tasks. For the test performance, I found the lowest test loss and reported the corresponding accuracy. 
- I initialized from the Rotation model or from random weights, and fine-tuned only the weights of the final block of convolutional layers and linear layer on the supervised CIFAR10 classification task. I reported the test results and compared the performance of these two models.
- I initialized from the Rotation model or from random weights, and trained the full network on the supervised CIFAR10 classification task. I reported the test results and compared the performance of these two models. 
- ploted by performing supervised fine-tuning/training
