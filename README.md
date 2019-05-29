# Airbus Ship Detection Challenge

We participated in an inactive with late submission Kaggle competition, Airbus Ship Detection Challenge. Ship detection has a wide range of real life application, in the areas of maritime traffic, monitoring of marine pollution, border control, etc. The challenge is to detect ships in satellite images and generate mask images of ships as shown in Figure 1. The final model we choose is a transfer learning model for image classification to classify if an image contains a ship or not and Mask R-CNN, a deep convolutional neural network architecture, for detection and segmentation of ships. Mask R-CNN is a flexible framework developed for the purpose of object instance segmentation. This model is an implementation of this Mask R-CNN technique on Python and Keras. It generates bounding boxes and segmentation masks for each instance of an object in a given image. We implement the convolutional neural network using the Mask-RCNN provided by Keras and run the code on a Google Cloud Platform with four Intel i7 CPUs, 32 GB memory and 1 NVIDIA Tesla T4 GPU. In the public leaderboard, our score is $0.67534$. In the private leaderboard, our score is $0.81560$. There are over 900 submission, and we are around the 800th position in the private leaderboard and 500th position in the public leaderboard.
