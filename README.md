# 102-Flower-Species-Classification-Project

NOTE: This project is not over. The final step is to use the trained model in a web application which will be done soon.

NOTE 2: The .ipynb file was constructed and executed in the Colab environment.

* Abstract: A CNN classifier was trained based on the Deep Learning DenseNet-161 pre-trained model for the classification of 102 different flower species. It was used a PyTorch framework and the accuracy reached 89.1% on the test set for the top 1 prediction probability and 98.4% for the top 5, yielding a successful prediction for a real life model application.

This work is based on the capstone project of the Pytorch Scholarship Challenge on Udacity. A deep learning algorithm is trained for an image classification task using a dataset containing images of 102 different species of flowers.

In the AI era, artificial inteligence algorithms will be incorporated into more and more everyday applications. An app that depicts a flower specie's name your camera is looking at might be wanted. For this, a way of seeing an image and then classifying it from a pool of labels may be enough to give what is needed. In such a situation, you want to include an image classifier in a smart phone app. Hence, we can use a deep learning model, pre-trained on hundreds of thousands of images as part of the overall application architecture.

In this project, I'll present how to train just a part of a pre-trained CNN model (the classifier) to be used as an image labeling algorithm, as a way of saving time and sculpting a model to suit our needs, so it can be exported for use in an application.

The project is broken down into five major steps:
1) Data exploration
2) Dataset loading and preprocessing
3) Train the image classifier on the dataset
4) Use the trained model to predict new content
5) Conclusion
