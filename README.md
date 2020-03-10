## Image_Segmentation_Model
### A Fully Convolutional Neural Network based model for Semantic Segmentation

In this project, a segmentation task has been performed for a small sample dataset. The dataset can be downloaded from this [link](https://drive.google.com/file/d/0B0d9ZiqAgFkiOHR1NTJhWVJMNEU/view), which has been prepared by Divam Gupta.

A FCN-8 architecture has been used for this task, which uses CNN to convert each of the image pixels to categories.For details of FCN-8, please refer to this [paper](https://arxiv.org/abs/1411.4038). 

### Model Performance
![performance](https://github.com/Niloy-Chakraborty/Fully-Convolutional-Network-for-Image_Segmentation/blob/master/loss_acc_fcn_8.png)

Opensource h5 pre-trained weights of VGG-16 architecture has been initialised at first. The model shows the Training Accuracy of 72% and Training Loss of 0.9
