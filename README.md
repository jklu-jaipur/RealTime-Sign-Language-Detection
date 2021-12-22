# RealTime-Sign-Language-Detection
This project mainly focuses on bridging the gap using artificial intelligence
(AI) to facilitate better communication between DHH and non-signing
hearing people by providing automatic real-time sign language translation.
This is an end to end deep learning project in which we used transfer learning.
Here we have used Tensorflow object detection API and mobilenet v2.

Note:- Before running this project please setup TensorFlow Object Detection API(https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/) and CUDA v 11.2 and CUDNN. CUDA works only on supported Nvidia GPUs. We used Nvidia GTX 1050 4GB V ram to train the model.

#DATA 

The dataset of images on which we trained and tested our model is inside tensorflow folder->workspace->images

If you want to train model on your own data then you can use the dataCollection.ipynb to create your own dataset according to your need.

#LABELING THE DATASET

We have used the labelImg tool to label the dataset.

#PYTHON FILES

1. dataCollection.ipynb file can be used to create your own dataset.

2. modelling.ipynb file contains the mobilenet model config and other dependencies. Here you can modify the model config according to your need and then train the model on your dataset.

3. detection.ipynb file uses the trained model for the real-time detection(usesOpen CV).

![image](https://user-images.githubusercontent.com/44231364/147047421-fa1164b9-e5d4-4fdf-8b7f-e9792fc40018.png)
![image](https://user-images.githubusercontent.com/44231364/147047448-68d71d4a-1b08-4cf8-a1f8-9bbac039a5d7.png)





