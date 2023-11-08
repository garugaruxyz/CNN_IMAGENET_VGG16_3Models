# CNN_IMAGENET_VGG16_3Models
 
he task of the assignment is Transfer Learning using a CNN pretrained on IMAGENET.

The suggested architecture is the VGG16.

The CNN should be used as fixed feature extractor on a new task on the CIFAR10 dataset (number of classes=10). 

The report must contain:
- the use of the pretrained CNN as feature extractor considering different layers (at least 3 different choices)
- the chosen "classical" classifier, describing the chosen hyper-parameters (to be kept fixed for all the different cuts performed, e.g. C=1 in SVM, or using a k-NN with k=5, etc.)
- for each transfer learning experiment:

1. the details about the chosen layer
2. the plot of the classification performance on train/test (of the new task)
