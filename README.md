# deeplearning-birds

After self-studying on how to build an image classification model using deep learning from a range of resources, I wanted to get my hands dirty by implementing and putting my learnings into practice. Some of these resources are found below.

### Birds Image Classifier with CNNs

This is an image classification project that uses Convolutional Neural Networks (CNNs) and feature extraction from pre-trained CNNs to classify the images of birds by their species. The objectives of this project was to demonstrate:

1. Why fine-tuned pre-trained CNNs perform well with little to moderate amount of training
2. How users can present test evaluation results to locate the set of prediction classes that need more training
3. How users can localise the important objects of the image that belong to a given prediction class, using Gradient Class Activation Mapping (Grad-CAM)

I personally find objective 3 very important for ML practitioners because an understanding of what the model learns helps minimise the fear that users have in using the product (aids in user adoption), whilst also equipping the practitioner with data-driven next steps on how to fine tune the model better (model improvement and explainability).

I wrote a medium article on this project. Read up more [here](https://medium.com/@bobbycxy/birds-classification-with-pre-trained-convolutional-neural-networks-and-cam-heatmap-visualization-3d424423aaa4).

### Dataset

The dataset comprises of 525 bird species. 84635 training images, 2625 test images(5 images per species) and 2625 validation images(5 images per species). You can use this [link](https://www.kaggle.com/datasets/gpiosenka/100-bird-species) to find the dataset used in this project.

### Environment

AWS EC2 Instance - Deep Learning AMI GPU TensorFlow 2.7.3 (Ubuntu 20.04). Instance type: c5.2xlarge

(Learn how to set up your deep learning workstation with AWS [here](https://medium.com/@bobbycxy/detailed-guide-to-connect-ec2-with-vscode-2c084c265e36?source=your_stories_page-------------------------------------))
