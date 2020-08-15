# ABOUT THE DATA
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.  
  
Here are the classes in the dataset, as well as 10 random images from each:  
  
![CIFAR10](https://cdn.analyticsvidhya.com/wp-content/uploads/2020/02/1_sGochNLZ-qfesdyjadgXNw.png)  
  
But for our project we will only be using a subset of this dataset with three classes namely aeroplane, car and bird. Our training data will contain 15,000 images and validation data will have 3,000 images.  
  
# DEPENDANCIES 
We have used numpy, tensorflow and keras for this project. If you don't have them on your local machine yet you can pip install them using:  
```html  
pip install numpy
```  
We have used the latest version of tensorflow here i.e. tensorflow2.0. For installation purpose you can refer [installing tensorflow2.0 for windows](https://www.tensorflow.org/install).  
  
As we are using keras implementation on tensorflow backend so we don't need to install it manually.  
  
# DOWNLOADING THE DATA  
The entire dataset is available on kaggle and can be downloaded using the download link i.e. [click here to download the CIFAR10 data](https://www.kaggle.com/valentynsichkar/cifar10-preprocessed). However, the dataset is also available on keras datasets so for this project I have directly imported the preprocessed data from there.  
  
# WHY THIS PROJECT
This was just a practice project to improve my understanding of the topic. I hope you find it helpful too. Try out the code by writing it out yourself or you can simply clone it on your local machine using  
```html
git clone https://github.com/kotiyalanurag/CIFAR10-and-CNN.git
```  
# LICENSE  
[GPL-3.0 License](https://github.com/kotiyalanurag/CIFAR10-and-CNN/blob/master/LICENSE)  
